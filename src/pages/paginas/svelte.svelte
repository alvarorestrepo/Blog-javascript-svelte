<script>
  import { Col, Row } from "sveltestrap";
  import Texto from "../_componentes/Textosvelte.svelte"
  let s = "/img/s1.jpg";
</script>

<Row>
  <Col>
    <img src={s} width="100%"  alt="svelte" />
  </Col>
</Row>
<Texto/>