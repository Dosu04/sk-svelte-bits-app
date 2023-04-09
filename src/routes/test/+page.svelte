<script>
    let saved = false;
    
    function handleClick() {
      saved = !saved;
    }
  </script>
  
  <style>
    .saved {
      fill: green;
    }
    
    .unsaved {
      fill: gray;
    }
  </style>
  
  <svg viewBox="0 0 24 24" width="24" height="24" class="{saved ? 'saved' : 'unsaved'}" on:click={handleClick}>
    <path d="M17.28 3.51L20.49 6.72L17.28 9.93L16.5 9.14L18.36 7.28L11.99 7.28V2.99C11.99 2.45 11.54 2 11 2H4C3.45 2 3 2.45 3 2.99V21C3 21.55 3.45 22 4 22H17.99C18.54 22 19 21.55 19 21V5.64L17.28 3.91V3.51ZM16.99 19.42L6.99 19.42V4.99H10.99V8.99H14.99V19.42H16.99Z"/>
  </svg>
  