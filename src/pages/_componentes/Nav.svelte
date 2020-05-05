<script>
import { url } from '@sveltech/routify'
</script>

<nav class=" navbar navbar-expand-lg navbar-light bg-warning">
  <a class="navbar-brand mr-4 pt-1" href={$url('./')}> <strong>JS</strong> </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link" href={$url('./paginas/inicio')}> <strong>Inicio</strong> </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href={$url('/paginas/angular')}> <strong>Angular</strong> </a>
      </li>
      <li class="nav-item">
        <a class="nav-link"href={$url('/paginas/react')}> <strong>React</strong> </a>
      </li>
      <li class="nav-item">
        <a class="nav-link"href={$url('/paginas/svelte')}> <strong>Svelte</strong> </a>
      </li>
      
    </ul>
  </div>
</nav>

<style>

.navbar{
    padding: .1rem 1rem;
}
.nav-link{
  font-size: 1.3rem;
  margin-right: 1rem;
  
}
a{
  font-size: 4rem;
  margin-top: -1rem;
  margin-bottom: -1rem;
}
</style>