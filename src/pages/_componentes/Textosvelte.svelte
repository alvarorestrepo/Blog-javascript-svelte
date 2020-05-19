<script>
  import { Col, Row, Container } from "sveltestrap";
  import Img from '../_componentes/Img.svelte'
  let img = "/img/sveltep.png";
</script>

<style>
  p {
    text-align: justify;
    font-size: 1.3rem;
  }
  li {
    font-size: 1.2rem;
    text-align: justify;
    margin-top: 5px;
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
        SvelteJS es el nuevo chico del barrio que empieza a tener algo de
        atención. Algunos pueden conocerlo por ser el lenguaje más popular para
        State of JavaScript en 2018. Como explicación resumida, Svelte quiere
        ser el framework que en realidad no es un framework; es básicamente una
        herramienta para compilar componentes el momento de la construcción
        (build), permitiéndote cargar un único bundle.js en tu página para
        renderizar la aplicación.
      </p>
    </Col>

  </Row>
  <br />
  <Row>
    <Col>
      <p>
        Esto significa que no hay DOM virtual, ni frameworks encima de
        frameworks, no framework que cargar en tiempo de ejecución.
      </p>
    </Col>

  </Row>
  <Row>
    <Col>
      <p>
        Estos puntos son bastante atractivos para desarrolladores
        experimentados, pero los principiantes posiblemente no puedan leer este
        último párrafo sin que les explote la cabeza. Afortunadamente, no es
        está compilación ‘mágica’ lo que hace que Svelte sea atractivo para los
        principiantes, sino su sintaxis.
      </p>
    </Col>
  </Row>

</Container>

<Container>
  <h1 class="titulo1" align="center">
    <strong>De donde salio Svelte?</strong>
  </h1>
</Container>
<Container>
  <Row>
    <Col>
      <p>
        Svelte fue creado por Rich Harris, quien es desarrollador y que por
        mucho tiempo buscaba una forma de mejorar el desempeño de las
        aplicaciones que desarrollaba, él trabaja cumpliendo ciertas
        características:
      </p>
    </Col>
  </Row>

  <Row>
    <Col>
      <ul>
        <li>
          Entregar productos con un excelente rendimiento y fácil desarrollo.
        </li>
        <li>
          Que la librería o framework tuviera una curva de aprendizaje muy corta
          para que otras personas puedan integrarlo en sus proyectos sin mucha
          complicación.
        </li>
        <li>
          Hacer más liviano el trabajo del navegador del lado cliente y reducir
          lo más posible la carga de código de librerías o frameworks por código
          JavaScript puro.
        </li>
      </ul>
    </Col>
  </Row>

  <Row>
    <Col>
      <p>
        El man en pocas palabras, se hartó y creó su propio JS framework a su
        gusto. Luego de haber mencionado las intenciones de Rich harris,
        entonces ya te preguntarás, muy bonita la historia pero ¿qué rayos y
        centellas es Svelte? , a eso vamos.
      </p>
    </Col>
  </Row>

</Container>

<Container>
  <h1 class="titulo1" align="center">
    <strong>Que es Svelte?</strong>
  </h1>
</Container>
<Container>
  <Row>
    <Col>
      <p>
        Es un framework reactivo y basado en componentes que utiliza un paso de
        compilación al momento de realizar cambios en el DOM (Document Object
        Model).
      </p>
    </Col>
  </Row>

  <Row>
    <Col>
      <p>
        Tal vez digas, reactivo?, con que se come eso? bueno, un framework
        reactivo significa que utiliza conceptos de la programación reactiva
        para realizar los cambios correspondiente en el estado de nuestras
        aplicaciones.
      </p>
    </Col>
  </Row>
  <Row>
    <Col>
      <p>
        Pero y ¿qué es programación reactiva? pues de manera corta y precisa, es
        un tipo de programación que trabaja con el flujo de datos (streams) de
        forma asíncrona y que reacciona según el cambio de datos.
      </p>
    </Col>
  </Row>
  <Row>
    <Col>
      <p>
        Un ejemplo, serían las hojas de cálculo en excel donde si pones una
        fórmula en una celda se pone a la espera a que el usuario introduzca los
        valores (asincronía) correspondientes para realizar el cálculo total e
        imprimir el resultado en pantalla (streams) y si modificas alguna celda,
        cambia el resultado total según ese nuevo dato sin ejecutar la operación
        en toda la tabla, solo donde se necesitó un cambio.
      </p>
    </Col>
  </Row>

</Container>
<Container>
  <h1 class="titulo1" align="center">
    <strong>Caracteristicas de Svelte?</strong>
  </h1>
</Container>
<Container>
  <Row>
    <Col>
      <ol>
        <li>
          No utiliza virtual DOM para realizar cambios en la aplicación como
          React o Vue: Este paso se basa en compilar nuestros componentes cuando
          realizamos un cambio, quitándole el trabajo al navegador de estar
          guardando en memoria nuestro árbol de elementos para hacer una
          comparación de un cambio que se hizo y solo se encarga de renderizar.
        </li>
        <li>
          Tiene su propio manejador de estado (Stores): Para los que sufren con
          entender Redux o otras librerías, Svelte ya trae su propio manejador y
          bastante más sencillo de aprender.
        </li>
        <li>
          Su sintaxis es sencilla: Esto ayuda al desarrollador escribir
          componentes con los lenguajes que ya conoce como HTML, CSS, JavaScript
          e incluso para quienes buscan aprender su primer framework JavaScript
          esta sería su oportunidad de darle un vistazo.
        </li>
        <li>
          Totalmente reactivo: Ayuda en la escalabilidad de nuestros proyectos
          para que sean más mantenibles y robustos.
        </li>
        <li>
          El tamaño de las apps que compilas a producción son bien reducidos a
          diferencia de otras alternativas y con código optimizado para
          producción**.**
        </li>
        <li>La documentación es super mega fácil de seguir paso a paso.</li>
        <li>
          Puedes utilizarlo para el server side rendering (SSR) con Sapper
          (propió de Svelte)
        </li>
      </ol>
    </Col>
  </Row>

</Container>
