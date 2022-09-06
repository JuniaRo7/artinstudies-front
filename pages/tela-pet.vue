<template>
<div>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css" integrity="sha256-mmgLkCYLUQbXn0B1SRqzHar6dCnv9oZFPEC1g1cwlkk=" crossorigin="anonymous" />
    <title>Tela Pet </title>

       
        <section id="landing__area" class="container__center">
            <nav class="center__row">
                <h1 class="logo"><i class="fas fa-kiwi-bird"></i> Art in studies</h1>
                <ul class="center__row">
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Artes</a></li>
                    <li><a href="#">Musica</a></li>
                    <li><a href="#">Pets</a></li>
                    <li><a href="#">Livros</a></li>
                </ul>
            </nav>
            <div class="landing__content center__row">
                <div class="landing__info align__left">
                    <h1>
                        Suas conquistas. <br>
                        Viram lindos pets.
                    </h1>
                    <p>Como Forma de agradecimento em troca de ações, vocês receberam pets virtuais coleciaveis em troca</p>
                    <button><a href="#/">Quero começar</a></button>

                </div>
                <div class="image__pet"></div>
            </div>
        
        </section>

        <!-- HELP  -->
        <section id="help" class="container__center">
            <h1>Veja como funciona</h1>
            <div class="help__cards--container center__row">
                <div class="help__card container__center">
                    <span class="card__title">Como ganhar?</span>
                    <h3>Missões a serem cumpridas</h3>
                    <p>EX:Se você acessar a pagina "Música" 5 vezes por dia por 5 dias, automaticamente ganha um pet musical .</p>
                    <div class="card__link container__center">
                        <a href="#">Ver</a>
                    </div>
                </div>
                <div class="help__card container__center">
                    <span class="card__title">Como funciona?</span>
                    <h3>Com acumulo de ações o pet pode evoluir de nivel</h3>
                    <p>O seu lindo pet pode evoluir para um ainda maior e mais bonito, basta precionar o botão evoluir quando alcançar as aões necessarias.</p>
                    <div class="card__link container__center">
                        <a href="#">Ver</a>
                    </div>
                </div>
                
                </div>
        
        </section>

        <!-- Gallery -->
        <section id="gallery">
            <img src="https://cdn.pixabay.com/photo/2018/05/26/18/06/dog-3431913_960_720.jpg" class="img__gallery" id="img-1">
            <img src="https://cdn.pixabay.com/photo/2020/10/05/21/05/bird-5630771_960_720.png" class="img__gallery" id="img-2">
            <img src="https://img.freepik.com/vetores-gratis/baleia-bonitinha-natacao-desenho-vetorial-icone-ilustracao-animal-natureza-icone-conceito-isolado-plano_138676-4465.jpg" class="img__gallery" id="img-3">
            <img src="https://img.freepik.com/vetores-gratis/hamster-bonito-sentado-icon-ilustracao-personagem-de-desenho-animado-de-mascote-de-hamster-conceito-animal-icone-branco-isolado_138676-906.jpg?w=2000" class="img__gallery" id="img-4">
            <img src="https://img.freepik.com/vetores-gratis/bonito-zebra-dancando-desenhos-animados-icone-ilustracao-vetorial-natureza-animal-conceito-de-icone-isolado-premium_138676-4700.jpg?t=st=1656697923~exp=1656698523~hmac=f2bdecbe2df7d63452d8ff547aab364ddeccd71b8aab3e312850e04d3616df79&w=740" class="img__gallery" id="img-5">
            <img src="https://img.freepik.com/vetores-gratis/leao-bonito-comendo-pizza-ilustracao-de-icone-vetorial-dos-desenhos-animados-conceito-de-icone-de-comida-animal-isolado-premium_138676-5032.jpg?t=st=1656697933~exp=1656698533~hmac=88f3be7a75e8a6968f220d78c90b2bc75afdfcc567f2a25c21d595cdfce9a4c2&w=740" class="img__gallery" id="img-6">
            <img src="https://img.freepik.com/vetores-gratis/unicornio-bonito-flutuando-com-ilustracao-do-icone-do-vetor-dos-desenhos-animados-do-balao_138676-2229.jpg?t=st=1656697998~exp=1656698598~hmac=27a0cf1531272daae8a7ebfe511fe1a54d02810ca00f9020f04c26d7ddce2195&w=740" class="img__gallery" id="img-7">
            <img src="https://img.freepik.com/vetores-gratis/panda-gordo-bonito-comendo-pizza-desenhos-animados-icone-ilustracao-vetorial-comida-animal-conceito-icone-isolado-plano_138676-4614.jpg?t=st=1656697933~exp=1656698533~hmac=8ae61cf0928e7380a6bbc208a390762970d6ec62a61a45c43096b534a7e3297d&w=740" class="img__gallery" id="img-8">
            <img src="https://img.freepik.com/vetores-gratis/a-preguica-fofa-dormindo-com-a-xicara-de-cafe-dos-desenhos-animados-icone-ilustracao-vetorial-conceito-de-icone-de-bebida-animal-isolado-vetor-premium-estilo-flat-cartoon_138676-3491.jpg?t=st=1656698125~exp=1656698725~hmac=f15891b58fdcfc258061e6ec04ca6b880b935c4a4ef7c45f1d0dc57103beb776&w=740" class="img__gallery" id="img-9">
        </section>

 
        

        <footer>
            <div class="footer__cont center__row">
                <p>2022 @ArtinStudies</p>
                <div>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-youtube"></i></a>
                    <a href="#"><i class="fab fa-facebook-f"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                </div>
            </div>
        </footer>
