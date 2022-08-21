<button>
  <slot></slot>
</button>


<style>
  button {
    width: 100px;
    border-radius: 8px;
    border: 2px solid transparent;
    padding: 0.6em 1.2em;
    font-size: 1em;
    font-weight: 500;
    font-family: inherit;
    background-color: #1a1a1a;
    cursor: pointer;
    transition: border-color 0.25s;
  }  
  button:hover {
    border-color: #774cda;
  }
</style>

