<script>
  import { Col, Row, Container } from "sveltestrap";
  import Img from '../_componentes/Img.svelte'
  let img = "/img/vuep.png";
</script>

<style>
  p {
    text-align: justify;
    font-size: 1.3rem;
  }

  .titulo1 {
    font-size: 3.2rem;
  }
</style>

<br />

<Container>

  <Row>

    <Img {img}/>
    <Col xs="12" sm="6">
      <p>
        Vue es un framework open source de JavaScript, el cual nos permite
        construir interfaces de usuarios de una forma muy sencilla. La curva de
        aprendizaje, desde mi punto de vista, es relativamente baja, claro,
        debes conocer muy bien JavaScript, saber trabajar con callbacks,
        promesas, objetos, entre otros temas más.
      </p>
    </Col>

  </Row>
  <br />
  <Row>
    <Col>
      <p>
        Si queremos hacer uso de Vue no será necesario instalar absolutamente
        nada en nuestra computadora, sí así lo deseamos podemos utilizar este
        framework mediante un CDN.
      </p>
    </Col>

  </Row>
  <Row>
    <Col>
      <p>
        Vue fue creado por Evan You ex trabajador de Google, quien, es
        importante mencionar, fue desarrollador Angular. Vue fue lanzado en el
        año 2014. Aunque inicialmente fue pensado para ser un biblioteca
        personal, la comunidad hizo que el proyecto creciera a un ritmo
        impresionante, posicionándolo hoy en día como uno de los Frameworks web
        más populares, junto con Angular y React.
      </p>
    </Col>
  </Row>
  <Row>
    <Col>
      <p>
        Una de las características más importantes de Vue es el trabajo con
        componentes. Un componente Vue, en términos simples, es un elemento el
        cual se encapsula código reutilizable. Dentro de un componente podremos
        encontrar etiquetas HTML, estilos de CSS y código JavaScript. Los
        componentes nos permiten desarrollar proyectos modularizados y fáciles
        de escalar, si nosotros así lo deseamos podemos reemplazar un componente
        por otro de una forma muy sencilla, como si de piezas de lego se
        tratasen.
      </p>
    </Col>
  </Row>

</Container>

<Container>
  <h1 class="titulo1" align="center">
    <strong>Su popularidad</strong>
  </h1>
</Container>
<Container>
  <Row>
    <Col>
      <p>
        Sin duda Vue tiene características muy interesantes, pero, seamos
        sinceros, Vue no ha inventado nada nuevo, de hecho, todo lo que hemos
        mencionado los podemos encontrar en otros Frameworks Web, entonces ¿Por
        qué es tan popular? La respuesta es relativamente sencilla. Vue es
        popular por que ha sabido tomar e implementar lo mejor que tienen otros
        frameworks web y ha sabido desechar todo lo que no le aporta valor al
        producto.
      </p>
    </Col>
  </Row>

  <Row>
    <Col>
      <p>
        A diferencias de otros frameworks web, en donde ya encontramos muchos
        features listo para ser usados con Vue esto no es así, pero no nos
        preocupes, podemos ir agregando funcionalidad de terceros a nuestro
        proyecto según nuestras necesidades, esto tiene ventajas, por ejemplo,
        tenemos mayor control sobre qué se utiliza, además, que el tamaño de
        nuestra aplicación será considerablemente menor que el de otros
        frameworks out of the box, lo cual sin duda mejora la velocidad de
        nuestra página web.
      </p>
    </Col>
  </Row>

</Container>
