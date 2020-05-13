<script>
  import { Col, Row, Container } from "sveltestrap";
  import Img from '../_componentes/Img.svelte'
  let img = "/img/reactp.png";
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
        React es una librería Javascript focalizada en el desarrollo de
        interfaces de usuario. Así se dene la propia librería y evidentemente,
        esa es su principal área de trabajo. Sin embargo, lo cierto es que en
        React encontramos un excelente aliado para hacer todo tipo de
        aplicaciones web, SPA (Single Page Application) o incluso aplicaciones
        para móviles.
      </p>
    </Col>

  </Row>
  <br />
  <Row>
    <Col>
      <p>
        Para ello, alrededor de React existe un completo ecosistema de módulos,
        herramientas y componentes capaces de ayudar al desarrollador a cubrir
        objetivos avanzados con relativamente poco esfuerzo.
      </p>
    </Col>

  </Row>
  <Row>
    <Col>
      <p>
        Por tanto, React representa una base sólida sobre la cual se puede
        construir casi cualquier cosa con Javascript. Además facilita mucho el
        desarrollo, ya que nos ofrece muchas cosas ya listas, en las que no
        necesitamos invertir tiempo de trabajo. En este artículo te ampliaremos
        esta información, aportando además diversos motivos por los que usar
        React como librería del lado del cliente.
      </p>
    </Col>
  </Row>

</Container>

<Container>
  <h1 class="titulo1" align="center">
    <strong>Un poco de historia</strong>
  </h1>
</Container>
<Container>
  <Row>
    <Col>
      <p>
        React es una librería desarrollada inicialmente por Facebook. Es
        software libre y a partir de su liberación acapara una creciente
        comunidad de desarrolladores y entusiastas. Su creación se realizó en
        base a unas necesidades concretas, derivadas del desarrollo de la web de
        la popular red social. Además de facilitar el desarrollo ágil de
        componentes de interfaces de usuario, el requisito principal con el que
        nació React era ofrecer un elevado rendimiento, mayor que otras
        alternativas existentes en el mercado.
      </p>
    </Col>
  </Row>

  <Row>
    <Col>
      <p>
        Detectaron que el típico marco de binding y doble binding ralentizaba un
        poco su aplicación, debido a la cantidad de conexiones entre las vistas
        y los datos. Como respuesta crearon una nueva dinámica de
        funcionamiento, en la que optimizaron la forma como las vistas se
        renderizaban frente al cambio en los datos de la aplicación.
      </p>
    </Col>
  </Row>

  <Row>
    <Col>
      <p>
        A partir de ahí la probaron en su red social con resultados positivos y
        luego en Instagram, también propiedad de Facebook. Más adelante, después
        de su liberación y alentados por los positivos resultados en el
        rendimiento de React, muchas otras aplicaciones web de primer nivel la
        fueron adoptando. BBC, Airbnb, Netix, Dropbox y un largo etc.
      </p>
    </Col>
  </Row>

</Container>

<Container>
  <h1 class="titulo1" align="center">
    <strong>Cuál es el objetivo de React</strong>
  </h1>
</Container>
<Container>
  <Row>
    <Col>
      <p>
        Sirve para desarrollar aplicaciones web de una manera más ordenada y con menos código que si usas Javascript
puro o librerías como jQuery centradas en la manipulación del DOM. Permite que las vistas se asocien
con los datos, de modo que si cambian los datos, también cambian las vistas.
      </p>
    </Col>
  </Row>

  <Row>
    <Col>
      <p>
       Detectaron que el típico marco de binding y doble binding ralentizaba un poco su aplicación, debido a la
cantidad de conexiones entre las vistas y los datos. Como respuesta crearon una nueva dinámica de funcionamiento,
en la que optimizaron la forma como las vistas se renderizaban frente al cambio en los datos de
la aplicación.
      </p>
    </Col>
  </Row>

  
</Container>

<Container>
  <h1 class="titulo1" align="center">
    <strong>Qué es el Virtual DOM</strong>
  </h1>
</Container>
<Container>
  <Row>
    <Col>
      <p>
        A lo largo del Manual de React volveremos varias veces sobre el concepto de "Virtual DOM", que es una de
las principales características de React. De momento, en líneas generales podemos decir que el virtual DOM
es una representación del DOM pero en memoria, que usa React para aumentar sensiblemente el rendimiento
de los componentes y aplicaciones front-end.
      </p>
    </Col>
  </Row>

  <Row>
    <Col>
      <p>
      El Virtual DOM se basa en una idea bastante sencilla e ingeniosa. Básicamente hace que, cuando se actualiza
una vista, React se encargue de actualizar el DOM Virtual, que es mucho más rápido que actualizar el DOM
del navegador (DOM real). Cuando React compara el DOM Virtual con el DOM del navegador sabe perfectamente
qué partes de la página debe actualizar y se ahorra la necesidad de actualizar la vista entera. Es algo
muy potente, pero que se hace de manera transparente para el desarrollador, que no necesita intervenir en
nada para alcanzar ese mayor rendimiento de la aplicación.
      </p>
    </Col>
  </Row>

  
</Container>



