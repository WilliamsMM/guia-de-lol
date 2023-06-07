<style>
body {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  background-image: url("./assets/fondo.jpg");
  background-size: cover;
  width: 100%;
  height: 100%;
  min-height: 100vh;
}

.portada-img {
  width: 100%;
  height: calc(100vh - 45px);
}

.title {

  text-align: center;
  font-size: 30px;
  color: aliceblue;
  margin-bottom: 20px;
}

.title-2 {

  text-align: center;
  font-size: 15px;
  color: aliceblue;
  margin-bottom: 20px;
  border: 3px solid rgb(84, 1, 130);
  padding: 10px;
  width: 400px;
  margin: auto;

}

.texto {


  font-size: 15px;
  color: aliceblue;
  margin-bottom: 20px;
  border: 3px solid rgb(84, 1, 130);
  padding: 10px;
  width: 400px;
  margin: auto;
}

footer {
  background-color: rgb(84, 1, 130);
  color: #fff;
  padding: 8px;
  text-align: center;
  margin-top: 30px;
}

.container {

  margin: 0 auto;
}
</style>
  


<template>
  <header class="bg-purple-900">
    <div class="container mx-auto flex justify-between items-center py-2">

      <h1 class="text-white font-bold text-xl">League of Legends</h1>

      <nav>
        <ul class="flex">

          <li><a href="https://www.google.co.ve/webhp" target="_blank" class="text-white font-bold py-2 px-4">Ir a
              Google</a></li>

          <li><a href="https://signup.leagueoflegends.com/es-mx/signup/redownload" target="_blank"
              class="text-white font-bold py-2 px-4">Descargar lol</a></li>

          <li><a href="https://signup.leagueoflegends.com/es-mx/signup/index#/" target="_blank"
              class="text-white font-bold py-2 px-4">Registrate</a></li>
        </ul>

      </nav>

    </div>
  </header>

  <main>
    <div>
      <img class="portada-img" src="./assets/lol.jpg" alt="">

      <div>
        <h1 class="title">¿QUÉ ES LEAGUE OF LEGENDS?</h1>

        <h1 class="title-2">League of Legends es un juego de estrategia por equipos en el que dos equipos de cinco
          campeones se enfrentan para ver quién destruye antes la base del otro. Elige de entre un elenco de 140 campeones
          para realizar jugadas épicas, asesinar rivales y derribar torretas para alzarte con la victoria.</h1>

      </div>

      <div>

        <h1 class="title">¡DESTRUYE LA BASE!</h1>

        <p class="title-2"> El nexo es el corazón de las bases de los equipos. Para ganar la partida, hay que destruir el
          nexo enemigo. (Nexo enemigo:El nexo enemigo, que se encuentra en la
          base del equipo contrario, es igual que el de tu equipo. Si acabas con él, ganarás la partida.)

        <p class="title-2">Tu nexo: Los súbditos se generan en tu nexo. Detrás del nexo se encuentra la fuente, donde
          podrás
          recuperar vida y maná con rapidez y acceder a la tienda.</p>

        <p class="title-2"> Nexo enemigo: El nexo enemigo, que se encuentra en la
          base del equipo contrario, es igual que el de tu equipo. Si acabas con él, ganarás la partida.</p>

        </p>

      </div>


      <div>
        <h1 class="title">¡ÁBRETE PASO!</h1>
        <h1 class="title-2">Para llegar hasta el nexo enemigo, tu equipo tendrá que avanzar por al menos una calle. Hay
          estructuras defensivas que bloquean tu avance: las torretas y los inhibidores. Cada calle cuenta con tres
          torretas y un inhibidor. Además, cada nexo tiene dos torretas adicionales.</h1>

      </div>

      <div>

        <h1 class="title">¡A LA CONQUISTA DE LA JUNGLA!</h1>
        <h1 class="title-2">Entre las calles se encuentra la jungla, en la que habitan monstruos neutrales y plantas
          mágicas. Los dos tipos de monstruos más importantes son el Barón Nashor y los dragones. Acabar con estas
          unidades otorgará a tu equipo mejoras únicas y, en ocasiones, te ayudará a darle la vuelta a la partida.</h1>
      </div>

      <div>
        <h1 class="title">¿Cómo jugar bien a League of Legends?</h1>

        <h1 class="title-2">Por eso te traemos esta guía con 11 consejos que te serán de mucha ayuda en tus aventuras por
          el mundo de la grieta del invocador.</h1>
      </div>

      <ul class="texto">
        <li> 1-Prueba diferentes campeones. </li>
        <li> 2-Conoce los roles y arquetipos.</li>
        <li> 3-Mira siempre el mapa.</li>
        <li> 4-Comunicate con tu equipo.</li>
        <li> 5-Infórmate sobre los objetos.</li>
        <li> 6-Domina el "Last Hit”</li>
        <li> 7-Usa asistentes virtuales</li>
        <li> 8-Mantener la calma XD.</li>
        <li> 9-No insultar a tus compañeros XD.</li>
        <li> 10-Estar atento al minimapa.</li>
        <li> 11-Nunca te rindas :D.</li>
      </ul>
    </div>

    <footer>
      <div class="container mx-auto flex justify-between items-center py-1">

        <ul class="flex">
          <li><a href="https://www.xnxx.com" target="_blank" class="text-white font-bold py-2 px-4">No tocar</a></li>
        </ul>
      </div>
    </footer>
  </main>
</template>