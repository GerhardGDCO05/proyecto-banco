<script setup>
  let hola=0;
</script>

<template>
  <main>
    <div class="titulo">
        <h1>MANJOUD BANK</h1>
      </div>
    <header class="header">
      <nav class="nav-bar">
        <div class="cap-social">
          <p class="nav-text cap-social-text">CAPITAL SOCIAL</p> 
        </div>
        <a href='#' class="links">Registrar</a>
        <a href="#" class="links">Conócenos</a>
        <a href="#" class="links preguntas-frecuentes">Preguntas Frecuentes </a>
      </nav>
      <div class="carrusel">
        <img class="first-carrusel" src="https://media.istockphoto.com/id/542727462/es/foto/horizonte-de-houston-texas.jpg?s=612x612&w=0&k=20&c=ZtuiuLR6C48V8jUy_Ws4qyoWrhT6F1wlS_hfxQ5DTjE=" alt="paisaje">
      </div>
    </header>
    <div class="container">
        <h2 class="subtitle">TU PATRIMONIO EN UN SITIO</h2>
        <nav class="nav-container">
          <a href="#" class="link-container">Posicion Global de tus Cuentas</a>
          <a href="#" class="link-container">Historial de transacciones</a>
          <a href="#" class="link-container">Control Financiero</a>
        </nav>
        <div class="fotos-container-first">
          <div class="img-mujer">
            <img class="foto-mujer" src="https://st.depositphotos.com/2117297/4993/i/450/depositphotos_49933079-stock-photo-hipster-woman-using-laptop.jpg" alt="">
          </div>
          <div class="feature">
            <div class="img-feature-container">
              <img class="img-feature img-seguridad" src="https://cdn-icons-png.flaticon.com/512/3208/3208690.png" alt="">
              <img class="img-feature img-seguridad" src="https://img.freepik.com/vector-premium/personaje-dibujos-animados-apoyo-al-servicio-al-cliente-femenino_188898-392.jpg?semt=ais_hybrid&w=740" alt="">
              <img class="img-feature img-seguridad" src="https://cdn-icons-png.flaticon.com/512/3208/3208690.png" alt="">
            </div>
            <div class="regist">
              <div class="custom-button">Registrate</div>
            </div>
          </div>
      </div>

      <div class="title-second-container"><h2>PRINCIPALES OPERACIONES DE CAPITAL DIGITAL</h2></div>
      <div class="fotos-container-second">
            <div class="second">
              <img src="https://thumbs.dreamstime.com/b/lupa-de-dibujos-animados-ilustraci%C3%B3n-vectorial-dibujada-mano-aislada-sobre-fondo-transparente-214104236.jpg" alt="consultas">
              <h2>CONSULTAS</h2>
              <p>Posicion global,</p>
              <p> Tarjetas, </p>
              <p>Cuentas, Entre Otras más.</p>
            </div>
            <div class="second">
              <img src="https://www.bbva.com/wp-content/uploads/2019/11/transferencias2.jpg" alt="transferencias">
              <h2>TRANSFERENCIAS Y PAGOS</h2>
              <p>Transferencia de dinero a terceros,</p>
              <p>soporte a multiples a bancos.</p>
              <p>Pagos de servicios como electricidad,</p>
              <p>internet y agua</p>
            </div>
            <div class="second">
              <img src="https://static.vecteezy.com/system/resources/previews/009/221/596/non_2x/medical-records-icon-filled-line-information-document-logo-cartoon-patient-database-design-symbol-illustration-free-vector.jpg" alt="registros">
              <h2>REGISTROS</h2>
              <p>Registros de todas las transferencias,</p>
              <p>pagos y monitoreo de cuentas.</p>
            </div>
      </div>
      <div class="extra">
        <div class="extra-banks">
          <img class="bdv" src="https://laverdaddemonagas.com/wp-content/uploads/2022/05/quieres-abrir-una-cuenta-en-bdv-aqui-te-ensenamos-laverdaddemonagas.com-1621287095-937796-1621287161-noticia-normal.jpg" alt="">
          <img class="bdt" src="https://www.bdt.com.ve/wp-content/uploads/2024/09/17-jul-LogoBDT_logo-6.png" alt="">
          <img class="bbva" src="https://upload.wikimedia.org/wikipedia/commons/d/d4/BBVAprovinciallogo.svg" alt="">
          <img class="mercantil" src="https://play-lh.googleusercontent.com/iI6Zm0naUfYPrxwGuZbLLuCue1F6bTv7qdMj4LIpsSFhv8HXBAr7Bl3K883bLU7QNTY=w416-h235-rw" alt="">

        </div>
        <div class="otros-extras">
          <h2>Multi-Soporte de Bancos</h2>
          <p>Compatibilidad para todos los bancos</p>
          <p>nacionales y gestiona tu patrimonio,</p>
          <p>todo en una pagina</p>
          <a href="#">Como Funciona >></a>

        </div>

      </div>
    </div>
    <footer class="barra-final">
      <div class="cap-digital">
        <div class="cap-digital-title">
          <h2>CAPITAL DIGITAL</h2>
        </div>        
        <div class="info-terminos-condiciones">
          <div>
            <p>Legal Terminos y Condiciones</p>
          </div>
          <div>
            <p>¿Donde nos encontramos?</p>
            <p>Sedes</p>
          </div>
          <div>
            <a href=""><p>Iniciar Sesion</p></a>
          </div>
        </div>
