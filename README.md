<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agro Forte e um Futuro Sustentável</title>

    <!-- CSS interno -->
    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family: Arial, sans-serif;
        }

        body{
            background:#f4fdf4;
            color:#333;
        }

        header{
            background:linear-gradient(135deg,#2e7d32,#4caf50);
            color:white;
            text-align:center;
            padding:40px;
        }

        nav{
            background:#1b5e20;
        }

        nav ul{
            list-style:none;
            display:flex;
            justify-content:center;
        }

        nav ul li{
            margin:15px;
        }

        nav a{
            color:white;
            text-decoration:none;
            font-weight:bold;
        }

        .hero{
            text-align:center;
            padding:60px 20px;
        }

        .hero h2{
            font-size:2.5rem;
            color:#2e7d32;
        }

        .hero p{
            margin-top:15px;
            font-size:1.2rem;
        }

        .conteudo{
            max-width:1000px;
            margin:auto;
            padding:50px 20px;
        }

        .conteudo h2{
            color:#2e7d32;
            margin-bottom:20px;
        }

        .cards{
            display:flex;
            flex-wrap:wrap;
            justify-content:center;
            gap:20px;
            padding:40px;
        }

        .card{
            background:white;
            width:280px;
            padding:20px;
            border-radius:12px;
            box-shadow:0 0 10px rgba(0,0,0,0.1);
            text-align:center;
        }

        .card h3{
            color:#388e3c;
            margin-bottom:10px;
        }

        .destaque{
            text-align:center;
        }

        button{
            margin-top:20px;
            padding:12px 25px;
            border:none;
            background:#4caf50;
            color:white;
            border-radius:8px;
            cursor:pointer;
            font-size:1rem;
        }

        button:hover{
            background:#2e7d32;
        }

        footer{
            background:#1b5e20;
            color:white;
            text-align:center;
            padding:20px;
            margin-top:30px;
        }
    </style>
</head>
<body>

<header>
    <div class="container">
        <h1>🌱 Agro Forte e um Futuro Sustentável</h1>
        <p>Agricultura Sustentável para um mundo melhor</p>
    </div>
</header>

<nav>
    <ul>
        <li><a href="#inicio">Início</a></li>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#beneficios">Benefícios</a></li>
        <li><a href="#futuro">Futuro</a></li>
    </ul>
</nav>

<section id="inicio" class="hero">
    <h2>Produzir hoje, preservar amanhã</h2>
    <p>
        A agricultura sustentável busca equilibrar produção de alimentos,
        preservação ambiental e desenvolvimento econômico.
    </p>
</section>

<section id="sobre" class="conteudo">
    <h2>🌾 O que é Agricultura Sustentável?</h2>

    <p>
        É um modelo de produção agrícola que utiliza os recursos naturais
        de forma responsável, reduzindo impactos ambientais e garantindo
        alimentos para as futuras gerações.
    </p>
</section>

<section id="beneficios" class="cards">

    <div class="card">
        <h3>💧 Economia de Água</h3>
        <p>Sistemas de irrigação inteligentes evitam desperdícios.</p>
    </div>

    <div class="card">
        <h3>🌱 Solo Saudável</h3>
        <p>Práticas sustentáveis preservam a fertilidade do solo.</p>
    </div>

    <div class="card">
        <h3>🐝 Biodiversidade</h3>
        <p>Proteção de espécies importantes para o equilíbrio ambiental.</p>
    </div>

</section>

<section id="futuro" class="conteudo destaque">
    <h2>🚜 Agro Forte e Futuro Sustentável</h2>

    <p>
        O agronegócio sustentável combina tecnologia, inovação e
        responsabilidade ambiental para alimentar a população e proteger
        o planeta.
    </p>

    <button id="btnMensagem">
        Saiba Mais
    </button>

    <p id="mensagem"></p>
</section>

<footer>
    <p>
        Projeto Agrinho 2026 - Agro Forte e um Futuro Sustentável 🌎
    </p>
</footer>

<!-- JS interno -->
<script>
    const botao = document.getElementById("btnMensagem");
    const mensagem = document.getElementById("mensagem");

    botao.addEventListener("click", () => {
        mensagem.innerHTML =
        "🌱 A agricultura sustentável é essencial para garantir alimentos, preservar a natureza e construir um futuro melhor para todos!";
    });
</script>

</body>
</html>
