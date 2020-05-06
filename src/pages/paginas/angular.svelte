<script>
  import { Col, Row } from "sveltestrap";
  import Footer from '../_componentes/Footer.svelte'
  import Texto from '../_componentes/Textoangular.svelte'
  let angular = "/img/angular1.png";
</script>

<Row>
  <Col>
    <img src={angular} width="100%"  alt="angular" />
  </Col>
</Row>

<Texto/>

<Footer/>
