<script>
  import {
   Col,
    Row,
    Container
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
 
  .boton{
      height: 260px;
      width: 260px;
      border: none;
     box-shadow: 2px 2px 10px #999;
     border-radius: 20px;
    background-color: white;
    align-content: center;
    margin-bottom: 20px
  }
  .boton:hover{
    /* height: 280px;
      width: 280px; */
       box-shadow: 6px 6px 20px rgb(136, 134, 134);
      transition-duration: 0.5s;
  }
</style>

<Container>
  <Row>
    <Col align="center" xs="12" sm="12" md="6" lg="3">
     <button on:click={goan}  class="boton"> <img class="img" src={angular} width="90%" alt=""></button>
    </Col>

    <Col align="center" xs="12" sm="12" md="6" lg="3">
       <button on:click={gore}  class="boton"> <img class="img" src={react} width="90%" alt=""></button>
    </Col>
 
    <Col align="center" xs="12" sm="12" md="6" lg="3">
       <button  on:click={govu} class="boton"> <img class="img" src={vue} width="90%" alt=""></button>
    </Col>
  
    <Col align="center" xs="12" sm="12" md="6" lg="3">
       <button on:click={gosv} class="boton"> <img class="img" src={svelte} width="80%" alt=""></button>
    </Col>
  </Row>
</Container>
