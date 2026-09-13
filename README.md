<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Murilo's Hub</title>
    <style>

        * {
            padding: 0px;
            margin: 0px;
            font-family: Arial, Helvetica, sans-serif;
        }

        header {
            background-color: blue;
            color: white;
            text-align: center;
            padding-bottom: 15px;
            padding-top: 10px;
            box-shadow: 2px 2px 2px 2px rgba(0, 0, 0, 0.356);
            
        }

        body > main {
            background-color: white;
            margin: auto;
            max-width: 700px;
            height: auto;
            text-align: justify;
            padding: 10px 0px 0px 0px;
            border-radius: 0px 0px 15px 15px;
            box-shadow: 2px 2px 2px 2px rgba(0, 0, 0, 0.247);
        
        }

        main > section > p {
            padding: 10px;
            text-align: left;
        }

        img {
            display: block;
            margin: auto;
            height: 50%;
        }

        h2 {
            margin-bottom: 10px;
            padding: 10px;
            background-image: linear-gradient(to right, blue, transparent);
            color: white;
            text-shadow: 2px 2px 2px black;
            box
        }
        
        h3 {
            margin-bottom: 10px;
            padding: 10px;
            background-image: linear-gradient(to right, blue, transparent);
            color: white;
            text-shadow: 2px 2px 2px black;
            box
        }

        ul {
            margin-left: 25px;
        }

        li {
            margin-bottom: 5px;
        }

        a {
            color: black;
            text-decoration: none;
        }

        a:hover {
            background-color: blue;
            color: white;
            transition: 0.3s;
            padding: 5px;
            text-decoration: overline;
        }
        
        body {
            background-image: linear-gradient(to top, blue, lightblue);
            
        }

        footer {
            padding: 5px;
            background-color: blue;
            color: white;
            font-size: 1em;
            text-align: center;
        }
    </style>
</head>

<body>
    <header>
        <h1>html + css</h1>
    </header>

    <main>
        <section>
            <h2>Me chamo Murilo Neves.</h2>
            <p>
                Olá!
        
            Aqui estão, por hora, todos os meus arquivos que desenvolvi em HTML.
            </p>
            <p>
            Creio ser um acervo de arquivos pequeno ainda, pois sou um desenvolvedor iniciante, porém minha meta é deixar isso mais completo, acompanhando assim minha carreira/jornada no mundo de desenvolvimento web e em outras linguagens de programação também.
            </p>
        
            <p>
            Não existe um limite!
            </p>
        </section>

        <h3>Projetos</h3>

        <ul>
            <li>
                <a href='https://murilodcg.github.io/projeto-cordel/' target='_blank'>Cordel Mordeno</a>
            </li>
            <li>
                <a href='/projeto-android/' target='_blank'>Projeto Android</a>
            </li>
            
        </ul>
        <abbr title="Murilo"><img src="https://lh3.googleusercontent.com/d/1684LTlOH9yxGuKk35flFYMpn7SQvgKWZ" alt="Murilo em cartoon!"></abbr>

    </main>
    <footer>
        <p>
            Pagina criada por Murilo Neves para Github
        </p>
    </footer>
</body>
</html>