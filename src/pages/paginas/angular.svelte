<script>
  import { Col, Row } from "sveltestrap";
  import Texto from '../_componentes/Textoangular.svelte'
  let angular = "/img/angular1.png";
</script>
<style>
img{
  margin-top: 50px;
}
</style>

<Row>
  <Col>
    <img src={angular} width="100%"   alt="angular" />
  </Col>
</Row>

<Texto/>


