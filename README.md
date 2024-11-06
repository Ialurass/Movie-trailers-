# Movie-trailers-

!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>f Movie Trailers</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Chakra+Petch:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>

<body>
    <header>f Movie Trailers</header>

    <section class="chamada">
        <div class="chamada-texto">
            <h1>ATRAVÉS DO ARANHAVERSO</h1>
            <p>#homem-aranha</p>
        </div>
        <div>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/gt_fAE1Eg2Q?si=EEv-tsY_b1B2OwKE"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </section>

    <section class="categoria">
        <h2>Filmes e séries</h2>
        <div class="categoria-videos">
            <!-- Trailer de The Last of Us -->
            <a href="https://www.youtube.com/watch?v=uLtkt8BonwM">
                <img src="https://img.youtube.com/vi/uLtkt8BonwM/maxresdefault.jpg" alt="Trailer de The Last of Us" />
            </a>
            <!-- Vídeo de Isabela Boscov sobre Curtindo a Vida Adoidado -->
            <a href="https://www.youtube.com/watch?v=Yf7vFz_U8ZU">
                <img src="https://img.youtube.com/vi/Yf7vFz_U8ZU/maxresdefault.jpg" alt="Isabela Boscov sobre Curtindo a Vida Adoidado" />
            </a>
            <!-- Trailer de Um Lugar Silencioso 1 -->
            <a href="https://www.youtube.com/watch?v=WR7cc5t7nJ4">
                <img src="https://img.youtube.com/vi/WR7cc5t7nJ4/maxresdefault.jpg" alt="Trailer de Um Lugar Silencioso 1" />
            </a>
            <!-- Trailer de Um Lugar Silencioso 2 -->
            <a href="https://www.youtube.com/watch?v=V4z6WpFqjsQ">
                <img src="https://img.youtube.com/vi/V4z6WpFqjsQ/maxresdefault.jpg" alt="Trailer de Um Lugar Silencioso 2" />
            </a>
        </div>
    </section>
</body>
</html>
/* Resetando margens e espaçamentos */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Estilo para o corpo da página */
body {
    background-color: black;
    color: white;
    font-family: "Chakra Petch", sans-serif;
    margin: 0;
    padding-bottom: 100px;
}

/* Estilo do cabeçalho */
header {
    text-align: center;
    padding: 20px;
    font-size: 32px;
    color: rgb(42, 122, 228);
    border-bottom: solid 2px rgb(42, 122, 228);
}

/* Estilo da seção chamada */
.chamada {
    background-color: rgb(184, 156, 213);
    padding: 80px 20px;
    display: flex;
    justify-content: center;
}

/* Estilo do texto na chamada */
.chamada-texto {
    margin-right: 5%;
}

h1 {
    font-size: 40px;
}

p {
    font-size: 20px;
}

/* Estilo da seção de categoria */
.categoria {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 50px;
}

.categoria h2 {
    font-size: 28px;
    color: rgb(42, 122, 228);
    margin-bottom: 20px;
}

/* Estilo dos vídeos */
.categoria-videos {
    display: flex;
    overflow-x: auto;
    gap: 10px;
    padding-bottom: 20px;
}

.categoria-videos img {
    width: 100%;
    max-width: 320px;
    opacity: 0.7;
    transition: opacity 0.3s ease, transform 0.3s ease;
}

.categoria-videos img:hover {
    opacity: 1;
    transform: scale(1.1);
    border: 3px solid rgb(42, 122, 228);
}

/* Adicionando um efeito visual ao passar o mouse */
.categoria-videos a {
    display: inline-block;
}
