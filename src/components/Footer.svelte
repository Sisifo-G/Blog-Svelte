<script>
  let fecha = new Date();
  let ano = fecha.getFullYear();
</script>


<style>
  .Footer {
    background: #121232;
    color: white;
    padding: 1.5em 0;
    margin: 2em 0 0 0;
    font-size: 13px;
    font-weight: 300;
  }

  .Footer-container {
    display: grid;
    grid-template-columns: minmax(auto, 1024px);
    justify-content: center;
    align-items: center;
  }

  .Footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .Footer-svelte {
    display: flex;
    align-self: center;
  }

  .Footer-svelte img {
    margin: 0 0 0 0.5em;
  }
</style>

<footer class="Footer">
  <div class="Footer-container">
    <div class="Footer-content">
      <div class="Footer-copy">CopyRight &copy; <strong>{ano}</strong></div>
      <div class="Footer-svelte">
        Proudly 💪 powered by svelte
        <img src="svelte.png" alt="Svelte" />
      </div>
    </div>
  </div>
</footer>
