<template>
    <div>
        <link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/flickity/1.0.0/flickity.css'>
        <link rel="stylesheet" href="./style.css">
        </link>
        <div class="book-store">
            <div class="header">
                <div class="browse">
                    <div class="browse-category">
                        Browse Category
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor"
                            stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                            class="feather feather-chevron-down">
                            <path d="M6 9l6 6 6-6" />
                        </svg>
                    </div>
                    <div class="search-bar">
                        <input type="text" placeholder="Search Book" />
                    </div>
                </div>
                <div class="profile">
                    <div class="user-profile">
                    </div>
                    <div class="profile-menu">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor"
                            stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                            class="feather feather-menu">
                            <path d="M3 12h18M3 6h18M3 18h18" />
                        </svg>
                        Menu
                    </div>
                </div>
            </div>
            <div class="book-slide">
                <div class="book js-flickity" data-flickity-options='{ "wrapAround": true }'>
                    <div class="book-cell">
                        <div class="book-img">
                            <img src="https://images-na.ssl-images-amazon.com/images/I/41yv3AcAtjL._SX346_BO1,204,203,200_.jpg"
                                alt="" class="book-photo">
                        </div>

                       
                       <!---Aqui começa a demontrar exemplos de livros e sugestões-->
                       <div class="bokks">
                        <div class="book-content">
                            <div class="book-title">A hipótese do amor</div>
                            <div class="book-author">por Ali Hazelwoods</div>
                            <div class="rate">
                                <fieldset class="rating">
                                    <input type="checkbox" id="star5" name="rating" value="5" />
                                    <label class="full" for="star5"></label>
                                    <input type="checkbox" id="star4" name="rating" value="4" />
                                    <label class="full" for="star4"></label>
                                    <input type="checkbox" id="star3" name="rating" value="3" />
                                    <label class="full" for="star3"></label>
                                    <input type="checkbox" id="star2" name="rating" value="2" />
                                    <label class="full" for="star2"></label>
                                    <input type="checkbox" id="star1" name="rating" value="1" />
                                    <label class="full" for="star1"></label>
                                </fieldset>
                            </div>
                            <div class="book-sum">Quando um namoro de mentira entre cientistas encontra a irresistível
                                força da atração, todas as teorias cuidadosamente calculadas sobre o amor são postas à
                                prova.</div>
                            <div class="book-see">See The Book</div>
                        </div>
                    </div>
                    <div class="book-cell">
                        <div class="book-img">
                            <img src="https://images-na.ssl-images-amazon.com/images/I/51h04+d0j4L._SX343_BO1,204,203,200_.jpg"
                                alt="" class="book-photo">
                        </div>
                        <div class="book-content">
                            <div class="book-title">Clube do livro dos homens</div>
                            <div class="book-author">Por Lyssa Adams</div>
                            <div class="rate">
                                <fieldset class="rating blue">
                                    <input type="checkbox" id="star6" name="rating" value="5" />
                                    <label class="full1" for="star6"></label>
                                    <input type="checkbox" id="star7" name="rating" value="4" />
                                    <label class="full1" for="star7"></label>
                                    <input type="checkbox" id="star8" name="rating" value="3" />
                                    <label class="full1" for="star8"></label>
                                    <input type="checkbox" id="star9" name="rating" value="2" />
                                    <label class="full1" for="star9"></label>
                                    <input type="checkbox" id="star10" name="rating" value="1" />
                                    <label class="full1" for="star10"></label>
                                </fieldset>

                                <span class="book-voters">1.987 voters</span>
                            </div>
                            <div class="book-sum">O que acontece no clube do livro fica no clube do livro.</div>
                            <div class="book-see book-blue">See The Book</div>
                        </div>
                    </div>
                    <div class="book-cell">
                        <div class="book-img">
                            <img src="https://m.media-amazon.com/images/I/41kAPeTE0HS._SY346_.jpg" alt=""
                                class="book-photo">
                        </div>
                        <div class="book-content">
                            <div class="book-title">Sunkissed</div>
                            <div class="book-author">Por Bianca Barros</div>
                            <div class="rate">
                                <fieldset class="rating purple">
                                    <input type="checkbox" id="star11" name="rating" value="5" />
                                    <label class="full" for="star11"></label>
                                    <input type="checkbox" id="star12" name="rating" value="4" />
                                    <label class="full" for="star12"></label>
                                    <input type="checkbox" id="star13" name="rating" value="3" />
                                    <label class="full" for="star13"></label>
                                    <input type="checkbox" id="star14" name="rating" value="2" />
                                    <label class="full" for="star14"></label>
                                    <input type="checkbox" id="star15" name="rating" value="1" />
                                    <label class="full" for="star15"></label>
                                </fieldset>

                            </div>
                            <div class="book-sum">Depois de conhecer Enrique Navarro, piloto de uma das equipes
                                adversárias, a menina que amava neve vai descobrir que o inverno só era sua estação
                                preferida porque ela ainda não sabia o que era ser beijada pelo Sol.</div>
                            <div class="book-see book-pink">See The Book</div>
                        </div>
                    </div>
                    <div class="book-cell">
                        <div class="book-img">
                            <img src="https://images-na.ssl-images-amazon.com/images/I/41kJVFM0AfL._SY344_BO1,204,203,200_QL70_ML2_.jpg"
                                alt="" class="book-photo">
                        </div>
                        <div class="book-content">
                            <div class="book-title">A vida invisivel de Addie Larue</div>
                            <div class="book-author">Por V.E Schwab</div>
                            <div class="rate">
                                <fieldset class="rating yellow">
                                    <input type="checkbox" id="star16" name="rating" value="5" />
                                    <label class="full" for="star16"></label>
                                    <input type="checkbox" id="star17" name="rating" value="4" />
                                    <label class="full" for="star17"></label>
                                    <input type="checkbox" id="star18" name="rating" value="3" />
                                    <label class="full" for="star18"></label>
                                    <input type="checkbox" id="star19" name="rating" value="2" />
                                    <label class="full" for="star19"></label>
                                    <input type="checkbox" id="star20" name="rating" value="1" />
                                    <label class="full" for="star20"></label>
                                </fieldset>
                                <span class="book-voters">1.987 voters</span>
                            </div>
                            <div class="book-sum">Uma vida que ninguém lembra. Um livro que ninguém esquece.

                                Em A vida invisível de Addie LaRue, o aguardado best-seller de V.E. Schwab, conheça
                                Addie e se perca em sua vida invisível ― porém memorável.</div>
                            <div class="book-see book-yellow">See The Book</div>
                        </div>
                    </div>
                    <div class="book-cell">
                        <div class="book-img">
                            <img src="https://images-na.ssl-images-amazon.com/images/I/41xVhz5sL1L._SX346_BO1,204,203,200_.jpg"
                                alt="" class="book-photo">
                        </div>
                        <div class="book-content">
                            <div class="book-title">Os sete maridos de Evelyn Hugo</div>
                            <div class="book-author">Por Taylor Jenkins Reid</div>
                            <div class="rate">
                                <fieldset class="rating dark-purp">
                                    <input type="checkbox" id="star21" name="rating" value="5" />
                                    <label class="full" for="star21"></label>
                                    <input type="checkbox" id="star22" name="rating" value="4" />
                                    <label class="full" for="star22"></label>
                                    <input type="checkbox" id="star23" name="rating" value="3" />
                                    <label class="full" for="star23"></label>
                                    <input type="checkbox" id="star24" name="rating" value="2" />
                                    <label class="full" for="star24"></label>
                                    <input type="checkbox" id="star25" name="rating" value="1" />
                                    <label class="full" for="star25"></label>
                                </fieldset>
                                <span class="book-voters">1.987 voters</span>
                            </div>
                            <div class="book-sum">Com todo o esplendor que só a Hollywood do século passado pode
                                oferecer, esta é uma narrativa inesquecível sobre os sacrifícios que fazemos por amor, o
                                perigo dos segredos e o preço da fama.</div>
                            <div class="book-see book-purple">See The Book</div>
                        </div>
                    </div>
                </div>
            </div>
            </div>
            <div class="main-wrapper">
                <div class="books-of">
                    <div class="week">
                        <div class="author-title">Autores</div>
                        <div class="author">
                            <img src="https://m.media-amazon.com/images/S/amzn-author-media-prod/80rvrf599r2ernjs2f4qf8ne70._SX450_.jpg"
                                alt="" class="author-img">
                            <div class="author-name">Taylor Jenkins Reid</div>
                        </div>
                        <div class="author">
                            <img src="https://m.media-amazon.com/images/S/amzn-author-media-prod/9ki8og63ijbmroq5bj0t5o7vj1._SX450_.jpg"
                                alt="" class="author-img">
                            <div class="author-name">Collen Hoover</div>
                        </div>
                        <div class="author">
                            <img src="https://m.media-amazon.com/images/S/amzn-author-media-prod/7qf9scd1ro1kucklcpho1o1ipp._SX450_.jpg"
                                alt="" class="author-img">
                            <div class="author-name">Mariana Zapata</div>
                        </div>
                        <div class="author">
                            <img src="https://m.media-amazon.com/images/S/amzn-author-media-prod/qhq3voilho234t4i5u4chvvi7s._SX450_.jpg"
                                alt="" class="author-img">
                            <div class="author-name">Holly Black</div>
                        </div>
                        <div class="author">
                            <img src="https://m.media-amazon.com/images/S/amzn-author-media-prod/1sfbtfpold57ji8c10ngl1ncur._SX450_.jpg"
                                alt="" class="author-img">
                            <div class="author-name">Tahereh Mafi</div>
                        </div>
                        <div class="author">
                            <img src="https://m.media-amazon.com/images/S/amzn-author-media-prod/4f278s9dqprfvdtnh9hssf45n8._SX450_.jpg"
                                alt="" class="author-img">
                            <div class="author-name">V. E. Schwab</div>
                        </div>
                    </div>

                    <div class="week year">
                        <div class="author-title">Famosinhos</div>
                        <div class="year-book">
                            <img src="https://images-na.ssl-images-amazon.com/images/I/51BSHmTVwsS._SX335_BO1,204,203,200_.jpg"
                                alt="" class="year-book-img">
                            <div class="year-book-content">
                                <div class="year-book-name">O principe cruel</div>
                                <div class="year-book-author">Por Holly Black</div>
                            </div>
                        </div>
                        <div class="year-book">
                            <img src="https://images-na.ssl-images-amazon.com/images/I/51wx3A+5s6L._SY344_BO1,204,203,200_.jpg"
                                alt="" class="year-book-img">
                            <div class="year-book-content">
                                <div class="year-book-name">Heartstopper</div>
                                <div class="year-book-author">Por Alice Oceman</div>
                            </div>
                        </div>
                        <div class="year-book">
                            <img src="https://m.media-amazon.com/images/I/51F9SrA6iIL.jpg" alt="" class="year-book-img">
                            <div class="year-book-content">
                                <div class="year-book-name">Amor & Azeitonas </div>
                                <div class="year-book-author">Por Jenna Evans Welch</div>
                            </div>
                        </div>
                        <div class="year-book">
                            <img src="https://m.media-amazon.com/images/I/511xDIdUsdS._SY346_.jpg" alt=""
                                class="year-book-img">
                            <div class="year-book-content">
                                <div class="year-book-name">Os padrinhos</div>
                                <div class="year-book-author">Por Olivia Uviplais</div>
                            </div>
                        </div>
                        <div class="year-book">
                            <img src="https://m.media-amazon.com/images/I/41083EVmg5L.jpg" alt="" class="year-book-img">
                            <div class="year-book-content">
                                <div class="year-book-name">Metanoia</div>
                                <div class="year-book-author">Por Cora Menestrelli</div>
                            </div>
                        </div>
                    </div>
                    <div class="overlay"></div>
                </div>
                <div class="popular-books">
                    <div class="main-menu">
                        <div class="genre">Populares por genero</div>
                        <div class="book-types">
                            <a href="#" class="book-type active"> Todos os generos</a>
                            <a href="#" class="book-type"> Romance</a>
                            <a href="#" class="book-type"> Fantasia</a>
                            <a href="#" class="book-type"> Distopia</a>
                            <a href="#" class="book-type"> Infanto Juvenil</a>
                            <a href="#" class="book-type"> Suspense/Terror</a>
                        </div>
                    </div>
                    <div class="book-cards">
                        <div class="book-card">
                            <div class="content-wrapper">
                                <img src="https://m.media-amazon.com/images/I/41JF1hE+k7L.jpg" alt=""
                                    class="book-card-img">
                                <div class="card-content">
                                    <div class="book-name">Leitura de verão </div>
                                    <div class="book-by">Por Emily Henry</div>
                                    <div class="rate">
                                        <fieldset class="rating book-rate">
                                            <input type="checkbox" id="star-c1" name="rating" value="5">
                                            <label class="full" for="star-c1"></label>
                                            <input type="checkbox" id="star-c2" name="rating" value="4">
                                            <label class="full" for="star-c2"></label>
                                            <input type="checkbox" id="star-c3" name="rating" value="3">
                                            <label class="full" for="star-c3"></label>
                                            <input type="checkbox" id="star-c4" name="rating" value="2">
                                            <label class="full" for="star-c4"></label>
                                            <input type="checkbox" id="star-c5" name="rating" value="1">
                                            <label class="full" for="star-c5"></label>
                                        </fieldset>
                                        <span class="book-voters card-vote">1.987 voters</span>
                                    </div>
                                    <div class="book-sum card-sum">Em Leitura de verão, uma escritora de romances que
                                        não acredita mais no amor e um escritor literário sufocado pela rotina se
                                        envolvem em um desafio que pode subverter tudo o que eles sempre pensaram sobre
                                        o que é ser feliz. </div>
                                </div>
                            </div>
                            <div class="likes">
                                <div class="like-profile">
                                    <img src="https://fotografia.folha.uol.com.br/galerias/4009-taylor-swift" alt=""
                                        class="like-img">
                                </div>
                                <div class="like-profile">
                                    <img src="https://entretetizei.com.br/cnco-anuncia-a-saida-de-joel-pimentel-do-grupo/"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-profile">
                                    <img src="https://www.wepick.com.br/etc/geracao-z-afinal-quem-e-olivia-rodrigo/"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-name"><span>Samantha William</span> and<span> 2 other friends</span>
                                    like this</div>
                            </div>
                        </div>
                        <div class="book-card">
                            <div class="content-wrapper">
                                <img src="https://images-na.ssl-images-amazon.com/images/I/41VestZBywL._SY344_BO1,204,203,200_QL70_ML2_.jpg"
                                    alt="" class="book-card-img">
                                <div class="card-content">
                                    <div class="book-name">Estilhaça-me</div>
                                    <div class="book-by">Por Tahereh Mafi</div>
                                    <div class="rate">
                                        <fieldset class="rating book-rate">
                                            <input type="checkbox" id="star-c6" name="rating" value="5">
                                            <label class="full" for="star-c6"></label>
                                            <input type="checkbox" id="star-c7" name="rating" value="4">
                                            <label class="full" for="star-c7"></label>
                                            <input type="checkbox" id="star-c8" name="rating" value="3">
                                            <label class="full" for="star-c8"></label>
                                            <input type="checkbox" id="star-c9" name="rating" value="2">
                                            <label class="full" for="star-c9"></label>
                                            <input type="checkbox" id="star-c10" name="rating" value="1">
                                            <label class="full" for="star-c10"></label>
                                        </fieldset>
                                        <span class="book-voters card-vote">1.987 voters</span>
                                    </div>
                                    <div class="book-sum card-sum">Um toque é o bastante.

                                        Com apenas um toque, Juliette Ferrars é capaz de fazer um homem adulto se
                                        ajoelhar de dor e implorar por misericórdia. Um único toque de Juliette pode
                                        matar. </div>
                                </div>
                            </div>
                            <div class="likes">
                                <div class="like-profile">
                                    <img src="https://randomuser.me/api/portraits/women/63.jpg" alt="" class="like-img">
                                </div>
                                <div class="like-name"><span>Kimberly Jones</span> like this</div>
                            </div>
                        </div>
                        <div class="book-card">
                            <div class="content-wrapper">
                                <img src="https://images-na.ssl-images-amazon.com/images/I/51i7kH+rh9L._SY344_BO1,204,203,200_.jpg"
                                    alt="" class="book-card-img">
                                <div class="card-content">
                                    <div class="book-name">É assim que acaba</div>
                                    <div class="book-by">Por Collen Hoover</div>
                                    <div class="rate">
                                        <fieldset class="rating book-rate">
                                            <input type="checkbox" id="star-c11" name="rating" value="5">
                                            <label class="full" for="star-c11"></label>
                                            <input type="checkbox" id="star-c12" name="rating" value="4">
                                            <label class="full" for="star-c12"></label>
                                            <input type="checkbox" id="star-c13" name="rating" value="3">
                                            <label class="full" for="star-c13"></label>
                                            <input type="checkbox" id="star-c14" name="rating" value="2">
                                            <label class="full" for="star-c14"></label>
                                            <input type="checkbox" id="star-c15" name="rating" value="1">
                                            <label class="full" for="star-c15"></label>
                                        </fieldset>
                                        <span class="book-voters card-vote">1.987 voters</span>
                                    </div>
                                    <div class="book-sum card-sum">O romance mais pessoal da carreira de Colleen Hoover,
                                        É assim que acaba discute temas como violência doméstica e abuso psicológico de
                                        forma sensível e direta.

                                    </div>
                                </div>
                            </div>
                            <div class="likes">
                                <div class="like-profile">
                                    <img src="https://randomuser.me/api/portraits/women/63.jpg" alt="" class="like-img">
                                </div>
                                <div class="like-profile">
                                    <img src="https://pbs.twimg.com/profile_images/2452384114/noplz47r59v1uxvyg8ku.png"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-name"><span>Adam</span> and<span> Kimberly</span> like this</div>
                            </div>
                        </div>
                        <div class="book-card">
                            <div class="content-wrapper">
                                <img src="https://m.media-amazon.com/images/I/41ioLoh7cKL._SY346_.jpg" alt=""
                                    class="book-card-img">
                                <div class="card-content">
                                    <div class="book-name">Peculiar</div>
                                    <div class="book-by">Por Nathalia Santos</div>
                                    <div class="rate">
                                        <fieldset class="rating book-rate">
                                            <input type="checkbox" id="star-c16" name="rating" value="5">
                                            <label class="full" for="star-c16"></label>
                                            <input type="checkbox" id="star-c17" name="rating" value="4">
                                            <label class="full" for="star-c17"></label>
                                            <input type="checkbox" id="star-18" name="rating" value="3">
                                            <label class="full" for="star-c18"></label>
                                            <input type="checkbox" id="star-c19" name="rating" value="2">
                                            <label class="full" for="star-c19"></label>
                                            <input type="checkbox" id="star-c20" name="rating" value="1">
                                            <label class="full" for="star-c20"></label>
                                        </fieldset>
                                        <span class="book-voters card-vote">1.987 voters</span>
                                    </div>
                                    <div class="book-sum card-sum">Até que ponto o ditado “os opostos se atraem” é
                                        verdadeiro?Ela é conhecida como a garota peculiar.Ele é conhecido como o garoto
                                        tímido e nerd.. </div>
                                </div>
                            </div>
                            <div class="likes">
                                <div class="like-profile">
                                    <img src="https://randomuser.me/api/portraits/women/63.jpg" alt="" class="like-img">
                                </div>
                                <div class="like-profile">
                                    <img src="https://pbs.twimg.com/profile_images/2452384114/noplz47r59v1uxvyg8ku.png"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-profile">
                                    <img src="https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1400&q=80"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-name"><span>Samantha William</span> and<span> 2 other friends</span>
                                    like this</div>
                            </div>
                        </div>
                        <div class="book-card">
                            <div class="content-wrapper">
                                <img src="https://images-na.ssl-images-amazon.com/images/I/41UD0aWfQ5L._SY344_BO1,204,203,200_QL70_ML2_.jpg"
                                    alt="" class="book-card-img">
                                <div class="card-content">
                                    <div class="book-name">Perdida</div>
                                    <div class="book-by">Por Carina Rissi</div>
                                    <div class="rate">
                                        <fieldset class="rating book-rate">
                                            <input type="checkbox" id="star-c21" name="rating" value="5">
                                            <label class="full" for="star-c21"></label>
                                            <input type="checkbox" id="star-c22" name="rating" value="4">
                                            <label class="full" for="star-c22"></label>
                                            <input type="checkbox" id="star-c23" name="rating" value="3">
                                            <label class="full" for="star-c23"></label>
                                            <input type="checkbox" id="star-c24" name="rating" value="2">
                                            <label class="full" for="star-c24"></label>
                                            <input type="checkbox" id="star-c25" name="rating" value="1">
                                            <label class="full" for="star-c25"></label>
                                        </fieldset>
                                        <span class="book-voters card-vote">1.987 voters</span>
                                    </div>
                                    <div class="book-sum card-sum">Perdida: Um amor que ultrapassa as barreiras do tempo
                                        é um romance divertido e apaixonante que une o melhor de dois mundos
                                        aparentemente muito diferentes. </div>
                                </div>
                            </div>
                            <div class="likes">
                                <div class="like-profile">
                                    <img src="https://randomuser.me/api/portraits/women/63.jpg" alt="" class="like-img">
                                </div>
                                <div class="like-profile">
                                    <img src="https://pbs.twimg.com/profile_images/2452384114/noplz47r59v1uxvyg8ku.png"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-profile">
                                    <img src="https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1400&q=80"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-name"><span>Angelina Stone</span> and<span> 2 other friends</span> like
                                    this</div>
                            </div>
                        </div>
                        <div class="book-card">
                            <div class="content-wrapper">
                                <img src="https://m.media-amazon.com/images/I/51yvcUb5tFL._SY346_.jpg" alt=""
                                    class="book-card-img">
                                <div class="card-content">
                                    <div class="book-name">Percy Jackson</div>
                                    <div class="book-by">por Rick Riordan</div>
                                    <div class="rate">
                                        <fieldset class="rating book-rate">
                                            <input type="checkbox" id="star-c1" name="rating" value="5">
                                            <label class="full" for="star-c1"></label>
                                            <input type="checkbox" id="star-c2" name="rating" value="4">
                                            <label class="full" for="star-c2"></label>
                                            <input type="checkbox" id="star-c3" name="rating" value="3">
                                            <label class="full" for="star-c3"></label>
                                            <input type="checkbox" id="star-c4" name="rating" value="2">
                                            <label class="full" for="star-c4"></label>
                                            <input type="checkbox" id="star-c5" name="rating" value="1">
                                            <label class="full" for="star-c5"></label>
                                        </fieldset>
                                        <span class="book-voters card-vote">1.987 voters</span>
                                    </div>
                                    <div class="book-sum card-sum">O garoto-problema Percy Jackson é um deles. Tem
                                        experiências estranhas em que deuses e monstros mitológicos parecem saltar das
                                        páginas dos livros direto para a sua vida. O garoto-problema Percy Jackson é um
                                        deles. Tem experiências estranhas em que deuses e monstros mitológicos parecem
                                        saltar das páginas dos livros direto para a sua vida. </div>
                                </div>
                            </div>
                            <div class="likes">
                                <div class="like-profile">
                                    <img src="https://pbs.twimg.com/profile_images/2452384114/noplz47r59v1uxvyg8ku.png"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-profile">
                                    <img src="https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1400&q=80"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-name"><span>George</span> and<span> Mike</span> like this</div>
                            </div>
                        </div>
                        <div class="book-card">
                            <div class="content-wrapper">
                                <img src="https://images-na.ssl-images-amazon.com/images/I/51mftSv6YmS._SX336_BO1,204,203,200_.jpg"
                                    alt="" class="book-card-img">
                                <div class="card-content">
                                    <div class="book-name">O acordo</div>
                                    <div class="book-by">Por Elle Kennedy</div>
                                    <div class="rate">
                                        <fieldset class="rating book-rate">
                                            <input type="checkbox" id="star-c1" name="rating" value="5">
                                            <label class="full" for="star-c1"></label>
                                            <input type="checkbox" id="star-c2" name="rating" value="4">
                                            <label class="full" for="star-c2"></label>
                                            <input type="checkbox" id="star-c3" name="rating" value="3">
                                            <label class="full" for="star-c3"></label>
                                            <input type="checkbox" id="star-c4" name="rating" value="2">
                                            <label class="full" for="star-c4"></label>
                                            <input type="checkbox" id="star-c5" name="rating" value="1">
                                            <label class="full" for="star-c5"></label>
                                        </fieldset>
                                        <span class="book-voters card-vote">1.987 voters</span>
                                    </div>
                                    <div class="book-sum card-sum"> Mas o que era apenas uma troca de favores entre dois
                                        opostos acaba se tornando uma amizade inesperada. Até que um beijo faz que
                                        Hannah e Garret precisem repensar os termos de seu acordo. </div>
                                </div>
                            </div>
                            <div class="likes">
                                <div class="like-profile">
                                    <img src="https://randomuser.me/api/portraits/women/63.jpg" alt="" class="like-img">
                                </div>
                                <div class="like-profile">
                                    <img src="https://pbs.twimg.com/profile_images/2452384114/noplz47r59v1uxvyg8ku.png"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-profile">
                                    <img src="https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1400&q=80"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-name"><span>Samantha William</span> and<span> 2 other friends</span>
                                    like this</div>
                            </div>
                        </div>
                        <div class="book-card">
                            <div class="content-wrapper">
                                <img src="https://images-na.ssl-images-amazon.com/images/I/41k7k3utgBL._SX324_BO1,204,203,200_.jpg"
                                    alt="" class="book-card-img">
                                <div class="card-content">
                                    <div class="book-name">Sua alteza real</div>
                                    <div class="book-by">Por Rachel Hawkins</div>
                                    <div class="rate">
                                        <fieldset class="rating book-rate">
                                            <input type="checkbox" id="star-c1" name="rating" value="5">
                                            <label class="full" for="star-c1"></label>
                                            <input type="checkbox" id="star-c2" name="rating" value="4">
                                            <label class="full" for="star-c2"></label>
                                            <input type="checkbox" id="star-c3" name="rating" value="3">
                                            <label class="full" for="star-c3"></label>
                                            <input type="checkbox" id="star-c4" name="rating" value="2">
                                            <label class="full" for="star-c4"></label>
                                            <input type="checkbox" id="star-c5" name="rating" value="1">
                                            <label class="full" for="star-c5"></label>
                                        </fieldset>
                                        <span class="book-voters card-vote">1.987 voters</span>
                                    </div>
                                    <div class="book-sum card-sum">. A princesa Flora pode até ser um novo capítulo em
                                        sua vida amorosa, mas Millie não quer ser coadjuvante na história de ninguém. As
                                        chances de um “felizes para sempre” podem ser poucas, mas isso não significa que
                                        elas não existam...
                                    </div>
                                </div>
                            </div>
                            <div class="likes">
                                <div class="like-profile">
                                    <img src="https://randomuser.me/api/portraits/women/63.jpg" alt="" class="like-img">
                                </div>
                                <div class="like-profile">
                                    <img src="https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1400&q=80"
                                        alt="" class="like-img">
                                </div>
                                <div class="like-name"><span>Samantha William</span> and<span> Jonathan</span> like this
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style>
@charset "UTF-8";
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap");
@import url(//netdna.bootstrapcdn.com/font-awesome/3.2.1/css/font-awesome.css);

:root {
    --body-bg-color: #9de6ff;
    --body-color-light: #8b939c;
    --body-font: "Roboto", sans-serif;
    --page-bg-color: #f2f5f7;
    --body-color: #3d4954;
    --border-color: #b8bec3;
    --placeholder: #ccd0d2;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
    ;
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
    border-radius: 8px;
}

img {
    max-width: 100%;
}

html {
    box-sizing: border-box;
    -webkit-font-smoothing: antialiased;
}

body {
    background-color: rgb(246, 255, 164);
    background-image: url("../static/fundo.png");
    background-attachment: fixed;
    font-family: var(--body-font);
    color: var(--body-color);
    font-weight: 400;
    margin: 0;
}

.likes,
.year-book,
.author,
.main-menu,
.profile-menu,
.profile,
.browse-category,
.browse,

.header {
    display: flex;
    align-items: center;
    background-color: rgba(255, 255, 255, 0.288);
    padding: 20px 0;
}

.book-store {
    display: flex;
    flex-direction: column;
    background-color: var(--page-bg-color);
    margin: 0 auto;
    overflow: hidden;
    box-shadow: 0px 2px 50px 10px rgba(0, 0, 0, 0.21);
}

.header {
    height: 70px;
    width: 100%;

    padding: 0 30px;
    font-size: 14px;
    font-weight: 500;
    color: var(--body-color-light);
    justify-content: space-between;
    flex-shrink: 0;
}
.bokks{
     display: flex;
    max-width: 1100px;
    margin: 0 auto;
    flex-wrap: wrap;
    padding: 0 12%
}
.search-bar {
    position: relative;
}

.search-bar input {
    height: 100%;
    width: 100%;
    display: block;
    background-color: transparent;
    border: none;
    font-weight: 600;
    padding: 0 10px 0 40px;
    background-repeat: no-repeat;
    background-size: 15px;
    background-position: 15px 50%;
    color: var(--body-color);
    font-family: var(--body-font);
}

.search-bar input::placeholder {
    color: var(--placeholder);
}

.browse-category {
    border-right: 1px solid var(--border-color);
    white-space: nowrap;
}

.browse-category svg {
    width: 16px;
    margin: 2px 10px 0 8px;
}

.header-title {
    font-size: 16px;
    font-weight: 400;
    margin-right: 120px;
}

.header-title span {
    font-weight: 500;
    color: var(--body-color);
}

.user-img {
    width: 28px;
    height: 28px;
    border-radius: 50%;
    margin-right: 15px;
}

.user-profile {
    position: relative;
    cursor: pointer;
    flex-shrink: 0;
}

.user-profile:before {
    content: "";
    position: absolute;
    background-color: #f86d72;
    width: 7px;
    height: 7px;
    border-radius: 50%;
    border: 2px solid var(--theme-bg-color);
    right: 12px;
    top: -3px;
    border: 2px solid #fff;
}

.profile {
    flex-shrink: 0;
}

.profile-menu {
    border-left: 1px solid var(--border-color);
}

.profile svg {
    width: 16px;
    margin: 0 8px 0 15px;
    flex-shrink: 0;
}

.book-slide {
    width: 100%;
}

.book {
    background: #fff;
}

.book-cell {
    position: relative;
    display: flex;
    padding: 25px;
    width: 40%;
    height: 250px;
    margin-right: 1px;
}

.book-cell:nth-child(1) {
    background-color: #fdd802;
}

.book-cell:nth-child(2) {
    background-color: #a4e0eb;
}

.book-cell:nth-child(3) {
    background-color: #fdd802;
}

.book-cell:nth-child(4) {
    background-color: #a4e0eb;
}

.book-cell:nth-child(5) {
    background-color: #fdd802;
}

.book-cell:nth-child(6) {
    background-color: #a4e0eb;
}

.flickity-page-dots {
    display: none;
}

.flickity-prev-next-button .arrow {
    fill: #d6d6d6;
}

.flickity-prev-next-button svg {
    left: 25%;
    top: 25%;
    width: 50%;
    height: 50%;
}

.flickity-prev-next-button.previous {
    left: 15px;
}

.flickity-prev-next-button.next {
    right: 15px;
}

.flickity-viewport {
    overflow: visible;
}

.book-photo {
    width: 180px;
    flex-shrink: 0;
    bottom: -35px;
    left: 35px;
    border-radius: 2px;
    box-shadow: -2px 6px 19px 0px #7f818e;
    transition: 0.3s ease;
}

.book-photo:hover {
    transform: scale(1.03);
}

.book-img {
    flex-shrink: 0;
}

.book-title {
    text-overflow: ellipsis;
    white-space: nowrap;
    overflow: hidden;
}

.book-title {
    color: #ffffff;
    font-weight: 600;
}

.book-author {
    margin-top: 3px;
    font-size: 14px;
    text-overflow: ellipsis;
    white-space: nowrap;
    overflow: hidden;
}

.book-content {
    padding: 0 20px;
    color: #ffffff;
    overflow: hidden;
}

fieldset,
label {
    margin: 0;
    padding: 0;
    display: inline-block;
    vertical-align: middle;
}

h1 {
    font-size: 0.5em;
    margin: 10px;
}

.rating {
    border: none;
}

.rating>input {
    display: none;
}

.rating>label:before {
    margin-right: 5px;
    margin-top: 10px;
    font-size: 0.9em;
    font-family: FontAwesome;
    display: inline-block;
    content: "";
}

.rating>label {
    color: #fff;
    float: right;
}

.rating>input:checked~label,
.rating:not(:checked)>label:hover,
.rating:not(:checked)>label:hover~label {
    color: #d85d61;
}

.rating>input:checked+label:hover,
.rating>input:checked~label:hover,
.rating>label:hover~input:checked~label,
.rating>input:checked~label:hover~label {
    color: #d85d61;
}

.blue>input:checked~label,
.blue:not(:checked)>label:hover,
.blue:not(:checked)>label:hover~label {
    color: #458997;
}

.blue>input:checked+label:hover,
.blue>input:checked~label:hover,
.blue>label:hover~input:checked~label,
.blue>input:checked~label:hover~label {
    color: #458997;
}

.purple>input:checked~label,
.purple:not(:checked)>label:hover,
.purple:not(:checked)>label:hover~label {
    color: #a76287;
}

.purple>input:checked+label:hover,
.purple>input:checked~label:hover,
.purple>label:hover~input:checked~label,
.purple>input:checked~label:hover~label {
    color: #a76287;
}

.yellow>input:checked~label,
.yellow:not(:checked)>label:hover,
.yellow:not(:checked)>label:hover~label {
    color: #ffad58;
}

.yellow>input:checked+label:hover,
.yellow>input:checked~label:hover,
.yellow>label:hover~input:checked~label,
.yellow>input:checked~label:hover~label {
    color: #ffad58;
}

.dark-purp>input:checked~label,
.dark-purp:not(:checked)>label:hover,
.dark-purp:not(:checked)>label:hover~label {
    color: #905587;
}

.dark-purp>input:checked+label:hover,
.dark-purp>input:checked~label:hover,
.dark-purp>label:hover~input:checked~label,
.dark-purp>input:checked~label:hover~label {
    color: #905587;
}

.book-voters {
    color: #fff;
    vertical-align: sub;
    font-size: 13px;
    margin-left: 7px;
    white-space: nowrap;
    margin-top: 7px;
}

.book-sum {
    margin-top: 20px;
    font-size: 14px;
    overflow: hidden;
    display: -webkit-box;
    -webkit-line-clamp: 3;
    -webkit-box-orient: vertical;
}

.book-see {
    margin-top: 25px;
    text-align: center;
    background-color: #fff;
    color: #fbadaf;
    font-weight: 600;
    padding: 8px;
    font-size: 14px;
    width: 160px;
    border-radius: 20px;
}

.book-see:hover {
    color: #ff6e72;
}

.book-see.book-blue {
    color: #a4e0eb;
}

.book-see.book-blue:hover {
    color: #22cdec;
}

.book-see.book-pink {
    color: #edb9d6;
}

.book-see.book-pink:hover {
    color: #ff6dbe;
}

.book-see.book-yellow {
    color: #fdca95;
}

.book-see.book-yellow:hover {
    color: #fb9124;
}

.book-see.book-purple {
    color: #cbb5e2;
}

.book-see.book-purple:hover {
    color: #a764ec;
}

.main-wrapper {
    width: 100%;
    display: flex;
    flex-grow: 1;
    margin-top: 100px;
    overflow: hidden;
}

.books-of {
    width: 320px;
    display: flex;
    flex-direction: column;
    overflow-y: auto;
    overflow-x: hidden;
    flex-shrink: 0;
}

.popular-books {
    flex-grow: 1;
    padding: 0 30px 50px;
    overflow-y: auto;
}

.genre {
    font-weight: 500;
    font-size: 15px;
}

.main-menu {
    white-space: nowrap;
    padding-bottom: 15px;
    border-bottom: 1px solid #dcddde;
    position: sticky;
    top: 0;
    right: 0;
    background-color: var(--page-bg-color);
    z-index: 2;
}

.book-types {
    margin-left: auto;
}

.book-types a {
    text-decoration: none;
    color: var(--body-color);
    font-size: 14px;
}

.book-type+.book-type {
    margin-left: 20px;
}

.book-type {
    position: relative;
    transition: 0.2s;
}

.book-type.active,
.book-type:hover {
    -webkit-text-stroke: 0.3px;
}

.book-type.active:before,
.book-type:hover:before {
    content: "";
    position: absolute;
    width: 28px;
    height: 2px;
    bottom: -17px;
    right: 15px;
    background-color: #67d4ea;
    box-shadow: 0px -1px 5px 0px #67d4ea;
}

.book-type:nth-child(2):before {
    right: 12px;
}

.book-type:nth-child(3):before {
    right: 8px;
}

.book-type:nth-child(4):before {
    right: 6px;
}

.book-type:nth-child(5):before {
    right: 20px;
}

.week {
    padding: 0 30px;
}

.author+.author {
    margin-top: 20px;
}

.author-name {
    font-size: 14px;
}

.author:last-child {
    margin-bottom: 40px;
}

.author-title {
    padding: 0 0 20px;
    font-weight: 500;
    font-size: 15px;
}

.author-img {
    border-radius: 50%;
    width: 30px;
    height: 30px;
    margin-right: 16px;
    object-fit: cover;
    object-position: center;
}

.year-book-img {
    width: 45px;
    margin-right: 16px;
}

.year-book-name {
    margin-bottom: 15px;
    font-weight: 500;
}

.year-book-author {
    font-size: 13px;
}

.year-book+.year-book {
    margin-top: 20px;
}

.year-book-content {
    display: flex;
    flex-direction: column;
    font-size: 14px;
}

.overlay {
    position: sticky;
    bottom: 0;
    left: 0;
    width: 340px;
    flex-shrink: 0;
    background: linear-gradient(to bottom, rgba(255, 255, 255, 0) 0%, #f2f5f7 65%, #f2f5f7 100%);
    height: 60px;
    margin-left: -35px;
}

.book-cards {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-column-gap: 40px;
    grid-row-gap: 40px;
    padding-top: 40px;
    position: relative;
}

.book-card {
    margin-top: 20px;
    background-color: #fff;
    height: 270px;
    box-shadow: -1px 3px 8px -1px rgba(0, 0, 0, 0.1);
    border-radius: 4px;
    display: flex;
    flex-direction: column;
    cursor: pointer;
    padding: 0 0 20px 20px;
    color: var(--body-color-light);
}

.book-card-img {
    width: 160px;
    margin-top: -35px;
    border-radius: 2px;
    box-shadow: 0px 1px 7px 2px #c7c9d3;
    border-bottom: 1px solid #dcddde;
    object-fit: cover;
    margin-bottom: 20px;
    transition: 0.3s ease;
}

.book-card-img:hover {
    transform: scale(1.04);
}

.card-content {
    color: var(--body-color);
    padding: 30px;
    overflow: hidden;
    position: relative;
}

.book-name {
    font-weight: 500;
    text-overflow: ellipsis;
    overflow: hidden;
    white-space: nowrap;
}

.book-by {
    font-size: 13px;
    color: var(--body-color-light);
    margin-top: 4px;
    text-overflow: ellipsis;
    overflow: hidden;
    white-space: nowrap;
}

.book-rate>label {
    color: #cccccc;
}

.rate {
    display: inline-block;
    white-space: nowrap;
}

.book-rate>input:checked~label,
.book-rate:not(:checked)>label:hover,
.book-rate:not(:checked)>label:hover~label {
    color: #ff9700;
}

.book-rate>input:checked+label:hover,
.book-rate>input:checked~label:hover,
.book-rate>label:hover~input:checked~label,
.book-rate>input:checked~label:hover~label {
    color: #ff9700;
}

.card-vote {
    color: var(--body-color-light);
}

.card-sum {
    color: var(--body-color-light);
    font-size: 13px;
    line-height: 1.6em;
    -webkit-line-clamp: 4;
    margin-top: 15px;
}

.content-wrapper {
    display: flex;
    border-bottom: 1px solid #ebedef;
    position: relative;
}

.content-wrapper:before {
    content: "";
    position: absolute;
    background-color: #8f98a9;
    background-color: #aaaebc;
    box-shadow: 0 -6px 0 0 #aaaebc, 0 6px 0 0 #aaaebc;
    width: 4px;
    height: 4px;
    border: 0;
    padding: 0;
    right: 12px;
    top: 17px;
    border-radius: 50%;
    margin-left: auto;
}

.like-profile {
    margin-top: 8px;
}

.like-profile+.like-profile {
    margin-left: -5px;
}

.like-img {
    border-radius: 50%;
    width: 28px;
    object-fit: cover;
    border: 2px solid #fff;
}

.like-name {
    font-size: 13px;
    margin-left: 15px;
    text-overflow: ellipsis;
    overflow: hidden;
    white-space: nowrap;
}

.like-name span {
    font-weight: 600;
}

@media (max-width: 1103px) {
    .book-cell {
        width: 60%;
    }
}

@media (max-width: 765px) {
    .book-cell {
        width: 80%;
    }
}

@media (max-width: 575px) {
    .book-cell {
        width: 100%;
    }
}

@media (max-width: 458px) {
    .book-photo {
        width: 180px;
    }

    .book-voters {
        display: none;
    }
}

@media (max-width: 420px) {
    .book-see {
        width: 120px;
        font-size: 13px;
    }

    .book-photo {
        width: 130px;
    }

    .main-wrapper {
        margin-top: 50px;
    }
}

@media (max-width: 360px) {
    .rating>label:before {
        font-size: 0.8em;
    }
}

@media (max-width: 1220px) {
    .card-vote {
        display: none;
    }
}

@media (max-width: 1085px) {
    .book-rate>label {
        font-size: 0.7em;
    }
}

@media (max-width: 1045px) {
    .books-of {
        display: none;
    }
}

@media (max-width: 725px) {

    .browse-category,
    .search-bar {
        display: none;
    }

    .header-title {
        margin-right: auto;
    }

    .book-cards {
        grid-template-columns: 1fr;
    }

    .book-types {
        display: none;
    }
}

@media (max-width: 372px) {
    .card-content {
        padding: 20px;
    }
}
</style>