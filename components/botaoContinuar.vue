<template>
  <div>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@500&display=swap"
      rel="stylesheet"
    />
    <button type="button" id="continuar"><a href="/tela-Login">Continuar</a></button>
  </div>
</template>

<script>
export default {}
</script>

<style>
#continuar {
  font-family: 'Rajdhani', sans-serif;
  width: 455px;
  height: 58px;
  border-radius: 105px;
  border: none;
  background-color: #f2f7c0;
  font-size: 40px;
  font-weight: 500;
  color: #6eade8;
  box-shadow: 3px 3px 3px rgb(65, 65, 65);
  margin-top: 273px;
  padding-bottom: 10px;
  margin-bottom: 182px;
}
@media only screen and (max-device-width: 500px) {
  #continuar {
    width: 300px;
  }
}
</style>