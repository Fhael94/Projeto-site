<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>GRIKPH Industrial Facilities</title>

    <!-- Link para fontes atrativas do Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@500;700&family=Montserrat:wght@500&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        header {
            background-color: #0b1101;
            color: white;
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        /* Estilo para a logo e nome */
        header .logo {
            display: flex;
            align-items: center;
        }

        header .logo img {
            height: 70px;
            margin-right: 10px;
        }

        header .logo h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 26px;
            color: white;
            margin: 0;
        }

        /* Estilizando o menu de navegação */
        nav {
            display: flex;
        }

        nav ul {
            list-style: none;
            display: flex;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-family: 'Montserrat', sans-serif;
            font-weight: 500;
            font-size: 14px;
            text-transform: uppercase;
            transition: color 0.3s ease, transform 0.3s ease;
        }

        /* Efeito de hover nas abas */
        nav ul li a:hover {
            color: #ffa500;
            transform: scale(1.05);
        }

        main {
            display: flex;
            flex-wrap: wrap;
            height: 80vh;
        }

        .left-section, .right-section {
            flex: 1;
            min-width: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            text-align: center;
        }

        .left-section {
            background-color: #ffa500;
        }

        .login-form {
            background-color: white;
            padding: 35px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .login-form h2 {
            margin-bottom: 20px;
        }

        .login-form input {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        .login-form button {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        @media (max-width: 768px) {
            main {
                flex-direction: column;
                height: auto;
            }

            .left-section, .right-section {
                flex: none;
                width: 100%;
            }

            nav ul {
                flex-direction: column;
                text-align: center;
            }

            nav ul li {
                margin: 10px 0;
            }
        }
    </style>
</head>

<body>
    <header>
        <div class="logo">
            <img src="LOGO.png" alt="Logo GRIKPH" />
            <h1>GRIKPH Industrial Facilities</h1>
        </div>

        <nav>
            <ul>
                <li><a href="informativo.html">Quem somos</a></li>
                <li><a href="informativo.html">Facilities</a></li>
                <li><a href="informativo.html">Trabalhe Conosco</a></li>
                <li><a href="informativo.html">Contatos</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <div class="left-section">
            <div class="login-form">
                <h2><u>Login</u></h2>
                <form id="loginForm">
                    <input type="text" id="username" placeholder="Usuário" />
                    <input type="password" id="password" placeholder="Senha" />
                    <button type="submit">Entrar</button>
                </form>
                <p>Esqueceu a senha? <a href="#" id="forgotPasswordLink">Clique aqui!</a></p>
            </div>
        </div>
    </main>
</body>

</html>
