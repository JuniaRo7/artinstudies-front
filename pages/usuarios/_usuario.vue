<template>
  <div>
    <div id="perfil">
      <h1>{{ usuario.nome }}</h1>
      <p>{{ usuario.email }}</p>
      <p>{{ usuario.senha }}</p>
      <b-button v-on:click="excluir">Clique para excluir</b-button>
    </div>
  </div>
</template>

<script>
export default {
  async asyncData({ $axios, route }) {
    const idUsuario = route.params.usuario
    const resposta = await $axios.get('/usuario/' + idUsuario)
    const usuario = resposta.data
    return { usuario }
  },
  methods: {
    excluir() {
      const idUsuario = this.$route.params.usuario
      console.log(idUsuario)
      this.$axios
        .delete('/deletarUsuario/' + idUsuario)
        .then((response) => {
          if (response.status === 200) alert('Usuário removido!')
          this.$router.go(-1);
        })
        .catch((error) => console.log(error))
    },
  },
}
</script>