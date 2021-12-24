---
title: 'Introdução ao Html e Css'
date: '2021-12-24'
---

## HTML

Vamos esclarecer algumas coisas bem simples sobre o HTML, ele não é uma linguagem de programação, como seu próprio nome diz, é uma marcação de texto.

Hypertext Markup Language

Essas marcações do html são feitos através de tags como essas:

- <>

Algumas tags importantes para conhecer:

- `<!DOCTYPE html>` - Está passando a informação de que se trata de um documento html
- `<head></head>` - Esta tag manda as informações para o navegador, por exemplo o titulo da página, o idioma e linguagem daquela pagina
- `<body></body>` - Nesta tag é onde colocamos todas as informações de  que o usuário consegue ver, a pagina em si.

Não iremos abordar sobre cada tipo de tag html. 

Avançando no conteúdo, precisamos falar de uma coisa muito importante no HTML, a respeito de **DOM**. Que significa *Document Object Model.* 

Para ficar mais claro, é a árvore de conteúdos do html, formando um condeúdo geneólogico. Confira na imagem abaixo:

![ArvoreElementosHTML](https://th.bing.com/th/id/OIP.A_MhPH53kS-5CtObSz8naQHaFi?pid=ImgDet&rs=1)

Para fazermos a distinção de cada tag na hora de colocarmos estilos em alguns elementos, podemos categoriza-los em algumas formas:

- class

```html
<div class="NomeDaSuaClaase">
Conteúdo da DIV
</div>
```

- id

```html
<p id="texto">Frase de exemplo</p>
```

# Vamos falar sobre CSS agora

CSS que signifca Cascading Style Sheets, como o próprio nome diz, se trata de uma estilização em camadas.

Então por exemplo eu quero estilizar todas as tags `<a>` que estejam dentro de uma ‘class’ chamada principal, ficaria assim:

.principal a {

    Aqui coloco as estilizações que eu quero

}

Para referenciar classes no css, usamos '.' e o nome do elemento, que no exemplo acima ficou '.principal', ou seja, a classe principal.

No caso de referenciar id, é o mesmo passo, só que substituindo o '.' por '#'. Ficaria assim então '#principal'

Um conceito bem bacana é que o CSS é dividido por blocos, então dependendo do conteúdo, pode ocupar a linha inteira ou ter quebra de linha, por isso temos a divisão de conteúdos que são block e outros que são inline e ainda outro que são block-inline.

Segue a imagem abaixo para ficar mais claro:

![BlockVsInline](https://th.bing.com/th/id/OIP.guzXbEHRbQzQrY3BztW6VwHaHa?pid=ImgDet&rs=1)

## Block elements:

- p
- h1 - h6
- ol, ul
- pre
- address
- blockquote
- dl
- div
- fieldset
- form
- hr
- noscript
- table

## Inline elements

- b, big, i, small, tt
- abbr, acronym, cite, code, dfn, em,  kbd, strong, samp, var
- a, bdo, br, img, map, object, q, script, span, sub, sup
- button, input, label, select, textarea

## Modificando estruturas naturais dos elementos

Por exemplo se quisermos que um elemento que seja block se transforme em um elemento inline:

p {

display: inline;

}

Simples assim 👆🏻

## Alguns tipos de estilos

Podemos modificar diversos aspectos de estilos para deixar o site ou aplicativo mais bonito.

Segue alguns exemplos de estilização:

- border - Todos os elementos são considerados caixas no html, portanto eles tem bordas, essas bordas podem ser estilizadas com uma linha sólida ou tracejada por exemplo, com estilos de cores também.
- width - Aqui colocamos a largura do componente.
- height - Colocamos a altura do componente.
- display - Aqui colocamos estilo da forma que apresentamos o elemento na tela.
- color - Podemos modificar a cor do componente.
- background - podemos aplicar cores e modificações para o fundo do componente.
- margin - Margem do componente externo, podemos colocar espaçamento do componente em relação a outros componente aos lados ou acima.
- padding- Como todo elemento tem margim externa, o padding seria para colocar margin interna no componente, assim sendo aumentando seu conteúdo.

Este conteúdo foi uma breve introdução ao html e css.
Te vejo na próxima