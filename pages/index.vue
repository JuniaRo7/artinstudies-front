<template>
  <div>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@500&display=swap"
      rel="stylesheet"
    />
    <img src="../static/logo.png" id="logo" />
    <p id="frasemotivadora">“O alívio para mentes brilhantes”</p>
    <botaoContinuar></botaoContinuar>
  </div>
</template>

<script>
import botaoContinuar from '../components/botaoContinuar.vue'
export default {
  components: { botaoContinuar },
  name: 'IndexPage',
}
</script>
<style>
body {
  font-family: 'Rajdhani', sans-serif;
  background-image: url('../static/fundo.png');
  background-size: cover;
  background-repeat: no-repeat;
  display: grid;
  place-items: center;
}
#logo {
  width: 186px;
  height: 190px;
  margin-top: 110px;
  margin-bottom: 128px;
  margin-left: 8em;
}
#frasemotivadora {
  font-weight: 700;
  font-size: 24px;
  text-align: center;
}
</style>