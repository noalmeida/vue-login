<template>
  <div class="login">
    <div class="container-outher">
      <h1 class="paragraph">Entrar</h1>
      <span class="container-login">
        <input class="form-control" type="email" placeholder="Login"
      /></span>
      <span class="container-password"
        ><input class="form-control" type="password" placeholder="Senha"
      /></span>

      <br />
      <div class="b-login">
        <button type="button" class="btn btn-primary btn-lg">Login</button>
      </div>
      <p>Você não possui conta? <a href="#">Crie uma conta</a></p>
    </div>
  </div>
</template>

<script>
export default {
  name: "login",
  data() {
    return {};
  },
  methods: {},
};
</script>

<style scoped>
@font-face {
  font-family: Poppins-Regular;
  src: url("../assets/Fonts/poppins/Poppins-Regular.ttf");
}

@font-face {
  font-family: Poppins-Bold;
  src: url("../assets/Fonts/poppins/Poppins-Bold.ttf");
}

@font-face {
  font-family: Poppins-Medium;
  src: url("../assets/Fonts/poppins/Poppins-Medium.ttf");
}
.paragraph {
  font-family: Poppins-Medium;
  font-size: 22px;
  padding-bottom: 2rem;
}

.container-outher {
  display: grid;
  justify-items: center;
  margin: 10% 30%;
}
.b-login {
  padding: 1rem;
}
.btn-primary {
  background-color: #3f3f3f;
  padding: 10px 50px;
}
</style>
