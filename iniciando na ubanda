<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desvende a Umbanda: Seu Guia Essencial</title>
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@400;700&family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --color-primary: #336699; /* Azul marinho */
            --color-secondary: #FFCC00; /* Dourado/Amarelo */
            --color-text: #333;
            --color-light: #f4f4f4;
            --color-white: #ffffff;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: var(--color-light);
            color: var(--color-text);
            line-height: 1.6;
        }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://source.unsplash.com/1600x900/?african-spirituality,nature-elements,sacred-symbols') no-repeat center center/cover; /* Imagem de fundo com elementos que remetem à Umbanda. Substitua por imagens reais de sua escolha se quiser. */
            color: var(--color-white);
            text-align: center;
            padding: 80px 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 60vh;
            position: relative;
        }

        .hero::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.4); /* Leve sobreposição para clarear o texto */
            z-index: 1;
        }

        .hero-content {
            position: relative;
            z-index: 2;
            max-width: 800px;
        }

        .hero h1 {
            font-family: 'Merriweather', serif;
            font-size: 3.2em;
            margin-bottom: 20px;
            color: var(--color-secondary);
            text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
        }

        .hero p {
            font-size: 1.4em;
            margin-bottom: 30px;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }

        .btn {
            display: inline-block;
            background-color: var(--color-secondary);
            color: var(--color-primary);
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.2em;
            transition: background-color 0.3s ease, transform 0.3s ease;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
        }

        .btn:hover {
            background-color: #e6b800; /* Um tom um pouco mais escuro de dourado */
            transform: translateY(-3px);
        }

        .container {
            max-width: 1000px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .section {
            padding: 60px 0;
            text-align: center;
        }

        .section h2 {
            font-family: 'Merriweather', serif;
            font-size: 2.5em;
            color: var(--color-primary);
            margin-bottom: 30px;
            position: relative;
        }

        .section h2::after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background-color: var(--color-secondary);
            margin: 15px auto 0;
            border-radius: 2px;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .feature-item {
            background-color: var(--color-white);
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            text-align: left;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .feature-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.15);
        }

        .feature-item h3 {
            color: var(--color-primary);
            font-size: 1.5em;
            margin-bottom: 15px;
        }

        .feature-item p {
            font-size: 1em;
            color: var(--color-text);
        }

        .author-bio {
            background-color: var(--color-primary);
            color: var(--color-white);
            padding: 60px 20px;
            text-align: center;
        }

        .author-bio h2 {
            color: var(--color-secondary);
            font-family: 'Merriweather', serif;
            font-size: 2.2em;
            margin-bottom: 20px;
        }

        .author-bio p {
            max-width: 700px;
            margin: 0 auto 30px;
            font-size: 1.1em;
            line-height: 1.8;
        }

        .call-to-action {
            background-color: var(--color-light);
            padding: 60px 20px;
            text-align: center;
        }

        .call-to-action h2 {
            color: var(--color-primary);
            font-family: 'Merriweather', serif;
            font-size: 2.8em;
            margin-bottom: 25px;
        }

        .price {
            font-size: 2.5em;
            font-weight: bold;
            color: var(--color-secondary);
            margin-bottom: 20px;
        }

        .footer {
            background-color: var(--color-primary);
            color: var(--color-white);
            text-align: center;
            padding: 30px 20px;
            font-size: 0.9em;
        }

        .footer p {
            margin: 0;
        }

        /* Responsividade */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5em;
            }

            .hero p {
                font-size: 1.2em;
            }

            .section h2 {
                font-size: 2em;
            }

            .btn {
                padding: 12px 25px;
                font-size: 1em;
            }
        }

        @media (max-width: 480px) {
            .hero h1 {
                font-size: 2em;
            }

            .hero p {
                font-size: 1em;
            }

            .section h2 {
                font-size: 1.8em;
            }

            .features-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <header class="hero">
        <div class="hero-content">
            <h1>Desvende os Primeiros Passos na Umbanda</h1>
            <p>Seja bem-vindo(a) ao seu guia essencial para iniciar sua jornada de fé e conhecimento dentro da Umbanda. Entenda seus fundamentos, orixás e práticas de forma clara e respeitosa.</p>
            <a href="#comprar" class="btn">Quero Iniciar Minha Jornada Agora!</a>
        </div>
    </header>

    <section class="section container">
        <h2>O que você vai aprender com este E-book?</h2>
        <div class="features-grid">
            <div class="feature-item">
                <h3>Introdução à Umbanda</h3>
                <p>Entenda a história, os pilares e a filosofia que sustentam essa religião tão rica e brasileira.</p>
            </div>
            <div class="feature-item">
                <h3>Os Orixás e suas Vibrações</h3>
                <p>Conheça os principais Orixás, suas características, domínios e como se relacionam com nossa vida.</p>
            </div>
            <div class="feature-item">
                <h3>Práticas e Rituais Simples</h3>
                <p>Aprenda sobre a importância da prece, oferendas e como se conectar de forma respeitosa com a espiritualidade.</p>
            </div>
            <div class="feature-item">
                <h3>Vocabulário Essencial</h3>
                <p>Um glossário prático para você se familiarizar com os termos e expressões mais utilizados na Umbanda.</p>
            </div>
            <div class="feature-item">
                <h3>Ética e Respeito na Fé</h3>
                <p>Compreenda a importância da conduta, do respeito e da caridade dentro da prática umbandista.</p>
            </div>
            <div class="feature-item">
                <h3>Mitos e Verdades</h3>
                <p>Desmistifique preconceitos e informações errôneas, consolidando um conhecimento sólido e verdadeiro.</p>
            </div>
        </div>
    </section>

    <section class="author-bio">
        <div class="container">
            <h2>Sobre o Autor(a)</h2>
            <p>Com anos de dedicação e estudo à Umbanda, [Nome do Autor(a)] é um(a) conhecedor(a profundo(a) dos seus ensinamentos e práticas. Este e-book é o resultado de uma paixão por compartilhar o saber e guiar novos corações no caminho da fé umbandista, com clareza, respeito e muito amor.</p>
            <p>Seu objetivo é tornar a Umbanda acessível, desmistificando-a e oferecendo um ponto de partida seguro e inspirador para todos que sentem o chamado dessa linda religião.</p>
        </div>
    </section>

    <section id="comprar" class="call-to-action">
        <div class="container">
            <h2>Pronto para Iniciar sua Jornada na Umbanda?</h2>
            <p>Não perca a oportunidade de mergulhar neste universo de fé, sabedoria e acolhimento.</p>
            <div class="price">Por apenas R$ 49,90</div>
            <a href="LINK_PARA_PAGINA_DE_COMPRA" class="btn">Comprar o E-book Agora!</a>
            <p style="margin-top: 20px; font-size: 0.9em; color: var(--color-text);">Acesso imediato após a confirmação do pagamento.</p>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 Seu Nome/Nome da Empresa. Todos os direitos reservados.</p>
            <p>Contato: seuemail@exemplo.com</p>
        </div>
    </footer>

</body>
</html>
