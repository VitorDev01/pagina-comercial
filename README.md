<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1.0">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/swiffy-slider@1.6.0/dist/js/swiffy-slider.min.js" crossorigin="anonymous" defer></script>
    <link href="https://cdn.jsdelivr.net/npm/swiffy-slider@1.6.0/dist/css/swiffy-slider.min.css" rel="stylesheet" crossorigin="anonymous">
    
    <title></title>
    <style> 
      @import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@200&display=swap');

      body { 
              /*Largura da página*/
              min-height: 100vh;
              background-color: #320000;
              
      }
      /*Escondendo os botes */
      .hide {
              display:none;
            }
            input[type="checkbox"] {
              display: none;
            }
            #btn-a:checked ~ .hide {
              display: block;
            }
            #btn-a:not(:checked) ~ .hide {
              display: none;
            }
            #btn-b:checked ~ .hide {
              display: block;
            }
              #btn-b:not(:checked) ~ .hide {
              display: none;
            }
            #btn-c:checked ~ .hide {
              display: block;
            }
            #btn-c:not(:checked) ~ .hide {
              display: none;
            }
            #btn-d:checked ~ .hide {
              display: block;
            }
            #btn-d:not(:checked) ~ .hide {
              display: none;
            }
            
            img {
              margin: auto;
              margin-top: 50px;
              display: block;
              height: 206px;
              width: 206px;
              border-radius: 50%;
            }
            
            h1 {
              color: #fff;
              font: 400 30px/1.6 "Source Sans Pro",sans-serif;
              text-align: center;
            }
     
            p {
              color: #fff;
              font: 400 20px/1.6 "Source Sans Pro",sans-serif;
              
            }
     
            #btn-1, #btn-2 , #btn-3 , #btn-4{
              background-color: #713021;
              border-color: #5d2417;
              margin-left: 5px;
              margin-right: 5px;
              border-radius: 10px;
              width: 100%;
            }
 
            .area p {
              margin: 15px;
              font: 400 20px/1.6 "Source Sans Pro",sans-serif;
            }

            .area {
             border: 3px solid ;
             border-top-color: #320000;
             border-bottom-color: #320000;
             border-right-color: #320000;
             border-left-color: #713021;
             display: block;
             margin: 10px;
             border-radius: 1px;
             
            }
            ul {
             list-style: none;
           } 
           a { /*Links menu*/
            color: white;
            text-decoration: none;
            font: 370 18px/1.6 "Source Sans Pro",sans-serif;
          }
        
          a:hover { /*cor ao tocar nos links*/
           background:rgba(0, 0, 0, .09);
           width: 20px;
          }
          i {
            margin-right: 10px;
          }
          .swiffy-slider {
            height: 150px;
            width: 150px;
            margin: 40px;
       
          }
          /*Menu a esquerda*/
          #menu {
            float: right;
            
          }
          
          mark {
            background-color: #8d4925;
            color: white;
            border-radius: 15px;
          }
    </style>
    <body>
    <!--foto-->
    <img src="eu3.jpg">
    <!-- Titulo -->

    <h1>@Vitor Oliveira <i class="fa fa-coffee" aria-hidden="true"></i></h1>
    
    <!-- Parágrafos-->
     <input type="checkbox" id="btn-a">
          <button id="btn-1">
          <!-- botão pessoa -->
          <label for= "btn-a" >
            <p><strong><i class="fa fa-user" aria-hidden="true"></i>Sobre Mim</strong></p>
          </label>
          </button>
          <div class="hide">
            <div class="area">
              <p>Bem vindo a minha página :), um breve resumo sobre min até por que se eu for escrever tudo aqui vai virar uma biografia kkk.
              <br><br>
              Sou do Rj Angra dos Reis conhecida muito por ser uma cidade turística, tenho 22 anos Canceriano nato e metade taurino, aberto a todo tipo de conhecimento que agregue no meu  desenvolvimento pessoal, aí que entra meu interesse em tarô e astrologia, estudando e praticando a mais de um ano e sempre tirando disso um novo aprendizado seja para o dia-a-dia pra lidar com pessoas, comunicação entre outras coisas.
              <br><br>
              Sobre profissão e carreira Atualmente estou  estudando programação front-end que faz parte do desenvolvimento web inclusive esta página foi feita por mim com cores do café mimha bebida favorita por sinal.
              <br><br>
               Abaixo mais informações sobre contato e consultas online.
              </p>
             </div>
          </div>
         <br><br>
          <input type="checkbox" id="btn-b">
          <!-- Botão -->
          <button id="btn-2">
          <label for= "btn-b" >
            <p><strong><i class="fa fa-list"></i>Contatos</strong></p>
          </label>
          </button>
        
          <div class="hide">
            <div class="area">
           
           <ul id="menu" role="menu">
             <li><a href="https://wa.me/5524992717594?text=Olá+Gostaria+De+Saber+Mais+Sobre+As+Consultas+Online">WhatsApp •  <i class=" fab fa-whatsapp" style="color: white"></i></a></li>
             
             <li><a href="mailto:vitorkw90@gmail.com">Gmail • <i class="fa fa-envelope"></i></a></li>
                          
             <li><a href="https://www.instagram.com/vitorkw89/">Instagram • <i class=" fab fa-instagram"></i></a></li>
              
            <li><a href="https://www.facebook.com/profile.php?id=100078322466753">Facebook • <i class="fab fa-facebook"></i></a></li>  
            
            <li><p>(Respondo em 
            <br>30 minutos <i class="fa fa-clock")></i>)</p></li>
            </ul>
            
          <!-- Carrocel imagens-->
          
          <div class="swiffy-slider">
          <ul class="slider-container">
              <li><img src="dog.jpg" style="height: 200px;
            width: 150px; border-radius:10px;margin: auto;
              margin-top: -30px;
              display: block;"></li>
              
              <li><img src="cobra.jpg"style="height: 200px;
            width: 150px; border-radius:10px;margin: auto;
              margin-top: -30px;
              display: block;"></li>
             
              <li><img  src="cav.jpg"style="height: 200px;
            width: 150px; border-radius:10px;margin: auto;
              margin-top: -30px;
              display: block;"></li>
              
              <li><img  src="âncora.jpg"style="height: 200px;
            width: 150px; border-radius:10px;margin: auto;
              margin-top: -30px;
              display: block;"></li>
              
              <li><img src="sol.jpg"style="height: 200px;
            width: 150px; border-radius:10px;margin: auto;
              margin-top: -30px;
              display: block;"></li>
              
              <li><img src="jardim.jpg"style="height: 200px;
            width: 150px; border-radius:10px;margin: auto;
              margin-top: -30px;
              display: block;"></li>
              
              <li><img src="navio.jpg"style="height: 200px;
            width: 150px; border-radius:10px;margin: auto;
              margin-top: -30px;
              display: block;"></li>
              
              <li><img  src="book.jpg"style="height: 200px;
            width: 150px; border-radius:10px;margin: auto;
              margin-top: -30px;
              display: block;"></li>
          </ul>

              <button type="button" class="slider-nav"></button>
              <button type="button" class="slider-nav slider-nav-next"></button>

          <div class="slider-indicators">
              <button class="active"></button>
              <button></button>
              <button></button>
          </div>
       </div>
          <br>
          <p>Acima algumas cartas do baralho Lenormand que uso inspirado por <a href="https://pt.m.wikipedia.org/wiki/Marie-Anne_Lenormand"><mark>Marie Anne Lenormand</mark></a> famosa oraculista de Napoleão Bonaparte. .</p>    
          </div>
          </div>
    
          <br> <br>
          <input type="checkbox" id="btn-c">
          <button id="btn-3">
          <label for= "btn-c" >
            <p><strong><i class="fa fa-search" aria-hidden="true"></i>Minha Opinião Sobre o tema</strong></p>
          </label>
          </button>
          <div class="hide">
            <div class="area">
              <p>
                A muito mistério quando se fala nesse assunto até por que são poucos que recorrem a alguma ajuda desse oráculo por motivos de preço e acessibilidade, além dos vários charlatões que existem hoje em dia principalmente na internet falando exatamente tudo que você quer ouvir pra te iludir. Tudo que eu estudo em relação a desenvolvimento pessoal eu levo o mais profundo a sério, procuro me ajudar e adquirindo experiência nisso também ajudar as pessoas, como todo estudo e dedicação levam tempo a certo valor a se cobrar por uma consulta seja online ou presencial, pensando nos valores absurdos que já vi penso em algo mais acessível para todos.
                  <br><br>
                  
                  Talvez uma pergunta sobre isso que todos pensam " isso envolve religião? É algo ruim ? " . Tarot são cartas que mostram situações que acontecem na vida de todos e fazendo a leitura pode se tomar ou não a melhor opção do que se pretende fazer . Muitos que se utilizam deste oráculo ( por sua preferência) misturam sua religião por vontade própria, eu particularmente prefiro não fazer e somente utilizar intuição e estudo aprofundado.
                  <br><br>
                  Também sendo uma ferramenta que pode ser usada para o bem tanto como mal é fundamental saber com quem você está se consultando e se é uma pessoa ética e confiável e que não vai lhe ocultar nada.
                  <br><br>
                   Abaixo explico as áreas na qual eu faço as leituras e preços.
                
              </p>
             </div>
          </div>
   
          <br><br>
          <input type="checkbox" id="btn-d">
          <button id="btn-4">
          <label for= "btn-d" >
            <p><strong><i class="fa fa-credit-card" aria-hidden="true"></i>Áreas & preço$ </strong></p>
          </label>
          </button>
          <div class="hide">
            <div class="area">
              <h1>Principais Áreas</h1>
              <ul>
                <li><a>Sentimental (Relacionamentos) • </a><i class="fa fa-heart" style="color:#fff"></i></li>
                
                <li><a>Financeira • $ </a></i></li>
                 
                <li><a>Estudos  • </a><i class="fa fa-book" style="color:#fff"></i></li>
                 
                <li><a>Amizades em geral & Parcerias  • </a><i class="fa fa-handshake" style="color:#fff"></i></li>
 
                <li><a>Familiar  • </a><i class="fa fa-users" style="color:#fff"></i></li>
              </ul>
              
              <p><mark>(Observação: não trabalho com qualquer assunto que envolva saúde)</mark></p>
              
              <h1> Custo & Acessibilidade</h1>
              <p>Em questão de preço acessível <mark>cada pergunta em qualquer área terá o preço de 10$</mark> já uma <mark>consulta completa de uma hora 60$.</mark></p>
              
              <h1>Atendimento Online x Presencial</h1>
              <p>Tanto um quanto o outro precisam ser em hora marcada. O atendimento online é feito por mensagem ou vídeo chamada dependendo da disponibilidade de cada um.</p>
              
              <p>Caso haja <mark>insatisfação da sua parte seu dinheiro é devolvido e você perde outras chances de se consultar futuramente.</mark></p>
             
             <h1> Metodos de Pagamento</h1>
             <p> • Pix & Boeloto Bancário </p>
             <br>
             <p><mark>(!A consulta só é feita após a formulação das perguntas e do pagamento!)</mark></p>
             
            <p><mark>Só trabalho com questões de serieade e que envolva assuntos pessoais e toda informação passada fica sobre sigilo ético. Não trabalho com áreas relacionadas a jogos e apostas até por que este oráculo não foi desenvolvimento pra isso.</mark></p>
            
            <p>Qualquer dúvida sobre o atendimento e outras coisas entre em contato na aba de (contatos)</p>
             </div>
          </div>
    </body>
</html>
