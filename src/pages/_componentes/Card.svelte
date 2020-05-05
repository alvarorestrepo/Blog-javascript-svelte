<script>
  import {
   Col,
    Row
  } from "sveltestrap";
  import { goto } from '@sveltech/routify'
  let angular = "/img/1.png";
  let react = "/img/2.png"
  let vue = "/img/3.png"
  let svelte = "/img/4.png"

  function goan(){
      $goto('/paginas/angular')
  }
  function gore(){
      $goto('/paginas/react')
  }
  function govu(){
      $goto('/paginas/vue')
  }
  function gosv(){
      $goto('/paginas/svelte')
  }
</script>

<style>
  .contenedor {
    margin: 50px;
  }
  
  .boton{
      height: 320px;
      width: 320px;
      border: none;
     box-shadow: 2px 2px 10px #999;
     border-radius: 20px;
    background-color: white;
  }
</style>



<div class="contenedor">
  <Row>
    <Col xs="12" sm="12" md="6" lg="3">
     <button on:click={goan}  class="boton"> <img class="img" src={angular} width="90%" alt=""></button>
    </Col>

    <Col xs="12" sm="12" md="6" lg="3">
       <button on:click={gore}  class="boton"> <img class="img" src={react} width="90%" alt=""></button>
    </Col>
 
    <Col xs="12" sm="12" md="6" lg="3">
       <button  on:click={govu} class="boton"> <img class="img" src={vue} width="90%" alt=""></button>
    </Col>
  
    <Col xs="12" sm="12" md="6" lg="3">
       <button on:click={gosv} class="boton"> <img class="img" src={svelte} width="80%" alt=""></button>
    </Col>
  </Row>
</div>