</div>
</template>
<script>
</script>
<style>

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root{
    --red: #F26419;
    --orange: #F6AE2D;
    --dark-blue: #33658A;
    --light-blue: #86BBD8;
    --dark: #2F4858;
}

body{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

/* align container */
.container__center{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.center__row{
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.align__left{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
}

h1{
    font-weight: 300;
    font-size: 40px;
    letter-spacing: 2px;
    color: var(--dark);
}

p{
    font-size: 18px;
    letter-spacing: 2px;
    line-height: 22px;
    margin: 2rem 0;
    color: var(--dark);
}

a{text-decoration: none;}

ul li{list-style: none;}

/* LANDING AREA =============*/
#landing__area{
    width: 100%;
    height: 70vh;
    background: url(../static/bg.jpg);
    background-position: center;
    background-size: cover;
}

#landing__area nav{
    height: 10%;
    width: 80%;
}

nav .logo{
    color: var(--orange);
}

nav a{
    color: var(--light-blue);
    margin: 0 20px;
}
nav a:hover{color: var(--orange);}

.landing__content {
    height: 90%;
    width: 80%;
}

.landing__content .landing__info{
    width: 60%;
    height: 100%;
}

.landing__info h1{color: var(--light-blue);}
.landing__info p{
    color: var(--light-blue);
    width: 60%;
}

.landing__info button{
    border: none;
    background: transparent;
    outline: none;
}

.landing__info button:active{
    transform: translateY(2px);
} 

.landing__info a{
    color: var(--dark-blue);
    background-color: var(--orange);
    padding: 10px 20px;
    border-radius: 20px;
    text-transform: uppercase;
}

.image__pet{
    width: 40%;
    height: 100%;
    background: url(../static/pet_img.png);
    background-position: center;
    background-size: contain;
    background-repeat: no-repeat;
}

/* HELP SECTION =========*/
#help{
    width: 80vw;
    max-width: 1200px;
    margin: 3rem auto;
}

.help__cards--container{
    padding: 2rem;
}

#help .help__card{
    position: relative;
    margin: 0 5%;
    text-align: center;
    padding: 1rem;
    border-radius: 10px;
    padding: 60px 10px;
}

.help__card:first-of-type{background-color: var(--red);}
.help__card:nth-of-type(2){background-color: var(--orange);}
.help__card:nth-of-type(3){background-color: var(--light-blue);}

.help__card h3,
.help__card p{ color: white;}

.help__card span{
    position: absolute;
    top: 5%;
    left: 0;
    background: white;
    padding: 5px;
    color: var(--red);
}

.help__card:first-of-type span{color: var(--red);}
.help__card:nth-of-type(2) span {color: var(--orange);}
.help__card:nth-of-type(3) span {color: var(--light-blue);}

.help__card .card__link{
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 0;
    border-radius: 10px;
    background-color: rgba(255, 255, 255, 0.5);
    z-index: 99;
    opacity: 0;
}

.help__card:hover .card__link{
    animation: showLink;
    animation-duration: 0.5s;
    animation-fill-mode: forwards;
}
@keyframes showLink{
    0%{
        opacity: 0;
        height: 0;
    }
    100%{
        opacity: 1;
        height: 100%;
    }
}

.card__link a{
    background-color: var(--dark-blue);
    color: var(--orange);
    padding: 10px 20px;
    border-radius: 20px;
}


/* GALLERY =============*/
#gallery{
    width: 100%;
    height: 70vh;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(3, 33%);
    margin: 2rem 0;
}

.img__gallery{
    height: 100%;
    width: 100%;
    object-fit: cover;
    cursor: pointer;
}


#img-1{grid-column: 1/3; grid-row:1/3;}
#img-2{grid-column: 1/2; grid-row:3/4;}
#img-3{grid-column: 2/3; grid-row:3/4;}
#img-4{grid-column: 3/4; grid-row:1/2;}
#img-5{grid-column: 3/4; grid-row:2/4;}
#img-6{grid-column: 4/6; grid-row:3/4;}
#img-7{grid-column: 4/5; grid-row:2/3;}
#img-8{grid-column: 4/6; grid-row:1/2;}
#img-9{grid-column: 5/6; grid-row:2/3;}

/* CONTACT FORM */
form{
    width: 60vw;
    max-width: 800px;
    margin: 2rem auto;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 10px;
}

form .form__row{
    width: 100%;
    position: relative;
}

.form__row input{
    width: 100%;
    height: 40px;
    border: none;
    border-bottom: solid 1px var(--light-blue);
    outline: none;
}
/* hide arrows form input number */
input::-webkit-outer-spin-button,
input::-webkit-inner-spin-button{
    -webkit-appearance: none;
}


.form__row label{
    position: absolute;
    bottom: 2px;
    left: 2px;
    color: var(--red);
    font-size: 14px;
    transition: 0.5s;
}

input:focus ~ label{
    top: -5px;
    font-size: 10px;
    color: var(--dark-blue);
}

textarea{
    width: 100%;
    height: 30px;
    margin-top: 1rem;
    border: none;
    border-bottom: 1px solid var(--light-blue);
    outline: none;
    appearance: none;
    resize: none;
}

textarea::placeholder{
    color: var(--dark-blue);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

form button{
    background-color: var(--dark-blue);
    font-size: 20px;
    border-radius: 10px;
    border: none;
    outline: none;
    color: var(--light-blue);
    cursor: pointer;
    width: 60%;
    margin: 5px;
}

form button:active{
    transform: scale(0.99);
}

/* FOOTER */
footer{
    background-color: var(--orange);
}

.footer__cont{
    width: 60%;
    margin: auto;
}

.footer__cont p{
    color: var(--dark-blue);
}

.footer__cont .fab{
    color: var(--light-blue);
    font-size: 20px;
    margin: 0 10px;
}
</style>