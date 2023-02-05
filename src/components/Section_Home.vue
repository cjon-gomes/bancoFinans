<template>
    <section id="home">
        <div class="container">
            <div class="row">
                <div class="col-md-6 d-flex">
                    <div class="align-self-center">
                        <h1 class="dispaly-4"> Suas contas, Descplicadas</h1>
                        <p>
                            Usado por mais de 1 milhão de pessoas, o Finans é uma 
                            ferramenta online que vai facilitar sua vida finamceira.
                        </p>
                        <form class="mt-4 mb-4">
                            <div class="input-group mb-3">
                                <input type="text" class="form-control" placeholder="Seu E-mail" aria-label="Seu E-mail" aria-describedby="button-addon2">
                                <div class="input-group-append">
                                    <button class="btn btn-primary" type="button" id="button-addon2">Cadastre-se</button>
                                </div>
                            </div>
                        </form>
                        <p>Disponivel para
                            <a href="" class="btn btn-outline-light">
                                <i class="fab fa-android fa-lg"></i>
                            </a>
                            <a href="" class="btn btn-outline-light">
                                <i class="fa-brands fa-apple fa-lg"></i>
                            </a>
                        </p>

                    </div>
                </div>
                <div class="col-md-6 d-none d-md-block">
                   <img src="../assets/img/capa-mulher.png" alt="">
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name:"Section_Home"
}
</script>
<style scoped>
    #home{
        background: #ffc107;
        color: white;
    }
</style>