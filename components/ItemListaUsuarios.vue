<template>
  <div class="item-perfis mb-2 pt-3 pb-3">
    <b-row>
      <b-col cols="2" class="d-flex align-items-center justify-content-center">
      </b-col>
      <b-col cols="10" class="d-flex align-items-center justify-content-center">
        <NuxtLink :to="`usuarios/${id}`">{{ usuario }}</NuxtLink>
      </b-col>
    </b-row>
  </div>
</template>

<script>
export default {
  name: 'usuarioPage',
  props: ['id', 'usuario' ],
}
</script>

<style>
.item-perfis {
  border-radius: 10px;
  margin-bottom: 20px;
  width: 85%;
  margin: auto;
  box-shadow: 3px 3px 3px 3px #9b9b9b;
}
a {
  color: black;
}
.img {
  width: 70px;
  height: 70px;
  margin-left: 50px;
  border: solid #345fcd 0.5px;
}
h1 {
  text-align: center;
  margin-bottom: 40px;
}
</style>