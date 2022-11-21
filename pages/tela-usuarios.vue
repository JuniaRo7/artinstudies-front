<template>
  <div class="page-holder bg-gray-100 mt-5">
    <b-container class="bv-example-row">
      <h1>Lista de Usuários</h1>

      <div :key="usuario.id" v-for="usuario in usuarios">
        <ItemListaUsuarios :id="usuario.id" :usuario="usuario.nome">
        </ItemListaUsuarios>
      </div>
    </b-container>
    <div class="text-center">
    </div>
  </div>
</template>

<script>
import ItemListaUsuarios from '~/components/ItemListaUsuarios.vue'
export default {
  auth: false,
  data() {
    return {
      usuarios: [],
      dados: '',
    }
  },
  async mounted() {
    const response = await this.$axios.get('/usuario')
    this.usuarios = response.data
  },
  components: { ItemListaUsuarios },
}
</script>

<style>

</style>