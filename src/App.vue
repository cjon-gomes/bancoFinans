<template>
  <div><!-- Filho principal -->
        <header>
            <nav class=" navbar navbar-expand-sm navbar-light bg-warning">
                <div class="container">

                  <a href="#" class="navbar-brand">
                    <img src="../src/assets/img/logo.png" width="142" alt="">
                  </a>

                  <button class="navbar-toggler" data-toggle="collapse" target="#nav-principal">
                    <span class="navbar-toggler-icon"></span>
                  </button>

                  <div id="nav-principal" class="collapse navbar-collapse">
                      <ul class="navbar-nav ml-auto">
                        <li class="nav-item ">
                          <a href="#" class="nav-link">Home</a>
                        </li>
                        <li class="nav-item">
                          <a href="#" class="nav-link">Recursos</a>
                        </li>
                        <li class="nav-item">
                          <a href="#" class="nav-link">Benefícios</a>
                        </li>
                        <li class="nav-item">
                          <a href="#" class="nav-link">Preço</a>
                        </li>
                        <li class="nav-item">
                          <a href="#" class="btn btn-outline-light ml-4">Entrar</a>
                        </li>
                      </ul>
                  </div>
                </div>
            </nav>
        </header>

        <Section_Home />
        <Section_Conteudo1 />
        <Section_Conteudo2 />
        <Section_Conteudo3 />

        <footer class="mt-4 mb-4">
          <div class="container">
            <div class="row">
              <div class="col-md-8">
                <p>
                  <a href="">Home</a>
                  <a href="">Recursos</a>
                  <a href="">Benefícios</a>
                  <a href="">Preço</a>
                </p>
              </div>
              <div class="col-md-4 d-flex justify-content-end">
                <a href="" class="text-secondary">
                  <i class="fa-brands fa-facebook"></i>
                </a>
                <a href="" class="text-secondary ml-2">
                  <i class="fa-brands fa-instagram"></i>
                </a>
                <a href="" class="text-secondary ml-2">
                  <i class="fa-brands fa-twitter"></i>
                </a>
                <a href="" class="text-secondary ml-2">
                  <i class="fa-brands fa-youtube"></i>
                </a>
              </div>
            </div>
          </div>
        </footer>

</div><!-- / filho principal -->
</template>

<script>

import Section_Home from "./components/Section_Home.vue";
import Section_Conteudo1 from "./components/Section_Conteudo1.vue";
import Section_Conteudo2 from "./components/Section_Conteudo2.vue";
import Section_Conteudo3 from "./components/Section_Conteudo3.vue";
export default {
  name: 'App',
  components: {
    Section_Home,
    Section_Conteudo1,
    Section_Conteudo2,
    Section_Conteudo3

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
.caixa{
  padding: 60px;
  border-bottom: 1px solid #e5e5e5;
}
footer p a{
  margin: 5px 15px;
}
 span{
  color: white;
}
</style>
