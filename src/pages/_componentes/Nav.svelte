<script>
import { url } from '@sveltech/routify'
</script>

<nav class=" navbar navbar-expand-lg navbar-light bg-warning">
  <a class="navbar-brand mr-4 pt-1" href={$url('./')}> <h1><strong>JS</strong></h1> </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link" href={$url('./paginas/inicio')}>Inicio</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href={$url('/paginas/angular')}>Angular</a>
      </li>
      <li class="nav-item">
        <a class="nav-link"href={$url('/paginas/react')}>React</a>
      </li>
      <li class="nav-item">
        <a class="nav-link"href={$url('/paginas/svelte')}>React</a>
      </li>
      
    </ul>
  </div>
</nav>

<style>

.navbar{
    padding: .1rem 1rem;
}
</style>