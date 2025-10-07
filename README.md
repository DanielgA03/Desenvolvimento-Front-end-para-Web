<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ONG para adoção de animais de estimação - Dê uma Segunda Chance</title>
    
    <style>
        /* --- Estilos Globais --- */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f7f6; /* Cinza claro suave */
            color: #333;
        }
        
        h1, h2 {
            text-align: center;
            color: #007bff; /* Azul vibrante para títulos principais */
        }

        h1 {
            padding-top: 20px;
            margin-bottom: 10px;
        }

        h2 {
            border-bottom: 2px solid #007bff;
            display: inline-block;
            padding-bottom: 5px;
            margin-top: 40px;
        }

        
        section h2 {
            display: block;
            text-align: center;
        }

        main {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto; /* Centraliza o conteúdo principal */
        }
        
        p {
            margin-bottom: 15px;
            text-align: justify;
        }

        /* --- Navegação (Menu) --- */
        nav {
            background-color: #007bff; /* Fundo azul para o menu */
            padding: 10px 0;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        
        nav ul {
            list-style: none; 
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            flex-wrap: wrap; 
        }
        
        nav ul li {
            margin: 5px 15px;
        }
        
        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            padding: 8px 12px;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }

        nav ul li a:hover {
            background-color: #0056b3; /* Azul mais escuro ao passar o mouse */
            color: #ffc107; /* Amarelo para destaque */
        }

        /* --- Estilo da Imagem "Quem Somos" --- */
        .quem-somos-img {
            display: block; 
            margin-left: auto; 
            margin-right: auto; 
            max-width: 100%; 
            height: auto; 
            padding: 20px 0; 
            border-radius: 8px; /* Cantos arredondados */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* --- Layout dos Destaques (Carrossel) --- */
        .destaques-home {
            background-color: #e6f0ff; /* Fundo levemente azulado para a seção */
            padding: 30px 20px;
            margin-top: 30px;
            border-radius: 10px;
        }

        .carrossel-container {
            text-align: center;
        }

        .carrossel-container h3 {
            color: #d9534f; /* Cor de destaque */
            margin-bottom: 20px;
        }

        .carrossel-item {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
            margin-bottom: 20px;
            text-align: left;
        }

        .carrossel-item img {
            width: 100%;
            max-height: 250px;
            object-fit: cover; /* Garante que a imagem preencha o espaço sem distorcer */
            border-radius: 5px;
            margin-bottom: 15px;
        }

        .carrossel-item h4 {
            color: #28a745; /* Verde para nome do pet */
            margin-top: 0;
            font-size: 1.5em;
        }

        /* Layout em Grid para os itens do Carrossel (Desktop) */
        @media (min-width: 768px) {
            .carrossel-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* 3 colunas ou mais, ajustável */
                gap: 20px;
            }
            .carrossel-item:last-of-type {
                /* O último item do carrossel contém os botões CTA.
                   Se houver 3 itens e for uma tela grande, ele não precisa ocupar a largura total.
                   Se houver espaço para 3, o CTA fica abaixo do 3º pet. */
                grid-column: span 1; 
            }
        }


        /* --- Botões CTA (Call to Action) --- */
        .cta-box {
            background-color: #fff3cd; 
            border: 1px solid #ffeeba;
            padding: 20px;
            margin-top: 20px;
            text-align: center;
            border-radius: 8px;
            
            grid-column: 1 / -1; 
        }

        .cta-box p {
            font-size: 1.1em;
            color: #856404;
            text-align: center;
        }

        .botao-destaque {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px 5px;
            text-decoration: none;
            color: white;
            font-weight: bold;
            border-radius: 5px;
            transition: background-color 0.3s, transform 0.2s;
        }

        .adote-pet {
            background-color: #28a745; /* Verde */
        }

        .adote-pet:hover {
            background-color: #1e7e34;
            transform: scale(1.05);
        }

        .Como {
             /*'ajudar-agora'*/
            background-color: #d9534f; /* Vermelho */
        }

        .Como:hover {
            background-color: #c9302c;
            transform: scale(1.05);
        }

        /* --- Rodapé --- */
        footer {
            background-color: #343a40; /* Fundo escuro */
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 50px;
        }
    </style>
    </head>
