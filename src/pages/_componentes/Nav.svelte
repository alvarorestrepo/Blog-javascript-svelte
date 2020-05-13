<script>
  import { url } from "@sveltech/routify";
</script>

<style>
  .navbar {
    padding: 0.1rem 1rem;
    position: fixed;
    z-index: 1;
    width: 100%;
  }
  .nav-link {
    font-size: 1.3rem;
    margin-right: 1rem;
    margin-top: 1px;
    margin-bottom: 1px;
  }
  a {
    font-size: 4rem;
    margin-top: -1rem;
    margin-bottom: -1rem;
  }
  .color {
    background: #ffef00;
  }
</style>

<nav class="navbar navbar-expand-lg navbar-light color">
  <a class="navbar-brand mr-4" href={$url('./')}>
    <strong>JS</strong>
  </a>
  <button
    class="navbar-toggler"
    type="button"
    data-toggle="collapse"
    data-target="#navbarSupportedContent"
    aria-controls="navbarSupportedContent"
    aria-expanded="false"
    aria-label="Toggle navigation">
    <span class="navbar-toggler-icon" />
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">

      <li class="nav-item">
        <a class="nav-link" href={$url('./paginas/inicio')}>
          Inicio
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href={$url('./paginas/angular')}>
          Angular
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href={$url('./paginas/react')}>
          React
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href={$url('./paginas/vue')}>
          Vue
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href={$url('./paginas/svelte')}>
          Svelte
        </a>
      </li>

    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input
        class="form-control mr-sm-2"
        type="search"
        placeholder="Search"
        aria-label="Search" />
      <!-- <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button> -->
    </form>
  </div>
</nav>