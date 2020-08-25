---
title: Como criar e publicar um site do zero &num;4 - Detalhando o corpo do site
---

No [último post](https://heitormvl.github.io/easycoding/blog/2020/08/10/como-criar-um-site-do-zero-pt3/) da série CCPSZ nós terminamos o conteúdo do cabeçalho e do rodapé.

Nesse post, vamos definir o corpo do site e adicionar o primeiro post.

<!--more-->

A seção de contúdo vai ser composta por **posts de blog** (obviamente), e um post terá a foto e nome do autor, uma data, e algum texto.

Vamos adicionar o post!

## Criando o primeiro post

Dentro  do container da seção conteúdo, adicione um elemento `<div>` de classe `post`.

![1.png](https://heitormvl.github.io/easycoding/images/ccsz4/1.png)

Dentro do post, adicione um elemento `<div>` de classe `autor-post`. Vamos colocar os detalhes do autor aqui.

![2.png](https://heitormvl.github.io/easycoding/images/ccsz4/2.png)

Agora encontre ou faça uma foto quadrada de você e mova-a para a pasta onde está o código.

![3.png](https://heitormvl.github.io/easycoding/images/ccsz4/3.png)

Então adicione um elemento `<img>` dentro da seção de detalhes do autor e um atributo `<src>` que aponte para a imagem.

\* *Lembrete 1: elementos* `<img>` *não têm uma tag de fechamento*  
\* *Lembrete 2: ao definir o caminho de atributos como* `href` *e* `src` *o VSC lista os arquivos e pastas disponíveis automaticamente, de forma semelhante às tags e atributos, bastando apenas selecionar o arquivo desejado e pressionar **ENTER***

![4.png](https://heitormvl.github.io/easycoding/images/ccsz4/4.png)

Abaixo da imagem, adicione um elemento `<span>` que contenha seu nome.

![5.png](https://heitormvl.github.io/easycoding/images/ccsz4/5.png)

Então, abaixo de toda a seção de detalhes do autor, adicione um elemento `<p>` de classe `data-post` e, dentro dele, entre a data de hoje.

![6.png](https://heitormvl.github.io/easycoding/images/ccsz4/6.png)

Abaixo da data do post, adicione um elemento `<h3>` de classe `titulo-post` e, entre sua tag de abertura e fechamento, dê ao post um título.

![7.png](https://heitormvl.github.io/easycoding/images/ccsz4/7.png)

Finalmente, coloque um elemento `<div>` de classe `conteudo-post` abaixo do título e adicione dois parágrafos com texto dentro da seção.

![8.png](https://heitormvl.github.io/easycoding/images/ccsz4/8.png)

Pronto! A seção de conteúdo ganhou seu primeiro post.

Vamos ver como ficou? *(Salve o arquivo e **CTRL** + **1**)*

![9.png](https://heitormvl.github.io/easycoding/images/ccsz4/9.png)

De novo, logo logo (próximo post) vamos melhorar a aparência

## Página Sobre

Já que um site é uma coleção de páginas, nós ainda não temos um site.  
Vamos mudar isso adicionando uma **página Sobre** com informação sobre você.

Para a página Sobre, vamos usar o **index.html**, a página inicial, como template.

No explorador do VSC, selecione o **index.html**, pressione **CTRL** + **C** e **CTRL** + **V** para fazer um **index copy.html**.

![10.png](https://heitormvl.github.io/easycoding/images/ccsz4/10.png)

Agora selecione o **index copy.html**, pressione **F2** e renomeie-o para **sobre.html**.

![11.png](https://heitormvl.github.io/easycoding/images/ccsz4/11.png)

Na seção de post, remova os elementos `<span>` e `<p>`.

![12.png](https://heitormvl.github.io/easycoding/images/ccsz4/12.png)

Então mude o `<h3>` para `<h1>`, faça ele dizer **"Sobre Mim"**, e substitua o conteúdo do post com uma biografia mais detalhada.

![13.png](https://heitormvl.github.io/easycoding/images/ccsz4/13.png)

Finalmente, altere qualquer menção a `post` nos atributos `class` para `sobre`.  
Para isso, vamos utilizar a ferramenta **encontrar e substituir** (find and replace) do VSC. Basta pressionar **CTRL** + **F**.

Agora clique na setinha para expandir.

![14.png](https://heitormvl.github.io/easycoding/images/ccsz4/14.png)

Em **Find** escreva **post**, para que ele localize essa palavra (elas ficarão amareladas) e em **Replace** escreva **sobre**, para que ele saiba pelo quê deve substituir.  
Agora é so clicar no botão da direita **Replace All**.

![15.png](https://heitormvl.github.io/easycoding/images/ccsz4/15.png)