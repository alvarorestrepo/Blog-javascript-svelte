<script>
  import { Col, Row, Container } from "sveltestrap";
  export let img = {};
</script>

<style>
  .zoom:hover {
    width: 200%;
    position: absolute;
    z-index: 1;
    transition: 0.5s;
  }
</style>

<Col xs="12" sm="6">
  <img class="zoom" src={img} alt="" width="100%" />
</Col>
