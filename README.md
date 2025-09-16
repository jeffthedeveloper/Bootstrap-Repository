# Bootstrap Repository (Projetos TinDog e Mondrian)

Este repositório contém dois projetos de front-end distintos que demonstram o uso de HTML, CSS moderno e o framework Bootstrap.

1.  **TinDog:** Uma landing page responsiva e completa para um aplicativo fictício (um "Tinder para cachorros"), construída com **Bootstrap 5**.
2.  **Mondrian Project:** Um exercício de arte visual que recria uma pintura no estilo de Piet Mondrian usando **CSS Grid Layout**.

## 1\. Projeto TinDog

Este projeto é uma landing page de produto completa que utiliza vários componentes do Bootstrap 5 para criar um layout responsivo e atraente.

### Funcionalidades (TinDog)

  * **Layout Responsivo:** O site se adapta a telas de desktop e dispositivos móveis.
  * **Componentes Bootstrap:** Utiliza componentes como Herói (Title), Colunas de Features, Depoimentos (Testimonial), Cards de Preço (Pricing) e Footer.
  * **Estilização Personalizada:** Inclui CSS personalizado (`solution.css`) para adicionar fundos animados em gradiente (`.gradient-background`) e formatar imagens (`.profile-img`).
  * **Assets:** Inclui todos os assets necessários, como a imagem do iPhone com o app, a foto do cachorro para depoimento e logotipos de parceiros (TechCrunch, Mashable, etc.).

## 2\. Projeto Mondrian (CSS Grid)

Este projeto é um exercício de CSS puro focado em recriar uma pintura abstrata de Piet Mondrian. O objetivo é praticar o **CSS Grid Layout**.

### Funcionalidades (Mondrian)

  * **CSS Grid:** O layout é construído inteiramente com `display: grid`.
  * **Estrutura de Grid:** Utiliza `grid-template-columns`, `grid-template-rows`, `gap`, `grid-column (span)`, `grid-row (span)` e `grid-area` para posicionar com precisão os blocos coloridos.
  * **Imagens de Referência:** O repositório inclui as imagens `goal.png` e `dimensions.png` que serviram como guia para o desenvolvimento do layout.

## Estrutura do Repositório

```
/
│
├── tin-dog-project-index.html  # Projeto 1: Landing Page (Bootstrap)
├── index.html                  # Projeto 2: Pintura Mondrian (CSS Grid)
├── Mondrian-index.html         # (Duplicata do index.html)
│
├── solution.css                # CSS para o TinDog
├── blank-template.css          # (Template CSS para o TinDog)
│
├── images/                     # Assets para o TinDog
│   ├── iphone.png
│   ├── dog-img.jpg
│   ├── techcrunch.png
│   ├── mashable.png
│   ├── bizinsider.png
│   └── tnw.png
│
├── goal.png                    # Imagem-objetivo do Mondrian
├── dimensions.png              # Imagem de dimensões do Mondrian
│
└── README.md                   # O README original do TinDog
```

## Como Usar

Ambos são projetos estáticos (HTML/CSS) e podem ser abertos diretamente em qualquer navegador web.

1.  **Para ver o projeto TinDog:**

      * Abra o arquivo `tin-dog-project-index.html` no seu navegador.

2.  **Para ver o projeto Mondrian:**

      * Abra o arquivo `index.html` (ou `Mondrian-index.html`) no seu navegador.
