# Anotações

HTML: mexe com o texto, e sua estrutura.
CSS: mexe com o designer, como a cor de fundo.
JAVA SCRIPT: mexe com a funcionalidade da página.


```js

const mensagem = "Bom ver você aqui! "
alert (mensagem + (10 * 100) + " abraços")
// bom ver você aqui! 1000 abraços

```

As letras e números dentro do símblo: < >, são chamadas de Tags, e permite colocar atríbutos/características ao texto.
EX: <div> faz quebra de linha.

Arrays são representados por conchetes: []

TEMPLATE: diz para o computados para o texto não aparecer na tela, no momoento certo, eu Dev, vou usar esse texto.

DIV coloca quebra de linha, já SPAN continua na mesma linha o conteúdo.

CLONENODE, clona o nó, que são simplesmente as tags e seus condeúdos.
Já as tags dentro de tags são filhos.

indexOf, permite acessa dentro dos arrays:[].

Clicar em F12, permite acessar "A ferramenta do desenvolvedor".

sinal de igual: = , faz atribuição de valores;
dois iguais: == , faz comparação de valores sem considerar o tipo/classe que pertencem, ex: numeros e textos, se o valor for igual é o que importa;
três iguais: === , vai levar em conta se os valores e o tipo/classe são iguais; se os valores forem iguais, mas o tipo não, ele vai colocar como errado.

ONCHANGE permite criar uma função; essa função é relaionada com alguma ação/evento que seja feita na tela.
*Por isso em Onchange, tem a palavra "On", que é ligado, porque ele "está atento/ligado", as interações que ocorrem na tela.

NEW serve para criar algo novo, uma estrutura de dados ou obj. específico chamado SET.
*Set armazena uma única informação de algo.

```css

  <img src="https://gist.githubusercontent.com/maykbrito/f47569e32fb2b21f2ecc9f4c035c141f/raw/a45997404564112d7596fbb1b9cad5de5521927e/logo.svg" alt="Logo do NlW">
/*para colocar uma imagem: "IMG", e depois "SRC", que é para colocar o link; e "ALT", serve para dizer ao css o que ele deve deixar escrito caso não acha a imagem.

```
```css

  font-family: 'Poppins', sans-serif; /*ativa uma fonte e suas características ao quiz, por meio do  nome escrito; poppins; + o Url/link escrito no topo da página css*/
  /*sans-serif quer dizer que se a fonte poppins não for achada, deverá colocar a fonte "sans-serif"*/

```
*programação é ensinar o computador. É igual a línguas humanas, existe linguagens específicas de programação e sintaxes específicas, além de ter que usar lógica de progamação, que é pensar de acordo com linguagem que você está usando para programar, para o algorítimo ser lógico.

*código é informação com o intuito de fazer uma comunição ou passar uma instrução.

*Lembrar que o HTML é uma caixa. Cada conteúdo é uma caixa dentro de outra.

*As funções no JavaScript são um bloco de código que executa um código; por isso o nome "função", pois faz algo funciona; e que pode ser chamado em outras partes do programa e reaproveitar o código. 

````css

body
{
  background: color: red;

  background: color: blue;
}
/*a cor de fundo será azul, porque o css, escolhe sempre a última opção*/
````

````html

<a href="https://rocketseat.com.br"> Ver site </a>
<!--como colocar link-->

````

P : coloca um parágrafo.

````css

  background-image: url(./assets/bg-mobile.jpg); /*o fundo é uma imagem*/ /*a img é do meu arquivo "assets", por isso, o uso do ponto (.) que quer dizer: " acesse dentro de"; e com "/bg-mobile.jpg" estamos pedindo para o ponto acessar exatamente essa img*/
  background-repeat: no-repeat; /*a img, é pequena, e por isso fica se repetindo na tela, com no-repeat, ela não repete*/
  background-position: top center; /*coloca a img no centro*/
  background-size: cover; /*size mexe com o tamanho; cover é "cobrir"/ ou seja, essa função faz a img cobrir todo o fundo*/

````

UL = lista desordenada, e OL = lista ordenada; OL enumera os intens, já UL não os enumeras.
Li = lista
```html
<ul> <ol>

<ul>
    <li> <li>
</ul>
```

QUAL A DIFERENÇA EM USAR "FLEX-DIRECTION:ROW" e "FLEX-DIRECTION:COLUMN"?
A propriedade CSS "flex-direction: row" define que os itens dentro de um container flex devem ser posicionados em uma linha horizontal, enquanto "flex-direction: column" define que os itens devem ser posicionados em uma coluna vertical.


```` html
<li> <!-- o hashtag quer dizer que o link não vai para nenhuma página-->
      <a href="#"> Inscrever-se no NLW </a>
</li>
<li>
     <a href="https://github.com/brezona?tab=repositories" target="_blank"> Ver meu portfólio </a>
</li> <!--target blanck quer dizer que: "o link deve abrir na mesma página/o outro site deve abrir nessa tela"-->
````


