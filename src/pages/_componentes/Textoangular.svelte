<script>
  import { Col, Row, Container } from "sveltestrap";
  import Img from "../_componentes/Img.svelte"
  let img = '/img/angularp.png'
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
        AngularJS es Javascript. Es un proyecto de código abierto, realizado en
        Javascript que contiene un conjunto de librerías útiles para el
        desarrollo de aplicaciones web y propone una serie de patrones de diseño
        para llevarlas a cabo. En pocas palabras, es lo que se conoce como un
        framework para el desarrollo, en esta caso sobre el lenguaje Javascript
        con programación del lado del cliente.
      </p>
    </Col>

  </Row>
  <br />
  <Row>
    <Col>
      <p>
        Puedes encontrar el proyecto de AngularJS en su propio sitio web:
        AngularJS, Superheroic JavaScript MVW Framework. Al ser un proyecto de
        código abierto cualquier persona con un poco de curiosidad echar un
        vistazo con profundidad y ver cómo se ha escrito, incluso admiten
        colaboraciones de desarrolladores que quiera aportar cosas.
      </p>
    </Col>

  </Row>

</Container>

<Container>
  <h1 class="titulo1" align="center">
    <strong>Mejoras del HTML</strong>
  </h1>
</Container>
<Container>
  <Row>
    <Col>
      <p>
        Este Javascript pretende que los programadores mejoren el HTML que
        hacen. Que puedan producir un HTML que, de manera declarativa, genere
        aplicaciones que sean fáciles de entender incluso para alguien que no
        tiene conocimientos profundos de informática. El objetivo es producir un
        HTML altamente semántico, es decir, que cuando lo leas entiendas de
        manera clara qué es lo que hace o para qué sirve cada cosa.
      </p>
    </Col>
  </Row>

  <Row>
    <Col>
      <p>
        Lógicamente, AngularJS viene cargado con todas las herramientas que los
        creadores ofrecen para que los desarrolladores sean capaces de crear ese
        HTML enriquecido. La palabra clave que permite ese HTML declarativo en
        AngularJS es "directiva", que no es otra cosa que código Javascript que
        mejora el HTML.
      </p>
    </Col>
  </Row>

  <Row>
    <Col>
      <p>
        Puedes usar el que viene con AngularJS y el que han hecho terceros
        desarrolladores, puesto que muchas personas están contribuyendo con
        pequeños proyectos -independientes del propio framework- para enriquecer
        el panorama de directivas disponibles. Hasta este punto serás un
        "consumidor de directivas", y nalmente cuando vayas tomando experiencia
        serás capaz de convertirte en un "productor de directivas",
        enriqueciendo tú mismo las herramientas para mejorar tu propio HTML.
      </p>
    </Col>
  </Row>

  <Row>
    <Col>
      <p>
        Promueve patrones de diseño adecuados para aplicaciones web Angular
        promueve y usa patrones de diseño de software. En concreto implementa lo
        que se llama MVC, aunque en una variante muy extendida en el mundo de
        Javascript que luego comentaremos con más detalle. Básicamente estos
        patrones nos marcan la separación del código de los programas
        dependiendo de su responsabilidad. Eso permite repartir la lógica de la
        aplicación por capas, lo que resulta muy adecuado para aplicaciones de
        negocio y para las aplicaciones SPA (Single Page Aplication).
      </p>
    </Col>
  </Row>
</Container>
