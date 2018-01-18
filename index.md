title: Beerjs #28
author:
  name: Leonardo Gatica
  twitter: lgaticaq
  url: https://about.me/lgatica
  email: lgatica@protonmail.com
output: index.html
theme: juanbrujo/cleaver-beerjs
style: style.css
controls: true

--

<h1>Como usar los Breakpoints en Chrome y Firefox</h1>

--

# ¿Por que usar breakpoints?

Los breakpoints nos permiten poder debugear el código de una forma mas dinámica y sencilla en vez de usar los `console.log()`.

--

# Chrome

--

## Breakpoint

<img src="img/chrome-loc-breakpoint.png">

--

## Breakpoint Condicional

<img src="img/chrome-conditional-loc-breakpoint.png">

--

## Administrar Breakpoints

<img src="img/chrome-breakpoints-pane.png">

--

## Breakpoint en el DOM

<img src="img/chrome-dom-change-breakpoint.png">

--

## Breakpoint en Eventos

<img src="img/chrome-event-listener-breakpoint.png">

--

## Breakpoint en Exceptions

<img src="img/chrome-uncaught-exception.png">

--


# Firefox

--

## Breakpoint Condicional

<img src="img/firefox-breakpoint-conditional.gif">

--

## Breakpoint en Exceptions

<img src="img/firefox-breakpoint-exception.gif">

--

# Extra Breakpoint en Node

Habilitar el debuger

```bash
node --inspect index.js
```

Habilitar el debuger con un breakpoint inicial

```bash
node --inspect-brk index.js
```

La extencion de chrome NIM permite abrir automáticamente una pestaña con el debuger al usar --inspect

--

<img src="img/node-inspect.png">