```css
body {
  /*tira todas as medidas de margem e borda pré-definidas pelo computador*/
  margin: 0;
  padding: 0;
}

/*variáveis*/
:root {
  --texto: white;
  --fundo: url(./assets/bg-mobile.jpg);
  --bordaLI: rgb(255, 255, 255, 0.5);
  --fundoLI: rgb(255, 255, 255, 0.1);
  --funfoLI-hover: rgb(255, 255, 255, 0.05);
  --linkssociaishouver: rgb(255, 255, 255, 0.2);
  --botão: url(./assets/lua-estrelas.svg);
}
.branco {
  --texto: black;
  --fundo: url(./assets/bg-mobile-light.jpg);
  --bordaLI: rgb(0, 0, 0, 0.5);
  --fundoLI: rgb(0, 0, 0, 0.05);
  --funfoLI-hover: rgb(0, 0, 0, 0.02);
  --linkssociaishouver: rgb(0, 0, 0, 0.1);
  --botão: url(./assets/sol.svg);
}

body {
  background: var(--fundo) no-repeat top center/cover;
  /*esse tipo de propriedade é chamada de "atalho" ou "short-hand"*/
  /* "var" é variável; veja que em :root e em .branco foram criadas variáveis*/
  
  height: 100vh;/*100% da viewport height; vai cobrir 100% da altura da viewport=tela*/
}

#conteudo {
  width: 100%; /*o conteúdo vai cobrir a largura máxima da tela, até o lime máximo abaixo, de 588 pixels*/
  max-width: 588px;

  margin: 56px auto; /*coloca 56px de espaçamento no topo e "auto"maticamente ele faz um calculo e faz as margens laterais na mesma medida/distancia*/
  padding: 0 24px; /*24 pixels são dos preenchimentos laterais*/
}

#perfil img {
  display: block; /*display em inglês é mostrar*/
  /*faz a img; que é um obj inline(em linha); ser block (quadrado); e por isso, pode ser centralizado com "auto"*/
}

#botão {
  position: relative; /*esse position relativisa outros position; como o do botton abaixo; assim o "absolute" de position abaixo, só funcionará dentro da área do width de 66px*/
  width: 66px;
}

#botão button {
  background: white var(--botão) no-repeat /*não repita a imagem*/ center /*posicione ela no centro*/;
  
  position: absolute; /*position:absolute, sobrepõem o elemento sobre outros*/
  z-index: 1; /*com z-index, o elemento é colocado na camada 1*/
  left: 0; /*coloca o button na posição 0 do lado esquerdo; totalmente no canto do lado esquerdo da área do botão que foi estabelecida acima*/

  /*um truque matemático: o botão não está alinhado a barrinha (span), então top: 50%, obriga ele a ficar esse tanto porcento acima da barra, e com "tranform..." o obrigamos a descer essa quantidade, assim alinhando o botton à barrinha*/
  top: 50%;
  transform: translateY(-50%);

  animation: deslizamentoVolta 0.4s; /*a animação do keiframe será de 4 seg.*/
}

.branco #botão button {
  animation: deslizamento 0.4s forwards; /*a animação do keiframe será de 4 seg*/ /*forwards diz para o css manter as propriedades, assim o botão não fica voltando*/
}

#botão button:hover { /*hover é a função que o seu conteúdo só funcina quando passa o mouse por cima do elemento*/
  outline: 8px solid var(--fundoLI); /*uma borda aparecerá em volta do botão*/
}

#botão span {
  display: block; /*span é uma tag inline (linha), por isso é tornada em block para aceitar a altura e largura*/

  backdrop-filter: blur(4px); /*bLur é "embaçar"*/
  -webkit-backdrop-filter: blur(4px); /*o "-webkit..." serve para ativar/permitir o backdrop-filter em alguns aparelhos*/
}

ul {
  list-style: none; /*tira as características da lista, omo pontos e números*/
  gap: 16px; /*gap é o "espaçamento entre" as listas*/
}

ul li a {
  text-decoration: none; /*o "none" tira a decoração do texto*/
  font-weight: 500; /*a fonte é 500*/
}

@media (min-width: 700px) { /*quando a largura mínima for de 700px, a variável fundo vai alterar para os novos fundos abaixo*/
  :root {
    --fundo: url(./assets/bg-desktop.jpg);
  }
  .branco {
   --fundo: url(./assets/bg-desktop-light.jpg);
  }
}

@keyframes deslizamento { /*keiframes colocas animações*/
  /*abaixo vemos animações para o botão, assim ele poderá deslizar suaviamente de uma ponta a outra*/
  from {
    left: 0;   
  }
  to {
    left: 52%;
  }
}
```

tags para formulários
```html
<label for="titulo"> Titulo do Input </label> <!-- for, é "para", assim, elee referencia o input que a Laber se refere, baseado no ID-->
    <input type="text" name="titulo" id="titulo">

    <select name="selecao" id="selecao">
        <option value="filme"> Filme </option>
        <option value="musica"> Música </option>
    </select>

    <textarea name="escreva" id="escreva" cols="30" rows="10"></textarea>
```
