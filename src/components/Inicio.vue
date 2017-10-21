<template>
  <div id="inicio">
    <div class="fixed-bg center" id="trees">
      <br>
      <a >
        <img src="../imgs/comdahl logo.png" width="350" height="350" alt="Logo"></img>
      </a>
      <br><br>
      <div class="row">
        <div class="col s4  -center">
          <i class="large material-icons">directions_walk</i>
          <br>
          TRABAJO
        </div>
        <div class="col s4  -center">
          <i class="large material-icons">trending_up</i>
          <br>
          DESARROLLO
        </div>
        <div class="col s4  -center">
          <i class="large material-icons">accessibility</i>
          <br>
          SOLIDARIDAD
        </div>
      </div>
    </div>
    <div class="-long3 -yellow">

    </div>
    <div class="fixed-bg -center -frase1" id="leaves">
      Apoyamos a todos aquellos que con esfuerzo y sacrificio <br>
      dan fertilidad a nuestras tierras catrachas,  <br>
      con el compromiso que nos caracteriza.
    </div>
    <div class="row center" >
      <div class="col s6 -white -long2 -right" id="contenedor-principal">
        <div class="typewriter">
          <h1>¿Qué es COMDAHL?</h1>
        </div>
      </div>
      <div class="col s6 flow-text -white -left -long2 " id="contenedor-principal">
        <p>
          <br>
          Es una asociación autónoma de personas unidas voluntariamente <br>
          con la intención de hacerle frente a las necesidades y aspiraciones <br>
          económicas, sociales y culturales comunes a todos los miembros  <br>
          mediante participación solidaria y responsable de sus miembros.
        </p>
      </div>
    </div>

    <div class="row">
      <div class="col m6 -lightgreen -long2 " id="contenedorVMision">
        <i class="large material-icons">settings</i>
        <div >
          <h1 id="MVision">MISION</h1>
        </div>
        <p>
          Somos una empresa cooperativa de primer grado, que promueve
          y desarrolla servicios de asistencia técnica especializada
          en procesos productivos, comerciales, administrativos
          y tecnológicos, que favorecen el desarrollo humano sostenible
          y el crecimiento patrimonial de las economías familiares,
          como una contribución eficaz para el desarrollo del sector
          cooperativo agropecuario Hondureño.
        </p>
      </div>
      <div class="col m6 -green -long2  " id="contenedorVMision">

        <div >
          <i class="large material-icons">remove_red_eye</i>
          <br>
          <h1 id="MVision">VISION</h1>
        </div>
        <div>
          <p>
            Ser una organización cooperativa líder en la promoción y
            desarrollo de servicios agropecuarios financieros, privilegiando
            la óptima utilización de los recursos naturales, el capital
            social, la tecnología y el trabajo humano, en el marco de los
            valores y principios cooperativistas universales, para contribuir
            a elevar la calidad de vida de las familias productoras y el
            crecimiento de la economía social en el país.
          </p>
        </div>


      </div>
    </div>
    <div class="row">
      <div class="col m3 -long1 color1" id="proyecto1">

      </div>
      <div class="col m3 -long1 color2" id="proyecto2">

      </div>
      <div class="col m3 -long1 color1" id="proyecto3">

      </div>
      <div class="col m3 -long1 color2" id="proyecto4">

      </div>
    </div>

    <div class="fixed-bg" id="pattern">

    </div>

  </div>
</template>

<script>
export default {
  name: 'inicio',
  mounted(){

  }
}
</script>

