---
title: HTML Básico &num;2 - Links e Mídia
---
Nesse post vamos ver mais sobre HTML como tags e atributos

<!--more-->

<iframe src="https://www.youtube.com/embed/s72D7UVPJF0" width="1100" height="465" frameborder="0" allowfullscreen></iframe>

Um arquivo .html, para ser mais preciso, é uma página da web. Sites são feitos de várias páginas, e é aí que entram os links, ou *hyperlinks*.

Eles conectam páginas entre si, ou um site com outro. Então, ao invés de termos que digitar cada url que queremos acessar, links nos levam diretamente com apenas um clique.

Vamos ver como criamos links.

## A

A tag de link é curta e simples: `<a>`.

Entre a tag de abertura e fechamento vai o texto que queremos que fique visível na página

<p 
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="KKzNzpW" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplos de tags A">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/KKzNzpW">
    Exemplos de tags A</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Fácil! O navegador vai mostrar qualquer coisa entre as tags de abertura e fechamento como um link

Para fazer o link funcionar, ainda precisamos adicionar um destino. Para isso, vamos usar algo conhecido como **atributo**.

### Atributo - HREF

Atributos adiciona informações às tags e vão *dentro* da tag de abertura.

Para adicionar um endereço ao link `<a>`, vamos usar o atributo `href`.

O atributo `href` ainda precisa de um valor. Para isso, vamos precisar adicionar um sinal de igual **=** e aspas **&quot;&quot;**

Agora dentro das aspas apenas adicionamos o endereço, também conhecido como Localizador Padrão de recursos, ou URL (Uniform Resource Locator) para simplificar.

<p 
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="wvGoGgz" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos HREF">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/wvGoGgz">
    Exemplo de atributos HREF</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Também podemos linkar arquivos locais. Isso só funciona se o destino está na mesma pasta da origem.

<p 
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="jOqVqmw" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos HREF 2">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/jOqVqmw">
    Exemplo de atributos HREF 2</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## IMG

Se quisermos adicionar **imagens** ao site, usamos a tag `<img>`.

Assim como a tag `<br>`, a **img** também é uma tag vazia, ou seja, não tem tag de fechamento.

<p 
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="OJNbNxX" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tags IMG">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/OJNbNxX">
    Exemplo de tags IMG</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Justamente por ser uma tag vazia, precisamos de um atributo para indicar a imagem...

### Atributo - SRC

Vamos usar o atributo `src`, que significa *source*, ou seja, *fonte*.

Assim como o **href**, podemos usar uma url ou um arquivo local:

<p  
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="QWNGNrq" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos SRC">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/QWNGNrq">
    Exemplo de atributos SRC</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

### Atributos - WIDTH e HEIGHT

Também podemos usar atributos que mudam o **tamanho** das imagens. Por exemplo, o atributo `width` muda a largura da imagem:

<p 
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="wvGoGEd" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos WIDTH">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/wvGoGEd">
    Exemplo de atributos WIDTH</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Se queremos mudar o quão alta uma imagem é, só precisamos adicionar o atributo `height` com um valor dentro das aspas:

<p 
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="VwamaqL" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de atributos HEIGHT">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/VwamaqL">
    Exemplo de atributos HEIGHT</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## IFRAME

Há outra tag muito útil que usamos para exibir uma página dentro de outra.

Fazemos isso com *quadros linear*, ou `<iframe>` (inline frame).

Um bom jeito de incluir vídeos em um site é usando o YouTube e a maneira mais fácil de conseguir isso é com um **iframe**.

Basta adicionar um url de um vídeo dentro do atributo `src`.

<p 
    class="codepen" data-height="265" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="poyNyXZ" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="poyNyXZ">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/poyNyXZ">
    poyNyXZ</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Chegamos ao fim desse post de HTML. Caso tenha restado alguma dúvida, não hesite em me contatar por email clicando na aba Contato no menu, ou <a href="mailto:easycoding.contato@gmail.com">aqui</a>.

Amanhã sai o próximo post da série _Como criar e publicar seu site do zero_.

Obrigado por ler até aqui, e até mais.