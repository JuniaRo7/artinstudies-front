<template>
  <div>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Ovo&family=Poppins:wght@300&family=Rajdhani:wght@500&display=swap"
      rel="stylesheet"
    />
    <h1>BEM-VINDO</h1>
    <p>Olá! Preencha seus dados para acessar a página.</p>
    <form @reset="onReset">
      <label>Nome</label>
      <input
        type="text"
        v-model="form.nome"
        name="nome"
        placeholder="    Seu nome"
      />
      <label>E-mail</label>
      <input
        type="email"
        v-model="form.email"
        name="email"
        placeholder="    insira seu e-mail"
      />
      <label>Senha</label>
      <input
        type="password"
        v-model="form.senha"
        name="senha"
        placeholder="    ************"
      />
      <input id="caixinha" type="checkbox" />
      <label id="remember">Lembre-me</label>
      <label id="forget">Esqueceu a senha?</label>
      <b-button type="button" id="continuar" v-on:click="cadastrar"
        >Continuar</b-button
      >
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      form: {
        nome: '',
        email: '',
        senha: '',
      },
      show: true,
    }
  },
  methods: {
    cadastrar() {
      this.$axios.post('/usuario', {
        nome: this.form.nome,
        email: this.form.email,
        senha: this.form.senha,
      })
      this.$router.push('/tela-usuarios')
    },
    onReset(event) {
      event.preventDefault()
      this.form.nome = ''
      this.form.email = ''
      this.form.senha = null
      this.show = false
      this.$nextTick(() => {
        this.show = true
      })
    },
  },
}
</script>

<style>
body {
  font-family: 'Poppins', sans-serif;
  background-image: url('../static/fundo.png');
  background-size: cover;
  background-repeat: no-repeat;
  font-weight: bold;
  display: grid;
  place-items: center;
  padding-bottom: 30px;
}
h1 {
  font-family: 'Ovo', serif;
  text-align: center;
  margin-top: 83px;
}
p {
  text-align: center;
  margin-top: 65px;
}
input,
label {
  display: block;
}
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
#remember,
#caixinha,
#forget {
  display: inline;
  margin-bottom: 0;
}

input {
  width: 454px;
  height: 47px;
  border: 1px solid black;
  border-radius: 49px;
  background: transparent;
  margin-bottom: 26px;
}
#caixinha {
  width: 14px;
  height: 14px;
}
#forget {
  float: right;
}
form {
  margin-top: 89px;
}
</style>