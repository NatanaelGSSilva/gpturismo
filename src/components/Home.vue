<template>
<div>
<nav class="navbar navbar-expand-md bg-primary navbar-dark fixed-top">
        <div class="container">
            <!-- Brand -->
            <a class="navbar-brand " href="#">
                <img src="gptur.png" alt="Logo GP" width="60"> Grupo GP
            </a>

            <!-- Toggler/collapsibe Button -->
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
        <span class="navbar-toggler-icon"></span>
      </button>

            <!-- Navbar links -->
            <div class="collapse navbar-collapse" id="collapsibleNavbar">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#sobre">Sobre</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#demo">Turismo</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#depoimentos">Depoimentos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contato">Contato</a>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link" to="/login">Login</router-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>


    <header class="fundo" style="margin-top:80px">
        <div class="fundo2">
            <div class="container" id="sobre">
                <div class="row">

                    <div class="col-md-6 text-center align-self-center text-white  mt-5">
                        <h2>Quem somos</h2>
                        <hr>
                        <h5>Conecendo um pouco sobre o grupo GP</h5>
                        <br>
                        <p>
                            Com sua sede na rua 31 de Março nº 336. Gp, gerida por seu proprietário Roberti Porto se expande a cada ano que começa. Garantindo uma viagem com conforto e qualidade para seus frequentadores de cursos técnicos e universitários em Pelotas, a GP no ano
                            passdo deu inicia a essa modalidade com apenas nove passageiros e um carro.
                        </p>

                    </div>
                    <div class="col-md-6 mt-5">
                        <img src="../img/Carro.jpg" alt="BMW antiga" class="img-fluid mt-5 d-none d-md-block">
                    </div>
                </div>
            </div>
        </div>
    </header>


    <!-- LOCALIZAÇÃO -->
    <section class="bg-secondary text-white mt-3 py-4" id="contato">
        <div class="container">
            <h3 id="localizacao">Localização</h3>
            <div class="row">
                <div class="col-md-8 embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3394.1459830269096!2d-52.34405208514863!3d-31.711907017780735!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x95104ab669219c43%3A0x92c8964baadf54f7!2sAv.%20Fernando%20Os%C3%B3rio%2C%204500%20-%20Centro%2C%20Pelotas%20-%20RS%2C%2096070-000!5e0!3m2!1spt-BR!2sbr!4v1567643435658!5m2!1spt-BR!2sbr"
                        frameborder="0" style="border:0;" allowfullscreen=""></iframe>
                </div>
                <div class="col-md-4 text-center align-self-center">
                    <h4>Av. Fernando Osório, 4500</h4>
                    <h5>Bairro: Três Vendas</h5>
                    <h5>Pelotas - RS</h5>
                    <h5>Fone: 9999.9999</h5>
                    <h5>E-mail: gpturismo@gmail.com</h5>
                </div>
            </div>
        </div>
    </section>


    </div>
</template>

<script>

export default {}
</script>

<style scoped>
.fundo {
    background: url(../img/horizonte.jpg);
    background-size: cover;
    min-height: 450px;
    position: relative;
}

.fundo2 {
    background: rgba(11, 56, 97, 0.7);
    position: absolute;
    width: 100%;
    height: 100%;
}

.navbar {
    box-shadow: 2px 2px 5px #f00;
    opacity: 0.9;
    margin-bottom: 4px;
}

#demo {
    margin-top: 80px;
    margin-bottom: 80px;
    margin-left: 100px;
    margin-right: 100px;
    text-align: center;
}
</style>