---
title: Mais sobre HTML &num;2 - Estilos e listas
---

No [último post](https://heitormvl.github.io/easycoding/blog/2020/08/11/mais-sobre-html-pt1/) da série de HTML nós vimos tags de links e mídia.

Nesse post, vamos conhecer as tags de estilização e de listas.

<!--more-->

Você está fazendo seu site e acha que já está na hora de deixas as coisas mais bonitas, certo?  
Nessa primeira parte vamos adicionar **CSS** dentro de algumas tags para mudar sua aparência.

## STYLE

Você lembra dos atributos? Eles são uma forma de prover informação adicional às tags.

Toda tag de HTML tem um atributo que podemos usar para mudar como se parece: `style`.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="BaKdzvj" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos STYLE">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/BaKdzvj">
    Exemplo de atributos STYLE</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

### BACKGROUND-COLOR

Agora tudo que precisamos fazer é adicionar um valor ao atributo `style`.

Que tal mudarmos a cor do background (plano de fundo) de toda a seção `<body>`?

Valores de `style` têm uma fórmula simples. Começamos com uma **propriedade**, como `background-color` (cor do plano de fundo).

Então nós adicionamos um dois pontos (`:`) seguido por como queremos alterar a propriedade. Nesse caso, vamos mudar a cor para `gray` (cinza).

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="KKzvMLq" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos STYLE 2">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/KKzvMLq">
    Exemplo de atributos STYLE 2</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

O atributo `style` usa CSS. É bom lembrar que declarações CSS requerem ponto-vírgula no final.

### COLOR

Vamos usar o atributo `style` com a tag `<p>` para mudar a cor do texto para vermelho.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="gOrxwwM" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos STYLE 3">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/gOrxwwM">
    Exemplo de atributos STYLE 3</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

### FONT-FAMILY

Por causa do ponto-vírgula podemos usar múltiplas declarações de código CSS.

Vamos mudar a fonte do nosso texto enquanto também mudamos a cor para vermelho.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="gOrxwWw" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos STYLE 4">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/gOrxwWw">
    Exemplo de atributos STYLE 4</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

### FONT-SIZE

Vamos tentar algo diferente. Dessa vez, vamos mudar o **tamanho da fonte** de um título com a propriedade `font-size` (tamanho da fonte) e valor `26px`.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="ExKvgvM" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos STYLE 5">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/ExKvgvM">
    Exemplo de atributos STYLE 5</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

`px` significa **pixels** e é um meio de medir o quão grande algo é na tela. Maior o número antes de `px`, maior ela é.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="KKzvgZR" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos STYLE 6">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/KKzvgZR">
    Exemplo de atributos STYLE 6</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

### TEXT-ALIGN

Algumas vezes precisamos que títulos ou parágrafos estejam centralizados. A boa notícia é que existe uma propriedade para isso: é chamada `text-align` (alinhamento do texto).

Para alinhar texto no meio, usamos a palavra `center` (centro) como valor.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="gOrxwjm" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos STYLE 7">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/gOrxwjm">
    Exemplo de atributos STYLE 7</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

### SPAN

Por enquanto mudamos o estilo de tags inteiras uma a uma. Entretanto, podemos dividir e estilizar diferentes **seções** de código HTML.

Se quisermos agrupar um **conjunto de palavras** por exemplo e mudar sua cor, podemos usar a tag `<span>`.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="vYGJyLZ" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos STYLE 8">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/vYGJyLZ">
    Exemplo de atributos STYLE 8</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

### DIV

Se quisermos agrupar tags inteiras juntas e mudar seu estilo, usamos a tag `div` para amarrá-las.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="xxVLRXE" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos STYLE 9">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/xxVLRXE">
    Exemplo de atributos STYLE 9</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

`<span>` e `<div>` são ótimos para usar CSS para estilizar sites. Vamos aprender mais sobre isso mais tarde quando usarmos ambos em diferentes arquivos.

## LISTAS

**Links** são ótimos em conectar sites um com o outro, mas eles também são ótimos em conectar páginas para formar um site.

Levar usuários por um site é chamado de **navegação**. Para criar um menu de navegação, vamos dar uma olhada nas **listas**.

Listas são um bom jeito de **organizar informação** e um dos elementos mais usados no HTML. Antes de adicionar qualquer link, vamos aprender o básico.

### LISTA ORDENADA

Tags de lista vêm em tipos diferentes tipos. Vamos começar com **listas ordenadas** (OL = Ordered Lists).

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="XWdaNyK" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tags OL">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/XWdaNyK">
    Exemplo de tags OL</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Acabamos de usar `<ol>` para criar uma lista, mas ainda está vazia. Para adicionar um **item de lista** (LI = List Item), vamos usar a tag `<li>`.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="NWNvbJV" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tags LI">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/NWNvbJV">
    Exemplo de tags LI</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

As letras ou números antes dos itens de lista são chamados de marcadores. Invés de números, também podemos usar letras como marcadores.

Para alterar o **tipo de marcador**, vamos usar o atributo `type` (tipo). Para letras maiúsculas em ordem alfabética, o valor que precisamos é `A`.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="YzqxNPj" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos TYPE">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/YzqxNPj">
    Exemplo de atributos TYPE</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Se quisermos **numerais romanos** como marcadores, usamos o tipo `I`.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="ExKvZPv" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tipo I">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/ExKvZPv">
    Exemplo de tipo I</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Se quisermos listar algo em ordem decrescente, apenas adicionamos o atributo `reversed` (revertido) à tag `<ol>` e voilá.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="XWdapjg" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tipo I revertido">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/XWdapjg">
    Exemplo de tipo I revertido</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

### LISTA DESORDENADA

Listas desordenadas podem soar meio caóticas, mas elas só são listas em tópicos. Para criar uma, vamos usar a tag `<ul>`.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="XWdappg" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tag UL">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/XWdappg">
    Exemplo de tag UL</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Também podemos fazer combinações de listas ordenadas e desordenadas.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="ZEWJLJK" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tag mista">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/ZEWJLJK">
    Exemplo de tag mista</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Agora podemos usar uma tag `<a>` para adicionar um link ao item.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="rNezjYz" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de LI com A">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/rNezjYz">
    Exemplo de LI com A</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Com isso, já podemos fazer uma navegação básica em HTML.

<p
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="wvGqgya" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de navegação">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/wvGqgya">
    Exemplo de navegação</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## Pronto!

Finalmente acabamos o curso básico de HTML. Mês que vem continuamos com o HTML intermediário.

Caso tenha restado alguma dúvida, não hesite em me contatar por email clicando na aba Contato no menu, ou <a href="mailto:easycoding.contato@gmail.com">aqui</a>.

Fique de olho que quarta continuamos com a série Como Criar e Publicar um site do zero.

Obrigado por ler até aqui, e até mais.