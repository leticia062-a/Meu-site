<!DOCYTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name=viewport" content="width=device-width, intial-scale=1.0">
    <title>Olá site</title>
    <style>
        body {
            background-color: #f0f8ff; /* cor de fundo clara */
            font-family: Arial, sans-serif; /* fonte moderna */
            text-align: center; /* centralizar o texto */
            padding: 50px; /* espaço interno */
        }

        h1 {
            color: #3333cc; /* azul escuro */
            transition: color 0.3 ease; /* animação suave */
        }
        h1:hover {
            color:#ff5733; /* cor quando passar o mouse */
        }

        p {
            color: #555555; /* cinza escuro */
            font-size: 18px; /* tamanho da fonte */
        }

        button {
            background-color: #4c87af; /* azul claro */
            color: white;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 20px;
        }

        button:hover {
            background-color: #6150bd; /* roxo ao passar o mouse */
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #3333cc; /* Cor normal do link */
            font-weight: bold;
            transition: color 0.3 ease; /* Transição suave na cor */ 
        }

        nav a:hover {
            color: #ec1c1c; /* Cor quando passar o mouse */
        }

        .card-container {
            .card-container 
             display: flex;
            justify-content: center; /* Alinha as cards horizontalmente */
            gap: 30px;
            flex-wrap: wrap; /* Não vai quebrar para a próxima linha, vai ficar tudo na mesma linha */
            margin-top: 30px;
        }
          
    
        .card h3 {
            margin-bottom: 10px;
        }

        .card p {
            flex-grow: 1; /* Para o texto ocupar o espaço disponível */
        }

        .card:hover {
            transform: scale(1.05);  /* Efeito de escala ao passar o mouse */
            transition: transform 0.3s ease-in-out; /* transição suave */
        }
        
        form {
            margin-top: 30px;
            background-color: white;
            padding: 40px;
            border-radius: 10px;
            width: 300px;
            margin-left: auto;
            margin-right: auto;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
        }

        input, textarea {
            width: 90%;
            padding: 15px;
            margin: 15px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 18px;
        }
        footer {
            margin-top: 50px;
            font-size: 14px;
            color: #888;
        }

        #topo {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #3333cc;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 50%;
            font-size: 18px;
            cursor: pointer;
        }
    </style>
    </head>
    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#servicos">Serviços</a>
        <a href="#contato">Contato</a>
    </nav>
    <body>
        <h1>Bem-vindo ao meu site!</h1>
        <p>Conheça meus trabalhos.</p>

        <h2 id="servicos">Meus Serviços</h2>

        <div class="card-container">
            <div class="card">
            <h3>Sites Responsivos</h3>
            <p>Criação de sites bonitos que funcionam em todos os dispositivos.</p>
        </div>
    
        <div class="card">
            <h3>Loja Virtual</h3>
            <p>Montagem de lojas online para vender seus produtos.</p>
        </div>
    
        <div class="card">
            <h3>Consultoria</h3>
            <p>Te ajudo a tirar suas ideias do papel para a internet!</p>
        </div>
    
        <h2 id="contato">Contato</h2>
    
        <form>
            <input type="text" placeholder="Seu Nome"rows="4" required><br>
            <input type="email" placeholder="Seu Email" rows="4" required><br>
            <textarea placeholder="Sua Mensagem" rows="4" required></textarea><br>
            <button type="submit">Enviar</button>
        </form>
        
        <button onclick="window.location.href='https://wa.me/5599982647496'">
            Fale comigo no WhatsApp
        </button>
        <p>
            📧 Email: leticianobre068@gmail.com <br>
            📱 WhatsApp: (99) 98264-7496
        </p>
    
        <footer>
            &copy; 2025 Leticia Desenvolvedor. Todos os direitos reservados.
        </footer>
    
        <button id="topo" onclick="window.scrollTo({top: 0, behavior: 'smooth'})">↑</button>
    
    </body>
    </html>
