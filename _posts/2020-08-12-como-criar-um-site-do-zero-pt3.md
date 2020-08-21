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

