<script>
  let showModal = false; // state variable to show/hide the modal
  
  let name = ''; // form input value
  
  function handleClick() {
    showModal = true; // show the modal when the image is clicked
  }
  
  function closeModal() {
    showModal = false; // hide the modal when the close button is clicked
  }
  
  function handleSubmit() {
    // do something with the form data
    console.log(`Name: ${name}`);
    closeModal();
  }
</script>

<style>
  /* styles for the modal */
  .modal {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .modal-content {
    background-color: #fff;
    padding: 1rem;
    border-radius: 0.25rem;
    max-width: 90%;
    max-height: 90%;
    overflow-y: auto;
  }
  
  .close-btn {
    position: absolute;
    top: 0.5rem;
    right: 0.5rem;
    font-size: 1.5rem;
    cursor: pointer;
  }
  
  input {
    display: block;
    margin-bottom: 1rem;
    width: 100%;
    padding: 0.5rem;
    border-radius: 0.25rem;
    border: 1px solid #ccc;
  }
  
  button {
    margin-right: 0.5rem;
  }
</style>

<img src="/images/home/profile.jpg" alt="" on:click={handleClick} />

{#if showModal}
  <div class="modal">
    <div class="modal-content">
      <span class="close-btn" on:click={closeModal}>&times;</span>
      <form on:submit|preventDefault={handleSubmit}>
        <label for="name">Name:</label>
        <input type="text" id="name" bind:value={name} required />
        <div class="btn-group">
          <button type="submit">Submit</button>
          <button type="button" on:click={closeModal}>Close</button>
        </div>
      </form>
    </div>
  </div>
{/if}
