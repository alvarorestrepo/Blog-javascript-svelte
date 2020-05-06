<script>
  import { Col, Row } from "sveltestrap";
  import Footer from '../_componentes/Footer.svelte'
  let vue = "/img/vue1.jpg";
</script>

<Row>
  <Col>
    <img src={vue} width="100%"  alt="vue" />
  </Col>
</Row>

<Footer/>
