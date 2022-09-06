<template>
    <div>

        <header>
            <div class="center">
                <div class="logo">
                    <h2>ArtInStudies</h2>

                </div>
                <div class="menu">
                    <a href="#">
                        Casita
                    </a>

                    <a href="#">
                        Resenhas
                    </a>

                    <a href="#">
                        Artes
                    </a>

                    <a href="#">
                        Playlist
                    </a>

                    <a href="#">
                        Anotações
                    </a>

                    <a href="#">
                        Petico
                    </a>
                </div>
            </div>
        </header>


        <section class="main">

            <div class="center">
                <div class="main_cta">
                    <h2>A imaginação, uma forma magnífica de voar pela mente.</h2>
                    <button>Adicionar suas criações</button>
                </div>
                <div class="criacoes">

                    <div class="ideiascriacoes">
                        <i class="fa-solid fa-paintbrush-fine"></i>
                        <h2>Pintura</h2>
                        <p>A pintura é uma minifestação artística através das cores. Pode ser feita de diversas
                            maneira...</p>
                    </div>

                    <div class="ideiascriacoes">
                        <i class=""></i>
                        <h2>Música</h2>
                        <p>A música é o elo mais forte do ser humano com a mente. Você sabia que a música é a última
                            memória
                            que perdemos?</p>
                    </div>

                    <div class="ideiascriacoes">
                        <i class=""></i>
                        <h2>Dança</h2>
                        <p>Mexer o corpo ajuda a circulação saguínea e o fucionamento do coração. Além disso é bom
                            sacudir o
                            esqueleto. </p>
                    </div>

                    <div class="ideiascriacoes">
                        <i class=""></i>
                        <h2>Escrita</h2>
                        <p>A escrita é uma ótima maneira de exercitar o cérebro. Escrever aflora a senbilidade
                            artística e
                            aumenta o vocabulário. Indubitavelmente! </p>
                    </div>

                </div>

            </div>
        </section>
        <footer>
            <div class="footer__cont center__row">
                <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css" integrity="sha256-mmgLkCYLUQbXn0B1SRqzHar6dCnv9oZFPEC1g1cwlkk=" crossorigin="anonymous" />
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
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;

}

.center {
    display: flex;
    max-width: 1100px;
    margin: 0 auto;
    flex-wrap: wrap;
    padding: 0 2%
}

header {
    background-color: rgba(255, 255, 255, 0.288);
    padding: 20px 0;
}

.logo {
    color: rgb(7, 179, 206);
}

.logo h2 {
    font-weight: bold;
    font-size: 18px;

}

.menu {
    width: 80%;
    text-align: right;
}

.menu a {
    padding: 10px;
    color: rgb(7, 179, 206);
    font-size: 14px;
    text-decoration: none;
    margin-right: 30px;
    transform: 0.5s;

}

.menu a:hover {
    padding: 10px;
    background-color: rgba(1, 37, 110, 0.505);
    color: rgb(255, 255, 255);
}

section.main {
    background-image: url("../static/fundo.png");
    padding: 70px 0;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
}

.main_cta {
    width: 100%;
    text-align: center;
    margin: 60px 0;
}

.main_cta h2 {
    color: rgb(2, 9, 28);
    font-size: 40px;
}

.main_cta p {
    color: yellow;
    font-size: 19px;
    margin: 10px 0;
}

.main_cta button {
    background-color: rgb(23, 173, 232);
    display: inline-block;
    padding: 8px 30px;
    color: white;
    border-radius: 6px;
    font-size: 16px;
    border: 0;
    cursor: pointer;
}

.criacoes {
    display: flex;
    flex-wrap: wrap;
}

.ideiascriacoes {
    border-radius: 10px;
    background-color: white;
    width: 23%;
    margin-right: 2%;
    padding: 50px 20px;
}

.ideiascriacoes h2 {
    color: rgb(2, 9, 28);
    margin: 10px 0;
    font-size: 17px;
}

.ideiascriacoes p {
    color: grey;
    font-size: 14px;
    line-height: 30px;

}

@media screen and (max-width: 768px) {
    .ideiascriacoes {
        width: 100px;
        margin-bottom: 20px;
    }
}
footer {
    background-color: var(--orange);
}

.footer__cont {
    width: 60%;
    margin: auto;
}

.footer__cont p {
    color: var(--dark-blue);
}

.footer__cont .fab {
    color: var(--light-blue);
    font-size: 20px;
    margin: 0 10px;
}
</style>