<style scoped>

  .-white{
    background-color: #FFFFC4;
    color: black;
  }
  .-green{
    background-color: #8FB259;
    color: #FFFFC4;
  }
  .-lightgreen{
    background-color: #CCCC52;
    color: #FFFFC4;
  }
  .-blue{
    background-color: #192B33;
    color: #FFFFC4;
  }
  .-yellow{
    background-color: #FFD933;
    color: #FFFFC4;
  }
  .-black{
    background-color: #212121;
    color: #FFFFC4;
  }
   #trees{
     background-image: url('https://static.pexels.com/photos/360013/pexels-photo-360013.jpeg');
     min-height: 700px;
     font-family: 'Roboto', sans-serif;
     font-size: 30px;
     padding-top: 10px;
   }
   .color2{
     background: yellow;
     position: relative;
   }
   .color2{
     background: blue;
     position: relative;
     -webkit-filter: grayscale(100%);
     filter: grayscale(100%);
     opacity: 0.5;
   }

   #proyecto1{
     background: url("../imgs/Agropecuaria.jpg") no-repeat center center;
     -webkit-background-size: cover;
     -moz-background-size: cover;
     -o-background-size: cover;
     background-size: cover;
     -webkit-filter: grayscale(100%);
     filter: grayscale(100%);
     opacity: 0.5;
   }
   #proyecto2{
     /*background-image: url("../imgs/Desarrollo comunal.jpg");*/
     background: url("../imgs/Desarrollo comunal.jpg") no-repeat center center;
     -webkit-background-size: cover;
     -moz-background-size: cover;
     -o-background-size: cover;
     background-size: cover;
     -webkit-filter: grayscale(100%);
     filter: grayscale(100%);
     opacity: 0.5;
   }
   #proyecto3{
     /*background-image: url("../imgs/Veterinario.jpg");*/
     background: url("../imgs/Veterinario.jpg") no-repeat center center;
     -webkit-background-size: cover;
     -moz-background-size: cover;
     -o-background-size: cover;
     background-size: cover;
     -webkit-filter: grayscale(100%);
     filter: grayscale(100%);
     opacity: 0.5;
   }
   #proyecto4{
     /*background-image: url("../imgs/Fabrica de biofertilizantes.jpg");*/

     background: url("../imgs/Fabrica de biofertilizantes.jpg") no-repeat center center;
     -webkit-background-size: cover;
     -moz-background-size: cover;
     -o-background-size: cover;
     background-size: cover;

   }
   .-transicion1{
     background-color: #FFD933;
     color: #FFFFC4;
     -webkit-transition: background-color 0.5s ease;
     transition: background-color 0.5s ease;
     font-size: 30px;
   }
   .-transicion1:hover {
     background-color: #192B33;
     color: #FFFFC4;

    }
   .-center{
     display: -webkit-box;
     -webkit-box-pack: center;
     -webkit-box-align: center;
     text-align: center;
   }
   .-right{
     display: -webkit-box;
     -webkit-box-pack: end;
     -webkit-box-align: center;
     text-align: center;
     justify-items: end;
     justify-content: end;
   }
   .-left{
     display: -webkit-box;
     -webkit-box-pack: start;
     -webkit-box-align: center;
     text-align: center;
     justify-items: start;
   }
   #trees {
      -webkit-filter: saturate(150%); /* Safari */
      filter: saturate(150%);
  }
  .-frase1{
    font-family: 'Katibeh', cursive !important;
    font-size: 50px !important;
  }
  #valores {
    -webkit-filter: contrast(120%); /* Safari */
    filter: contrast(120%);
  }
   #pattern{
     background-image: url('https://previews.123rf.com/images/doublebubble/doublebubble1511/doublebubble151100198/48256629-Loros-de-colores-Hermoso-guacamayo-azul-y-oro-Foto-de-archivo.jpg');
     min-height: 500px;
   }
   #leaves{
     background-image: url('https://static.pexels.com/photos/192136/pexels-photo-192136.jpeg');
     min-height: 700px;

   }
  .fixed-bg {
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }

  .-long1{
    height: 300px;
  }
  .-long2{
    height: 600px;
  }
  .-long3{
    height: 200px;
  }
  #contenedor-principal {
    font-family: 'Roboto', sans-serif;
    font-size: 1.4em;
    align-items: flex-start;
    text-align: left;
    display: -webkit-box;
    -webkit-box-align: center;
    padding-top: 15px;
  }
  #contenedorVMision {
    font-size: 18px !important;
    color: #192B33;
    padding: 90px;
    align-items: center;
    text-align: center;
    justify-items: center !important;
  }

  #MVision{
    align-items: center;
    text-align: center;
  }
  .typewriter h1 {
    font-size: 50px;
    overflow: hidden; /* Ensures the content is not revealed until the animation */
    border-right: .15em solid orange; /* The typwriter cursor */
    white-space: nowrap; /* Keeps the content on a single line */
    margin: 0 auto; /* Gives that scrolling effect as the typing happens */
    letter-spacing: .15em; /* Adjust as needed */
    animation:
      typing 3.5s steps(40, end),
      blink-caret .75s step-end infinite;
  }

  /* The typing effect */
  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }

  /* The typewriter cursor effect */
  @keyframes blink-caret {
    from, to { border-color: transparent }
    50% { border-color: orange; }
  }
</style>
