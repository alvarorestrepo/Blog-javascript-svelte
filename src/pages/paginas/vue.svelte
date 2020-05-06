<script>
  import { Col, Row } from "sveltestrap";
  import Texto from "../_componentes/Textovue.svelte"
  let vue = "/img/vue1.jpg";
</script>

<Row>
  <Col>
    <img src={vue} width="100%"  alt="vue" />
  </Col>
</Row>
<Texto/>