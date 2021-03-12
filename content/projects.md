---
title: "Projetos"
date: "2019-05-18"
author: "Lucas Gouvêa"
---

## Grupo Tesseract

O grupo tesseract é uma organização da qual faço parte há alguns anos e participo ativamente, seja em projetos ou contribuindo pro conhecimento e crescimento interno da organização.
Temos um modelo de trabalho transparente, horizontal, orientado a melhorias contínuas e com o objetivo de tornar o desenvolvimento de software uma atividade mais humana.
Acesse grupotesseract.com.br para mais informações ou procure a gente no Github.

[<div class="image-container"><img src="/img/logo-tesseract-branco-simples.png"></div>](https://www.grupotesseract.com.br/)
      

## Trampos musicais da vida

Gosto muito de tocar guitarra. Mais do que eu deveria.

## Freelance

Quando sobra tempo consigo participar em trampos freelance pra sistemas ou sites mais básicos. Infelizmente, não tem sobrado tempo, mas qualquer coisa eu atualizo aqui, ou você sempre pode mandar um e-mail com uma proposta irrecusável :D

## Portfólio feito em React - Beatriz Montanhaur
[<div class="image-container"><img src="/img/beatrizdm.png"></div>](https://www.beatrizdm.com/)

## Site do projeto Múltiplos Olhares - Documentário sobre Esclerose Múltipla e Pandemia
[<div class="image-container"><img src="/img/multiplosolhares.png"></div>](https://www.projetomultiplosolhares.com/)

## Exemplos de código que vieram com o template e vou deixar aqui pois achei bonitinho e vai que alguém precisa um dia
```css
/* PostCSS code */

pre {
  background: #1a1a1d;
  padding: 20px;
  border-radius: 8px;
  font-size: 1rem;
  overflow: auto;

  @media (--phone) {
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  code {
    background: none;
    color: #ccc;
    padding: 0;
    font-size: inherit;
  }
}
```

```js
// JS code

const menuTrigger = document.querySelector('.menu-trigger')
const menu = document.querySelector('.menu')
const mobileQuery = getComputedStyle(document.body).getPropertyValue('--phoneWidth')
const isMobile = () => window.matchMedia(mobileQuery).matches
const isMobileMenu = () => {
  menuTrigger.classList.toggle('hidden', !isMobile())
  menu.classList.toggle('hidden', isMobile())
}

isMobileMenu()

menuTrigger.addEventListener('click', () => menu.classList.toggle('hidden'))

window.addEventListener('resize', isMobileMenu)
```

```html
<!-- HTML code -->

<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```

