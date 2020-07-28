+++
author = "Unidade para resistir!"
title = "Um post de exemplo para Centro Acadêmico"
date = "2020-03-11"
description = "Aqui é a descrição do post."
tags = [ "layoutcacs", "teste", "unidade para resistir", ]
categories = [ "testes", "gestao", ]
aliases = ["migrate-from-jekyl"]
images  = ["img/2014/04/pic01.png", "globais/logo_cacs.jpg"]
+++

Texto de prévia do post.
<!--more-->

## Título 2

O markdown usa estrutura de títulos de # como título mais elevado para ###### como título menos elevado. O visual da pra editar fácil.

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Testando alguns recursos pra mostrar

### Inserção de imagens no post
Parágrafo
{{<figure src="/img/globais/logo_cacs.jpg" alt="Esse é o logo do CACS para leitura em dispositivos de acessibilidade">}}

### Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

#### Blockquote sem atribuição

> Testando pra mostrar.
> **Negrito** funciona, *itálico* também, ou seja, dá pra formatar com markdown tranquilo.

#### Blockquote com atribuição

> Aqui vai ficar uma primeira linha e vou atribuir uma quebra de parágrafo.</p>
> — <cite>Outra linha com citação e nota de rodapé[^1]</cite>


[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## Tables

Tables aren't part of the core Markdown spec, but Hugo supports supports them out-of-the-box.

   Name | Age
--------|------
    Bob | 27
  Alice | 23

#### Inline Markdown within tables

| Inline&nbsp;&nbsp;&nbsp;     | Markdown&nbsp;&nbsp;&nbsp;  | In&nbsp;&nbsp;&nbsp;                | Table      |
| ---------- | --------- | ----------------- | ---------- |
| *italics*  | **bold**  | ~~strikethrough~~&nbsp;&nbsp;&nbsp; | `code`     |

## Code Blocks

#### Code block with backticks

```
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```
#### Code block indented with four spaces

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

#### Code block with Hugo's internal highlight shortcode
{{< highlight html >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

## List Types

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

* List item
* Another item
* And another item

#### Nested list

* Item
1. First Sub-item
2. Second Sub-item

## Other Elements — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
