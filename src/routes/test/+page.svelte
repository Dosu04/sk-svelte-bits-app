<script>
    let count = 0;
    let liked = false;
  
    function like() {
      if (!liked) {
        count++;
        liked = true;
      } else {
        count--;
        liked = false;
      }
    }
  </script>
  
  <button class="Like-Button" on:click={like}>
    {#if liked}
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="red" class="bi bi-heart-fill" viewBox="0 0 16 16">
        <path fill-rule="evenodd" d="M8 1.314C12.438-3.248 23.534 4.735 8 15-7.534 4.736 3.562-3.248 8 1.314z"/>
      </svg>
    {:else}
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="white" class="bi bi-heart-fill" viewBox="0 0 16 16">
        <path fill-rule="evenodd" d="M8 1.314C12.438-3.248 23.534 4.735 8 15-7.534 4.736 3.562-3.248 8 1.314z"/>
      </svg>
    {/if}
    
    <span>{count}</span>
  </button>
  
  <style>
    .Like-Button {
      background-color: transparent;
      border: none;
      cursor: pointer;
      display: flex;
      align-items: center;
    }
    
    .Like-Button svg {
      margin-right: 5px;
      vertical-align: middle;
    }
  </style>
  