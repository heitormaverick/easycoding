---
title: Introdução ao HTML
author: Heitor Maciel
---

HTML é a lingugem de programção usada na maioria dos sites.

Para programar em HTML, primeiro é necessário conhecer algumas das funções que o compoem. Vamos ver o que cada uma faz.

<!--more-->

<iframe width="1000" height="422" src="https://www.youtube.com/embed/5kla4KkvCuM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## HTML

Tudo começa com a tag `<html>`. Como qualquer tag, ela é composta por um `<`, o nome dela: `html` e o `>`.

A tag `<html>`, assim como muitas tags, vem em pares, sendo a `<html>` uma tag de abertura e a `</html>` uma tag de fechamento.

_Nota: tags de fechamento sempre têm uma `/` entre o `<` e o nome._

Por último, a tag `<html>` usualmente será a primeira tag do seu código, e a de fechamento, a última. Veja o exemplo a seguir:

<p  
    class="codepen" data-height="189" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="eYJMXqM" style="height: 189px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="eYJMXqM">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/eYJMXqM">
    eYJMXqM</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## BODY

Como pode ter visto na imagem anterior, a segunda tag mais importante de um HTML é a `<body>`, que como o nome já diz, compõe o corpo do HTML, ou seja, é onde todo o conteúdo do site vai ficar.

Assim como o `<html>`, o `<body>` precisa de uma tag de fechamento `</body>` 

## HEADINGS

Os **headings**, ou cabeçalhos/títulos, são tags que alteram a aparência do texto contido nelas. Veja o exemplo a seguir:

<p  
    class="codepen" data-height="319" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="ZEQxZbo" style="height: 319px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tags heading">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/ZEQxZbo">
    Exemplo de tags heading</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Você percebeu os números nas tags `<h->`? Quanto menor o número, maior o texto, e vice-versa.

E assim como as tags anterioresa, as `<h->` também precisam da tag de fechamento correspondente.

## P

Podemos separar linhas em parágrafos usando as tags `<p>` e `</p>`

Elas podem ser muito úteis para separar diferentes linhas de texto no conteúdo. Veja o exemplo:

<p 
    class="codepen" data-height="385" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="VweXNPY" style="height: 385px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tags P">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/VweXNPY">
    Exemplo de tags P</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>


Você deve ter percebido que as duas primeiras linhas "Texto sem a tag P" e "Texto sem a tag P, segunda linha" ficaram juntas, mesmo pressionando ENTER, diferente da terceira e quarta linha, que ficaram separadas.

Isso aconteceu porque o HTML não sabe diferenciar um ENTER de um espaço " " normal, por isso usamos as tags `<p>` e `</p>`

Notou que há um espaço entre cada linha em que usamos o `<p>` no exemplo? Quer saber como evitá-lo? Veja a próxima tag:

## BR

Para apenas quebrarmos a linha, ao invés de criar um novo parágrafo, usamos a tag `<br>`. Veja o exemplo:

<p  
    class="codepen" data-height="324" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="YzwaMVX" style="height: 324px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tags BR">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/YzwaMVX">
    Exemplo de tags BR</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Se você prestou atenção, além de agora o texto do exemplo onde o `<br>` foi usado não ter mais espaço depois da quebra de linha, algo no código está diferente.

Achou?

Se sim, parabéns, você já está treinando seus olhos de programador. Se não, a resposta era a própria tag `<br>`, que ao contrário de todas as tags que vimos até agora não precisa da sua tag de fechamento correspondente.

Isso é o que chamamos de _tag vazia_. Tags vazias não possuem conteúdo, mas ainda assim são importantes para estruturar uma página. E caso queira pular linhas dentro de um parágrafo, é só usar mais de uma tag `<br>` uma embaixo da outra.

## EM e STRONG

Outras funções muito importantes para melhorar a aparência do nosso texto são o `<em>` e `<strong>`.

A tag `<em>` dá _ênfase_ ao texto (mais especificamente usando o itálico).

Já a `<strong>` deixa o texto **forte** (usando o negrito).

Veja o exemplo delas em ação:

<p
    class="codepen" data-height="328" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="jOWzRaz" style="height: 328px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tags EM e STRONG">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/jOWzRaz">
    Exemplo de tags EM e STRONG</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Lembrando que essas tags requerem as tags de fechamento correspondentes como visto acima.

## HEAD

Já vimos muitas tags que aparecem no site em si, mas tem uma tag que não aparece NO site. É a tag `<head>`.

Ela vem depois da tag de abertura `<html>` e antes da tag de abertura `<body>` e tem uma tag de fechamento também.

Na tag `<head>` são inseridas informações como o título do site ou como estilizar a página (por enquanto).

## TITLE

Para darmos um título ao nosso site (aquele texto que aparece na aba onde o site está aberto, por exemplo "EasyCoding - Mat. de HTML" nessa página), usamos a tag `<title>`.

Colocamos a tag dentro do par de tags **HEAD** junto com sua tag de fechamento correspondente, e dentro destas, o título desejado. Veja o exemplo:

<p 
    class="codepen" data-height="243" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="MWKVddK" style="height: 243px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tags TITLE">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/MWKVddK">
    Exemplo de tags TITLE</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## DOCTYPE

Por último e menos importante (mas não podemos deixar de falar), a tag `<!DOCTYPE html>`. Ela serve para dizer ao navegador em qual versão de HTML o site foi feito, no caso, HTML 5. Essa é a versão mais recente e utilizada em praticamente qualquer site existente hoje em dia.

Ela já foi obrigatória na fase de transição entre o HTML 4 e o HTML 5, mas hoje em dia, todo navegador já usa o HTML 5 como padrão, tornando essa tag desnecessária.

Com isso, você pode escolher entre pôr ou não. Caso queira ter 100% de certeza de que seu site será entendido por qualquer navegador, ponha, mas fique tranquilo que caso não ponha, as chances de alguém usar um navegador que não suporte é mínima, visto que até o finado Internet Explorer suporta.

<p
    class="codepen" data-height="207" data-theme-id="dark" data-default-tab="html,result" data-user="heitormaverick" data-slug-hash="eYJMweE" style="height: 207px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Exemplo de tags DOCTYPE">
    <span>See the Pen <a href="https://codepen.io/heitormaverick/pen/eYJMweE">
    Exemplo de tags DOCTYPE</a> by heitormaverick (<a href="https://codepen.io/heitormaverick">@heitormaverick</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

Chegamos ao fim desse post de introdução a HTML. Caso tenha restado alguma dúvida, não hesite em me contatar por email clicando na aba Contato no menu, ou <a href="mailto:heitor-easycoding@gmail.com">aqui</a>.

Em breve sai o primeiro post da série _Como criar e publicar seu site do zero_.

Obrigado por ler até aqui, e até mais.
