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

"<div>" coloca quebra de linha, já "<span>" continua na mesma linha o conteúdo.

"cloneNode", clona o nó, que são simplesmente as tags e seus condeúdos.
Já as tags dentro de tags são filhos.

indexOf, permite acessa dentro dos arrays:[].

Clicar em F12, permite acessar "A ferramenta do desenvolvedor".

sinal de igual: = , faz atribuição de valores;
dois iguais: == , faz comparação de valores sem considerar o tipo/classe que pertencem, ex: numeros e textos, se o valor for igual é o que importa;
três iguais: === , vai levar em conta se os valores e o tipo/classe são iguais; se os valores forem iguais, mas o tipo não, ele vai colocar como errado.

Onchange permite criar uma função; essa função é relaionada com alguma ação/evento que seja feita na tela.
*Por isso em Onchange, tem a palavra "On", que é ligado, porque ele "está atento/ligado", as interações que ocorrem na tela.

"New" serve para criar algo novo, uma estrutura de dados ou obj. específico chamado "Set".
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

<p> : coloca um parágrafo.

````css

  background-image: url(./assets/bg-mobile.jpg); /*o fundo é uma imagem*/ /*a img é do meu arquivo "assets", por isso, o uso do ponto (.) que quer dizer: " acesse dentro de"; e com "/bg-mobile.jpg" estamos pedindo para o ponto acessar exatamente essa img*/
  background-repeat: no-repeat; /*a img, é pequena, e por isso fica se repetindo na tela, com no-repeat, ela não repete*/
  background-position: top center; /*coloca a img no centro*/
  background-size: cover; /*size mexe com o tamanho; cover é "cobrir"/ ou seja, essa função faz a img cobrir todo o fundo*/

````

O "<ul>" = lista desordenada, e "<ol>" = lista ordenada; <ol> enumera os intens, já <ul> não os enumeras.
E "<li>" = faz a lista. 

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
