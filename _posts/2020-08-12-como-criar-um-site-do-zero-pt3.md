---
title: Como criar e publicar um site do zero &num;3 - Detalhando o cabeçalho e rodapé
---
Nesse post, vamos melhorar o cabeçalho e rodapé do nosso site.

<!--more-->

No [último post](https://heitormvl.github.io/easycoding/blog/2020/08/10/como-criar-um-site-do-zero-pt2/) da série CCPSZ nós criamos um modelo para o nosso site com cabeçalho, corpo e rodapé.

Hoje, vamos finalizar o cabeçalho e o rodapé.

## Cabeçalho

O cabeçalho terá um **título clicável** no lado esquerdo e uma **barra de navegação** com links às outras páginas no lado direito.

![01.png](https://heitormvl.github.io/easycoding/images/ccsz3/01.png)

### Título

Para o lado esquerdo, adicione um elemento `<a>` dentro do **container** dentro do **cabeçalho**, faça com que ele aponte para **"index.html"** e escreva **Meu Blog** (ou o que você quiser) dentro do elemento `<a>`.

![02.png](https://heitormvl.github.io/easycoding/images/ccsz3/02.png)

### Barra de Navegação

Para o lado direito, vamos fazer uma **lista não ordenada** `<ul>`* com links para as páginas Sobre e Contato. Depois vamos transformar essa lista em uma barra de navegação.

*\* A tag `<ul>` será explicada mais profundamente em breve.*

Dentro do container e abaixo do título, adicione um elemento `<ul>` e, dentro dele, adicione dois elementos `<li>`*.

*\* A tag `<li>` será explicada mais profundamente em breve.*

![03.png](https://heitormvl.github.io/easycoding/images/ccsz3/03.png)

Dentro dos elementos `<li>`, adicione links para **"sobre.html"** e **"contato.html"** e escreva **Sobre** e **Contato** entre eles.

![04.png](https://heitormvl.github.io/easycoding/images/ccsz3/04.png)

Vamos ver como nosso site está ficando?

### Extensão VSC - *Open in Default Browser*

Para podermos testar nosso site sem ter que publicá-lo, vamos usar uma extensão para o VSCode chamada *Open in Default Browser*.

Para instalá-la, clique no ícone de extensões no menu lateral do VSC.

![05.png](https://heitormvl.github.io/easycoding/images/ccsz3/05.png)

Agora pesquise **default browser** e clique em *install* na primeira opção.

![06.png](https://heitormvl.github.io/easycoding/images/ccsz3/06.png)

Agora pressione **CTRL** + **SHIFT** + **E** para voltar ao explorador de arquivos e feche a aba da extensão para voltarmos ao código.

### Testando

Certifique-se de salvar as alterações pressionando **CTRL** + **S**. A bolinha branca no nome do arquivo deve sumir:

![07.png](https://heitormvl.github.io/easycoding/images/ccsz3/07.png)

Agora pressione **CTRL** + **1**. Agora o VSC vai abri seu navegador para exibir o site (**Aviso:** o site ainda não está publicado. O que você está vendo é apenas um arquivo local.)

Seu site deve estar assim:

![08.png](https://heitormvl.github.io/easycoding/images/ccsz3/08.png)

Meio... simples né? Mas não se preocupe. Em breve vamos melhorar a aparência do site.

## Rodapé

O rodapé. Ele terá duas colunas: uma vai redirecionar para suas redes sociais, e outra vai exibir uma curta biografia.

![09.png](https://heitormvl.github.io/easycoding/images/ccsz3/09.png)

Dentro do **container** do **rodapé** crie dois elementos `<div>` e mude seus atributos `class` para **coluna**.

![10.png](https://heitormvl.github.io/easycoding/images/ccsz3/10.png)

### Links

Dentro da primeira coluna, adicione um elemento `<h4>` e faça ele dizer **Meus Links** (ou o que você quiser).

Abaixo dele, adicione um parágrafo que contenha um link, uma quebra de linha e outro link. Dentro dos **HREF** desses links, coloque o link de onde você quer que eles redirecionem e entre as tags **A** ponha o nome do site.

![11.png](https://heitormvl.github.io/easycoding/images/ccsz3/11.png)

### Biografia

Na segunda coluna, adicione um elemento `<h4>` que diz Minha História (ou o que você quiser) e um elemento `<p>` que contenha um biografia curtinha.

![12.png](https://heitormvl.github.io/easycoding/images/ccsz3/12.png)

Pronto terminamos o rodapé.

Salve o arquivo (novamente: **CTRL** + **S**) e execute o arquivo.

![13.png](https://heitormvl.github.io/easycoding/images/ccsz3/13.png)

Ainda está meio feio, mas como já disse, em breve vamos corrigir isso.

Por hoje acabamos. No próximo post vamos elaborar o conteúdo principal: os posts, então não percam.

Caso tenha restado alguma dúvida, não hesite em me contatar por email clicando na aba Contato no menu, ou <a href="mailto:easycoding.contato@gmail.com">aqui</a>.

Fique de olho que sexta sai o próximo post.

Obrigado por ler até aqui, e até mais.