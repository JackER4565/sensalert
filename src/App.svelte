<script>
  import sensAlert from './assets/sensalert-logo.png'
</script>

<main>
  <div>
      <img src={sensAlert} class="logo" alt="SensAlert Logo" />
  </div>
  <h1>SensAlert</h1>

  <div class="card">
    Muy pronto...
  </div>


  <footer class="footer">
    © Copyright 2024 SensAlert - Web by <a href="https://luminn.ar" target="_blank">Luminn</a>
  </footer>
</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .footer {
    color: #888;
    font-size: 0.8em;
    text-align: center;
    margin-top: 1em;
    margin-bottom: 1em;
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
  }
</style>
