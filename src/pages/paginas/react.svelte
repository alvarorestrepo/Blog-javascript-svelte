<script>
  import { Col, Row } from "sveltestrap";
  import Texto from "../_componentes/Textoreact.svelte"
  let react = "/img/react1.png";
</script>
<style>
img{
  margin-top: 50px;
}
</style>

<Row>
  <Col>
    <img src={react} width="100%"  alt="react" />
  </Col>
</Row>

<Texto/>
