
<div align = "center">
  <img alt="Memory Gmae" src="https://user-images.githubusercontent.com/90014122/188282340-581786e4-b596-4e8a-a07a-5bdd357cdd03.png">
  <br>
  A temática do jogo foi inspirada no filme Eternal Sunshine of the Spotless Mind. 
</div>

<h1>Objetivo</h1>
<p>Criar um jogo da memoria usando a linguagem de programação JavaScripit</p>
<p>O jogo da memória é um clássico jogo formado por peças que apresentam uma figura em um dos lados. Cada figura se repete em duas peças diferentes. Para começar o jogo, as peças são postas com as figuras voltadas para baixo, para que não possam ser vistas</p>

<h1>Descrição</h1>
<h3>Página Inical</h3>
<ul>
<li> Inicia-se com uma tela de login para o usuário. É necessário que o usuário digite pelo menos três letras para realizar o acesso ao jogo.</li>(A função que realiza essa validação é:  validateInput)
</ul>
<h3>Página do Jogo</h3>
<ul>
<li> Existe uma função para contar o tempo de jogo. Nome da Função: startTimer</li>
<li>Uma função que resgata o nome do usuário que foi guardado dentro do Armazenamento Local do navegador que fornece métodos para armazenar e recuperar a informação.(Nome da Função: onload.) </li>
</ul>
<p>O primeiro passo é realizar a criação da carta utilizando Java Script. A função createElement facilita na criação recebendo os parâmetros tag e nome da classe, após essa função ser realizada as cartas que estão dentro de um array são duplicadas e depois são embaralhadas de forma aleatória. Nesse momento, é realizado uma verificação das cartas que foram inicializadas anteriormente com um valor vazio.</p>

<p>Caso o valor da primeira e da segunda carta ainda seja vazio então esse valor é preenchido e as cartas são reveladas para o jogador. Em seguida, chama-se a função checkCards para saber se os valores são iguais.</p>

<p>Quando é confirmado que os valores são iguais às imagens ficam em preto e branco, se não, é chamado a função setTimeout que revela e esvazia os valores das cartas esperando um período de 500ms. Para finalizar o jogo é chamada a função checkEndGame que verifica se todas as 20 cartas estão com a classe disabled-card ativa. </p>

<p></p>

<h2></h2>

<h3>Tecnologias utilizadas</h3>

[site no Git Pages](https://kathleenfs.github.io/Jogo-da-memoria-com-JavaScript/)
<div style="display: inline_block"><br>
   <img align="center" alt="kath-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="kath-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="kath-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
 </div>