<!-- informacion adicional-->
        <div class="info-adicional">
          <div>
            <p>0414-2326879</p>
          </div>
          <div>
            <p>Caracas, Venezuela</p>
          </div>
          <div>
            <p>capitaldigital@e-banking.net</p>
          </div>
        </div>
      </div>
      <div class="derechos-reservados">
        <p>© 2025-Actua Capital Digital, S.A. Todos los derechos reservados</p>
      </div>

    </footer>
  </main>
</template>

<style scoped>
  main {
    overflow: hidden;
    margin: 0;
    padding: 0;
    
  }
  .titulo{
    width: 100%;
    height: 10vh;
    display: flex;
    flex-direction: row;
    justify-content: center;
  }
  .titulo img{
    width: 25%;
    height: 100%;
  }
  h1{
    margin-left: 2vw;
  }
  .header {
    width: 100%;
    height: 60vh;
    margin: 0;
    padding: 0;
  }

  .nav-bar {
    width: 100%;
    height: 20%;
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
    align-items: center; /* Asegura que los ítems estén centrados verticalmente */
  }

  .carrusel {
    width: 100%;
    height: 80%;
    display: flex;
    justify-content: center;
  }

  .first-carrusel {
    width: 97%;
    height: 100%;
    margin-left: 0;
  }

  .link-container {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 1em;
    margin: 0; /* Elimina márgenes no deseados */
    padding: 0; /* Elimina el padding no deseado */
    text-decoration: none;
    color: #050000;
  }

  .cap-social {
    
    max-width: 100%;
    max-height: 100%;
    margin-left: 2vh;
    border-left: 2px solid #000;
    display: flex;
    align-items: center; /* Centra verticalmente el texto */
  }

  .cap-social-text {
    margin-left: 0.8vh;
    color: rgb(14, 119, 224);
    font-size: 3vh;
  }

  .links {
    font-family: Arial, Helvetica, sans-serif;
    color: black;
    width: 90%;
    height: 70%;
    text-align: center;
    margin: 0 0.6em;
    font-size: 3vh;
    display: flex;
    align-items: center; /* Centra verticalmente el texto */
    justify-content: center; /* Centra horizontalmente el texto */
    transition: opacity 0.3s ease; /* Corregido: eliminada la coma extra */
  }

  .links:hover{
    opacity: 0.5;
  }
  .preguntas-frecuentes{
    background-color: rgb(78, 131, 245);
    border-radius: 50px;
    opacity: 1;
    transition: opacity 0.3s ease, color 0.3s ease; /* Corregido: 0.3 -> 0.3s */
    color: #fff;
  }

  .preguntas-frecuentes:hover {
    opacity: 0.8;
    color: black;
  }
  /*------------------------------------------------------------------------------------------- */
  .container{
    display: flex;
    flex-direction: column;
  }
  .nav-container{
    margin-top: 2vh;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    text-align: center;
    background-color: rgb(74, 132, 219);
    height: 10vh;
    align-items: center;
  }
  .fotos-container-first{
    width: 100% ;
    height: 50vh;
    display: grid;
    grid-template-columns: 1fr 1fr;
  }
  .img-mujer, .feature{
    width: 95%;
    height: 95%;
    margin-left: 2vw;
    margin-top: 2vh;
  }
  .img-feature-container{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
  }
  .foto-mujer{
    width: 100%;
    height: 100%;
  }
  .img-feature{
    width: 40%;
    height: 30vh;
    margin: auto;
  }
  .regist{
    display: flex;
    width: 100%;
    height: 20vh;
    margin: auto;
    justify-content: center;
    align-items: center;
  }
  .custom-button {
    display: inline-block;
    width: 80%; /* Ajusta el ancho */
    padding: 0.5em 1em; /* Espaciado interno */
    font-size: 2.5vh; /* Tamaño del texto */
    text-align: center; /* Centra el texto */
    background-color: #007bff; /* Color de fondo */
    color: white; /* Color del texto */
    border-radius: 5px; /* Bordes redondeados */
    cursor: pointer; /* Cambia el cursor al pasar sobre el elemento */
    box-sizing: border-box; /* Incluye el padding en el tamaño total */
  }

  .custom-button:hover {
    background-color: #0056b3; /* Cambia el color al pasar el mouse */
  }
  .fotos-container-second{
    width: 100%;
    height: 75vh;
    display: flex;
    flex-direction: row;
  }
  .second{
    justify-content: center;
    height: 100%;
    width: 33.33%;
    
  }
  .second img{
    width: 100%;
    height: 50%;
    border-radius: 50%;
    margin-bottom: 10vh;
  }
  .second h2,.second p{
    text-align: center;
  }
  .second h2{
    font-size: 3vh;
  }
  .extra{
    margin-top: 10vh;
    width: 100%;
    height: 80vh;
    display: flex;
    flex-direction: row;
  }
  .extra-banks{
    width: 100%;
    height: 94%;
    display: flex;
    flex-wrap: wrap;
    margin-top: 5vh;
    justify-content: center;
  }
  .extra-banks img{
    width: 33.33%;
    height: 20%;
    margin: 0 10vh;
  }

  .otros-extras{
    display: flex;
    flex-direction: column;
    width: 100%;
    text-align: center;
    margin-top: 5vh;
    margin-right: 3vh;
    justify-content: center;
  }
  .otros-extras h2{
    font-size: 5vh;
  }

  .barra-final{
    width: 100%;
    height: 50vh;
  }
  .cap-digital{
    display: flex;
    flex-direction: column;
    background-color: #acf;
    width: 100%;
    height: 90%;
    border-bottom: 4px solid #000;
    align-items: center;
  }
  .cap-digital-title{
    width: 20%;
    text-align: center;
    border-left: 4px solid #000;
    font-size: 1.8vh;
  }
  .info-terminos-condiciones{
    display: grid;
    grid-template-columns: repeat(3,1fr);
  }

  .info-terminos-condiciones div p{
    margin:2vh;
    text-align: center;
  }

  .info-adicional{
    display: grid;
    grid-template-columns: repeat(3,1fr);
    
  }
  .info-adicional div{
    margin:0 3vw;
  }

  .derechos-reservados{
    text-align: center;
  }
  .title-second-container{
    margin: auto;
    margin-top: 20vh;
    margin-bottom: 0;
    font-size: 3vh;
  }

  .subtitle{
    margin: auto;
    margin-top: 2vh;
  }
  p{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 2vh;
  }
  a{
    text-decoration: none;
  }

  /*---------------------------------querys-----------------------------*/
  @media (max-width: 700px) {
  .custom-button {
    width: 90%; /* Ajusta el ancho en pantallas pequeñas */
    font-size: 2vh; /* Reduce el tamaño del texto */
  }
  .nav-bar {
    display: flex; /* Cambia de grid a flexbox */
    flex-wrap: row; /* Permite que los elementos se ajusten si no caben */
    justify-content: space-evenly; /* Distribuye los elementos con espacio entre ellos */
    padding: 0; /* Agrega un poco de espacio interno a los lados */
  }

  .links {
    width: 100%;
    height: 80%; /* Asegura que cada enlace ocupe el ancho completo */
    text-align: center; /* Centra el texto dentro de cada enlace */
    font-size: 1.5vh; /* Ajusta el tamaño del texto */
    margin: 0.5em; /* Agrega espacio entre los enlaces */
    max-width: 30%; /* Limita el ancho máximo de cada enlace */
  }

  .preguntas-frecuentes {
    flex: 1; /* Asegura que este enlace también se ajuste */
    max-width: 30%; /* Limita el ancho máximo */
    text-align: center; /* Centra el texto */
  }

  .cap-social {
    flex: 1; /* Permite que el elemento se ajuste proporcionalmente */
    max-width: 30%; /* Limita el ancho máximo */
    text-align: center; /* Centra el texto */
    font-size: 1.5vh; /* Ajusta el tamaño del texto */
    margin: 0.5em; /* Agrega espacio entre los elementos */
  }

  .cap-social-text {
    margin: 0; /* Elimina márgenes adicionales */
    font-size: 1.5vh; /* Ajusta el tamaño del texto */
  }

  /* Ajustes para fotos-container-second */
  .fotos-container-second {
    display: flex;
    flex-direction: column; /* Apila los elementos verticalmente */
    align-items: center; /* Centra los elementos horizontalmente */
    gap: 3vh; /* Espacio entre los elementos */
    width: 100%; /* Ocupa todo el ancho disponible */
    margin: 0 auto 50vh auto; /* Margen inferior para separar de .extra */
  }

  .second {
    width: 90%; /* Ajusta el ancho de cada elemento */
    height: auto; /* Ajusta la altura automáticamente */
    margin-bottom: 3vh; /* Espacio inferior entre los elementos */
    margin: auto;
    text-align: center; /* Centra el texto */
  }

  .second img {
    width: 50%; /* Ajusta el tamaño de las imágenes */
    height: auto; /* Mantiene la proporción de las imágenes */
    margin: 0 auto; /* Centra las imágenes */
  }

  .second h2, .second p {
    text-align: center; /* Centra el texto */
  }

  /* Ajustes para extra */
  .extra {
    display: flex;
    flex-direction: column; /* Apila los elementos verticalmente */
    align-items: center; /* Centra los elementos horizontalmente */
    width: 100%; /* Ocupa todo el ancho disponible */
    margin-top: 10vh; /* Espacio superior para separar de .fotos-container-second */
    gap: 3vh; /* Espacio entre los elementos internos */
  }

  .extra-banks {
    display: flex;
    flex-wrap: wrap; /* Permite que las imágenes se ajusten en varias filas */
    justify-content: center; /* Centra las imágenes horizontalmente */
    gap: 3vh; /* Espacio entre las imágenes */
    width: 100%; /* Ocupa todo el ancho disponible */
  }

  .extra-banks img {
    width: 80%; /* Ajusta el tamaño de las imágenes */
    height: auto; /* Mantiene la proporción de las imágenes */
    margin: 0 auto; /* Centra las imágenes */
  }

  /* Ajustes para otros-extras */
  .otros-extras {
    text-align: center; /* Centra el texto */
    margin-top: 10vh; /* Espacio superior */
    width: 90%; /* Ajusta el ancho */
    gap: 2vh; /* Espacio entre los elementos internos */
  }

  .otros-extras h2 {
    font-size: 3vh; /* Ajusta el tamaño del texto */
  }

  .otros-extras p {
    font-size: 2vh; /* Ajusta el tamaño del texto */
  }

  /* Ajustes para barra-final */
  .barra-final {
    width: 100%; /* Ocupa todo el ancho disponible */
    margin-top: 50vh; /* Espacio superior para separar de .extra */
    padding: 3vh 0; /* Espacio interno */
    background-color: #f5f5f5; /* Color de fondo opcional */
  }

  .cap-digital {
    display: flex;
    flex-direction: column; /* Apila los elementos verticalmente */
    align-items: center; /* Centra los elementos horizontalmente */
    width: 100%; /* Ocupa todo el ancho disponible */
    gap: 3vh; /* Espacio entre los elementos internos */
  }

  .cap-digital-title {
    width: 90%; /* Ajusta el ancho */
    text-align: center; /* Centra el texto */
    font-size: 2.5vh; /* Ajusta el tamaño del texto */
  }

  .info-terminos-condiciones {
    display: flex;
    flex-direction: row; /* Apila los elementos verticalmente */
    align-items: center; /* Centra los elementos horizontalmente */
    gap: 1vh; /* Espacio entre los elementos */
    width: 100%; /* Ajusta el ancho */
  }

  .info-adicional {
    display: flex;
    flex-direction: row; /* Apila los elementos verticalmente */
    align-items: center; /* Centra los elementos horizontalmente */
    gap: 1vh; /* Espacio entre los elementos */
    width: 95%; /* Ajusta el ancho */
  }

  .derechos-reservados {
    text-align: center; /* Centra el texto */
    font-size: 1.5vh; /* Ajusta el tamaño del texto */
    margin-top: 1vh; /* Espacio superior */
  }
}

</style>