<body>
    <header>
        <h1>Dê uma segunda chance ao amor</h1>
        
        <nav>
            <ul>
                
                <li> <a href="projeto.html">Projeto</a></li>
                <li> <a href="cadastro.html">Cadastro para Adoção</a></li>
                <li> <a href="sobre.html">Sobre Adote um Petz</a></li>
                <li> <a href="transparencia.html">Transparência</a></li>
                <li> <a href="doacoes.html">Como Doar</a></li>
                <li> <a href="voluntariado.html">Inscrição para Voluntáriado</a></li>
                <li> <a href="contato.html">Contato</a></li>
                <li> <a href="blog.html">Blog</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Quem Somos</h2>
            <p>Somos a voz e a ação em favor dos animais abandonados e em situação de risco. Nascemos da indignação com os maus-tratos e da profunda crença de que todo ser vivo merece uma vida digna, segura e cheia de afeto.

            Nossa equipe é formada por voluntários, protetores independentes e parceiros dedicados que trabalham incansavelmente para reverter o cenário de abandono em nossa comunidade. Atuamos com o Projeto "Recomeço de Patas" para oferecer mais do que um abrigo; oferecemos uma segunda chance.

            Desde 2024, nosso foco é o resgate, a reabilitação completa (incluindo tratamento veterinário, castração e vacinação) e a busca por um lar definitivo através da adoção responsável. Cada animal que ajudamos é a prova de que juntos podemos transformar a dor do abandono em uma história de amor e recomeço.

            Seja um apoiador, voluntário ou adotante. Junte-se a nós para construir um mundo onde a compaixão e o respeito prevaleçam.</p>
            
            <img src="patas.jpeg" alt="voluntarios em ação" class="quem-somos-img">
        </section>

        <section>
            <h2>Missão da ONG Amigão</h2>
            <p>Nossa missão é dupla e inegociável:

            Resgatar e Reabilitar: Resgatar animais vítimas de abandono e maus-tratos, fornecendo todos os cuidados essenciais para sua recuperação física e emocional, com foco prioritário na castração como ferramenta de controle populacional.
        
            Promover a Posse Responsável: Educar a sociedade sobre os deveres de um tutor, incentivando a adoção consciente e combatendo o ciclo de abandono e crueldade.

            Trabalhamos para ser uma ponte segura entre a rua e o sofá. Nossa missão é garantir que cada patinha encontre seu caminho de volta para o lar, promovendo o bem-estar animal e a conscientização humana.</p>
        </section>
        <section class="destaques-home">
            <h2>Prontos para Encontrar o Amor</h2>

            <div class="carrossel-container">
                <h3>Os Destaques da Semana</h3>
                
                <div class="carrossel-item">
                    <img src="luna.jepg.jpg" alt="Pet para Adoção - Luna"> 
                    <h4>Luna</h4>
                    <p>6 meses, "Conheçam Luna, nossa gatinha que veio para provar que felino é sinônimo de afeto! Ela é uma gata extremamente dócil e carente, do tipo que derrete no seu colo assim que é pega. Luna adora amassar 'pãozinho' e te seguir pela casa, e o ronrono dela é tão alto que parece um motorzinho.
                        Apesar de amar a atenção humana, ela também é brincalhona e adora sessões de caça com varinhas ou bolinhas. Luna é sociável, adaptando-se bem a novos ambientes e até a outros pets (com a devida introdução). Se você procura uma companheira fiel que irá te dar amor incondicional e te aquecer nas noites frias, Luna é a sua gata."
                    </p>
                </div>

                <div class="carrossel-item">
                    <img src="leo.jpeg" alt="Pet para Adoção - Leo">
                    <h4>Leo</h4>
                    <p>2 anos, "Conheçam Leo, a nossa dose diária de alegria e energia! Como todo filhote, Leo é extremamente brincalhão e agitado. Ele adora explorar cada canto, seja do lar temporário ou do jardim. Sua curiosidade é incansável, e ele transforma qualquer brinquedo (ou até um chinelo, se não estiver de olho!) no melhor passatempo do mundo.
                    Apesar de toda a bagunça típica da idade, Leo é muito dócil e carinhoso. Ele é sempre o primeiro a vir pedir colo depois das brincadeiras e adora longas sessões de carinho na barriga. Ele se dá bem com outros cães e está aprendendo rapidamente sobre socialização. Se você procura um companheiro cheio de vida, pronto para longos passeios e com muito amor para dar, Leo é o seu match perfeito!"
                    </p>
                </div>

                <div class="carrossel-item">
                     <img src="max.jepg.jpg" alt="Pet para Adoção - Max"> 
                    <h4>Max</h4>
                    <p>3 anos, "Max é um filhote com um coração gigante, mas que precisa de um tempinho para confiar. Nos primeiros momentos, ele é um pouco tímido e desconfiado, observando tudo com cautela. Ele não é de chegar invadindo, mas prefere se aproximar no tempo dele, buscando a segurança de quem o acolhe.
                        Uma vez que ele se sente seguro, Leo se revela um companheiro extremamente fiel e carinhoso. Ele adora ficar juntinho, colado ao seu humano de confiança. É dócil, paciente e ideal para um lar que entenda a importância de uma adaptação gradual e que ofereça um ambiente tranquilo e amoroso. Ele está pronto para florescer com a paciência certa."
                    </p> 
                </div>

                <div class="cta-box">
                    <p>
                        Sua doação garante que tenhamos ração, vacinas e tratamento veterinário para criar mais finais felizes como o dele. 
                    </p>
                    
                    <a href="cadastro.html" class="botao-destaque adote-pet">
                        Adote um Pet
                    </a> <br>
                    <a href="doacoes.html" class="botao-destaque Como">
                        Como Ajudar Agora
                    </a>
                </div>

            </div> </section>
    </main>
    <footer>
        <p>&copy; 2025 ONG Amigão - Todos os direitos reservados.</p>
    </footer>
</body>
</html>
