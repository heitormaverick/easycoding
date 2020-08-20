---
title: Como criar e publicar um site do zero &num;2 - Programando o corpo do nosso site
---
Nesse post, vamos começar a programar nosso site.

O nosso site será feito no formato de blog, já que é um dos mais fáceis.

<!--more-->

- Para começarmos, abra o Visual Studio Code (caso não o tenha instalado, veja nosso [post #*](https://heitormvl.github.io/easycoding/blog/2020/08/07/como-criar-site-do-zero-pt*/) onde explico como configurar os programas que usaremos).

- Agora, clique em "Open Folder", escolha onde quer guardar os arquivos do seu site e crie uma pasta. Ela pode ter o nome que você quiser.

![01.png](https://heitormvl.github.io/easycoding/images/ccsz2/01.png)
![02.png](https://heitormvl.github.io/easycoding/images/ccsz2/02.png)

- Clique em abrir.

- Agora clique com o botão direito na área azul, e crie um novo arquivo chamado "index.html".

![03.png](https://heitormvl.github.io/easycoding/images/ccsz2/03.png)

- Agora vamos botar nosso conhecimento de HTML em prática. Caso algo que eu mostre aqui seja novo para você, veja nosso [post de introducão ao HTML](https://heitormvl.github.io/easycoding/blog/2020/08/05/introducao-ao-html/)

- Comecemos com as tags principais:
- Primeiro o `<html>`.
- Ao invés de escrever a tag inteira, tente escrever apenas `html`. Apareceu um pop-up com o html selecionado? Pressione **ENTER**.

![04.png](https://heitormvl.github.io/easycoding/images/ccsz2/04.png)
 
- Viu que ele finalizou a tag e ainda fez a tag de fechamento? Essa uma é ferramenta muito útil do VS Code.

![05.png](https://heitormvl.github.io/easycoding/images/ccsz2/05.png)

- Agora, coloque o cursor entre as tags `<html>` e `</html>` e pressione **ENTER**. Isso é muito importante para manter a hierarquia do nosso código organizada e mais fácil de entender.

![06.png](https://heitormvl.github.io/easycoding/images/ccsz2/06.png)

- Agora insira as tags `<head>` e `<body>` dentro do `<html>`. Para isso, basta escrever o nome da tag, selecioná-la com as teclas ⬆️ e ⬇️ e pressionar **ENTER**.
- Lembre-se de pressionar **ENTER** entre as tags para separá-las como na imagem:

![07.png](https://heitormvl.github.io/easycoding/images/ccsz2/07.png)

- Agora vamos adicionar um título ao nosso site (o nome que aparece na aba do navegador). Para isso, vamos usar a tag `<title>` dentro do `<head>`, mas como dessa vez só colocaremos uma linha de código, não é necessário quebrar as tags no meio. Veja o exemplo:

![08.png](https://heitormvl.github.io/easycoding/images/ccsz2/08.png)

- Agora vamos para o corpo do site.
- O corpo será dividido em três seções: o cabeçalho, a seção de conteúdo e o rodapé.
- Para criarmos essas **div**isões, vamos usar a tag `<div>` \*. E para diferenciarmos elas, vamos usar o atriuto `id` \*.

- Primeiro criamos os `<div>` dentro do `<body>` escrevendo seu nome e selecionando-o (lembre-se de quebrá-los no meio).

*\* A tag `<div>` e o atributo `id` serão explicados mais profundamente no post **Mais Sobre HTML** em breve.*

![09.png](https://heitormvl.github.io/easycoding/images/ccsz2/09.png)

- Agora dentro das tags de abertura `<div>` colocamos o atributo `id` e nele os nomes das seções:

![10.png](https://heitormvl.github.io/easycoding/images/ccsz2/10.png)

- Como o conteúdo dessa seções vai ter algumas coisas em comum, é interessante usar mais um conjunto de **DIVs** com a mesma classe.
- Dentro de cada seção, adicione um `<div>` com o atributo `class` nomeado como **container**.

![11.png](https://heitormvl.github.io/easycoding/images/ccsz2/11.png)

Pronto. Já temos o **"esqueleto"** do nosso site. No próximo post vamos elaborar o cabeçalho e o rodapé, então não percam.

Caso tenha restado alguma dúvida, não hesite em me contatar por email clicando na aba Contato no menu, ou <a href="mailto:heitor-easycoding@gmail.com">aqui</a>.

Fique de olho que quarta sai o próximo post.

Obrigado por ler até aqui, e até mais.