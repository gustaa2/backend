# backend


index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lojinha</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Minha Lojinha</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Cadastrar</a></li>
                <li><a href="#">Logar</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="produtos">
            <div class="produto">
                <img src="https://http2.mlstatic.com/D_Q_NP_852209-MLU74345962453_022024-P.webp" alt="Celular">
            <h2>Celular</h2> 
            <p>Preço: R$ 140,80</p>
        </div>
        <div class="produto">
            <img src="https://media.pichau.com.br/media/catalog/product/cache/ef72d3c27864510e5d4c0ce69bade259/t/g/tgt_b110_-_monitor_kit_teclado_e_mousee_6.jpg" alt="Computador">
            <h2>Computador</h2>
            <p>Preço: R$ 480,75</p>
            </div>
            <div class="produto">
                <img src="https://www.sony.com/image/049f2e40c5919cfd7b407fa4f0a3f183?fmt=pjpeg&wid=1200&hei=470&bgcolor=F1F5F9&bgc=F1F5F9" alt="tv">
             <h2>tv</h2>
             <p>Preço: R$ 320,05</p>
            </div>
        </section>
    </main>
</body>
</html>


style.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 1em 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

.produtos {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.produto {
    background: white;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 10px;
    text-align: center;
    margin: 10px;
    width: 200px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.produto img {
    max-width: 100%;
    height: auto;
}

footer {
    text-align: center;
    padding: 1em 0;
    background-color: #4CAF50;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}
