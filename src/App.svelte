<script>
  import poiemaLogo from './assets/poiema.png'

  const currentYear = new Date().getFullYear();
</script>

<main>
  <header>
    <img src={poiemaLogo} alt="Poiema" />
    <h1 class="center">Super Seed 2023 | Poiema CWB</h1>
  </header>

  <div class="content">
    <p class="center">Você que tá afim de aprender coisas novas, pode escolher as opções abaixo:</p>

    <ul>
      <li>
        <div class="card">
          <h3>Aulas de guitarra <span aria-label="Emoji de guitarra" role="img">🎸</span></h3>
          <p>Pra você que quer iniciar no mundo da música, ou quer aprimorar os seus conhecimentos!</p>

          <button>Quero esse</button>
          <a href="https://wa.me/5541991670404">Chamar no WhatsApp</a>
        </div>
      </li>

      <li>
        <div class="card">
          <h3>Aulas de front-end <span aria-label="Emoji de guitarra" role="img">💻</span></h3>
          <p>Pra você que quer aprender possível nova profissão, entrando de cabeça no mundo da programação; ou então, já sabe um pouco do assunto mas quer conhecer mais ainda.</p>

          <button>Quero esse</button>
          <a href="https://wa.me/5541991670404">Chamar no WhatsApp</a>
        </div>
      </li>
    </ul>
  </div>

  <footer>jlozovei {currentYear}</footer>
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
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>
