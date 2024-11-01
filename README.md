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
                <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBw8PEBINDg0NEBAPDw8PDw4NEA8QDQ8QFhEWGBURFRUYHSkgGBsoHRUTITMiKDUrLi4uFyAzODYvOCgtLisBCgoKDg0OFRAPFSsdFR8rKy03LSstKystLSssLSs1LzcuNy0rKy0tKzgrKystKy4tKysrLTcrKzctListKysrN//AABEIAKMBNgMBIgACEQEDEQH/xAAcAAEAAgIDAQAAAAAAAAAAAAAAAwcFCAIEBgH/xABGEAACAQMABgUGCgUNAAAAAAAAAQIDBBEFBxIhMVEGQXGBkRMUYZKxwSIjQlJicqGywtFkg6Kj8RUkMjNDU2NzgrPS4fD/xAAXAQEBAQEAAAAAAAAAAAAAAAAAAQID/8QAHxEBAQEBAAEEAwAAAAAAAAAAAAERAiEDEjGBMkFR/9oADAMBAAIRAxEAPwC8QAAAAAAAAAAAAAAAAAAAAAAAAAABxnJJZbwjH3N63uhuXPrf5FkGSB09FyzFrlJ+xf8AZ3CAAcI1YtuKkm1jKXVn+DA5gAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAARVqyj6XyFers8OPsOhNmpEca9VyeW+7qRBI5yI5GkY3SnSOrYuGxZTuYVNpz8lWp06sHHZxiM8KWcvrWMdeThT1lWH9vTvbWX6VbzVNdtWG1BL05PPazL529KhVXXWlTffBv8J4qh0q5sl5XV3O/dZKUZxcJJOLg04yi+DTXFE2hVvqP6q/am/eitOi/SXbewnujj4PVht+/2lm6AntQlPnP2RidO/T9vHPX6qS+WTABwaAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAY6vW+NlTwt0IzTzveZSTWOSxHf6SORLWppTlP5UsJvPUuCXIhkbiI5EUiSRFIqPCa4aW1o9S/u7mnP9ipH8SKUVV8y9tadPa0XXx8mVB+NeEX9kmUHkvX4z7HqOhF21c4zxh7JR/M2P6MRxbQfNyf2msfQ5/wA6j9V/eibQ6Bji2pL6Cfia7730+ef5aSeWQABwaAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAdGvxfadaRPXe99rIJHREUiKRLIikEed6d09rR10uVFz9WSl+E11Rsp0opbdldw65Wlwl2+Slg1rQvxBnOhizdw3dT7t6NqNHRxRprlTh7DV/oDDN2uzGO1/+8TaagsRiuUYr7DN+FjmADKgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAMdVe99pBIlqMhkdGUciKRJIikB1L+G1TqR+dTnHxi0axRibRyNZZ0dhuD+Q3HwePcSq9Lq1pZvFu64feNnUa46qqWb2P1oe02OM0gACKAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAB8Z9ONTg+xgY2ZDIlmRSOjKORFIkkRyAika4aZhi4uILds3VePq15fkbHTNeulFLZvryP6Zcy9atKS9pKr1mp+nm9i/pRNgih9SsM3bfJ/hL4M1QAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAOFZ/BfYcyK5fwX3e0QY6RFIkkRyOjKORHIkkRyAhmUH05jjSV2v8bPjCL95fkyh9YSxpS7X06D8bWk/eSq9lqNhm4m+W190u8pjUVD4yo/RL3FzmaoACAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAGL05e3NNJWltTr1JZy61ZUaNNLH9JpSk28vCSfB5a3ZyjZhr64345uL3SxJ5lwS6yyaPujNI3Cilexto1ZSairSdSdJLZb3ynFPO59XI73ni5HndJX0KVCVepKMY0tmrKW1lxjGpF7L689XpO5C7pySlGrTlFrKlGcWmuaeTftmJrLeeLkQXWkHsyjSUPK7OYKq5KnnOFtNLKXHwOj5xD58PWidCy0nSrVKzpTjU8lUhQk4vMVKMFPj176rXbF8hOZ5NZDQukb+U/J3tpawj8mvaXEqkM8pQqQjJdqzx7zL3j+D3ow0Z+T5PPP4PD2sytxPMIv0mc8jpyIpEkiJmkcWRyObOEgIplHazaezpOs/nwt5Puoxj+AvGZSmtZY0k/Tb0H9sl7iVXs9REf61+h+1FwFS6ho/F1n2/eLaM1QAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAABFdSxB+HiYavLPXy4GU0i8Q70eJ6a6a8ztKlaLSqNeTo/5ktyfcsy/wBLN8pXg9YfSjzirKyoz+JoVGqmMNVa0Xvb5qLbWOcW+TXha7Xfx3bmWx0V1SUa1rCvfVriFWtFTjTpOEfJxe+O25RblLG98MZx1ZMo9TVhw86ve50P+A0UlSqbTcptyb65vabfaz0HRfpHPR1dVlvpyxGvSSx5SmnxS+cstrta62WatTVhnPnd8+eXQ3/uyO61MWTpyVK6ulVw9iVV0pUk+pSioptdjGj0NncxnGM4TUoTUZxlHhKLWVL05TMvTqZilyefH+BWur67qU4VdHV041rKrKGy+Kg5PdnrxJS38nEsGlWUKc6sniFKDqTl82EU234JlE02QtnnKfTzR1R4VeUc8HOlUx4pPHeZC10xbVt1K5oTfzY1IOXq5yEZLJwkfIyOTAikUtrcWNJL02dB/vKy9xdUimtbtCT0jBxWc2VH/erkqva6ho/EVX6X95lrFYai6Tja1NpYbk+P15fkWeZqgAIAAAAAAAAAAAAAAAAAAAAAAAAAAAAADr39NypyUVl8UueOoqfT1vLSGlrLRsoyVGjtXd1tJqGxFr4Lz2KP60uA+NZ4llwE11Yx1Y4H0+JLkj6QAABVHTu0lZaZtr+EX5K/g7avsxbxVSSTeOeKT7Kcj2H8lSu7Gvb+UdJ3NKVKM8bWymuLjlZTzjG7cenwfFFLgkXRRN5qn0tFtQdjVj1ONapGTXpjKnheLMTW1aacjwstv6lzbJftTRsaBqY17s+inSe3w6NteU8cFG7tHD1XVafejuQuemNHdO1q1V9OjZ1PtpNMvgDVxS1p0i6Rp4raJov9XWoy73ty9h6Ho5oepeXMr3StKhBeQ8hTs1CpUSW1teUlUkkk8uXDfv8AGyANGN0RoW3tNrzeLgp4zHalKKxyz2mSAIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP/2Q==" alt="ps5">
             <h2>ps5</h2>
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
