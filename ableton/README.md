# [Ableton](https://www.frontendpractice.com/projects/ableton)

![](https://www.frontendpractice.com/_next/image?url=%2Ffullsize%2FC1-Ableton.jpg&w=3840&q=90)

Ideia: estabelecer um processo para o desenvolvimento desses projetos.

Baseado no que estou aprendendo em Data Science acho uma boa tornarmos isso em ciência.

E o primeiro passo de tudo é definir o problema que temos que resolver.

## 🎯 Objetivo

> Recriar página About

Requisitos:

- Deve ser responsivo
- Os menus devem funcionar, apenas os links não levarem para lugar nenhum
  - O primeiro muda ao ficar responsivo
  - O segundo fica sticky apenas ao scrollar para cima (voltando)

## Plano

- [x] Definir assets
  - [x] Tipografia 🔨
  - [x] Imagens
  - [x] Paleta de cores
- [x] Definir tech stack
  - [x] Tailwind, com npx
  - [x] HTML
- [x] Carregar assets
  - [x] Tailwind
  - [x] Favicons
  - [x] Fontes
  - [x] Cores do tema
  - [x] Background
- [x] Desenvolver
  - [x] Menu superior
  - [x] Menu inferior
  - [x] Menu more
  - [x] Menu responsivo
  - [x] Hero
  - [x] Body sections
  - [x] Footer
  - [x] select highlight texto fundo azul
  - [x] Converter imagens para webp

## Lições aprendidas

React é muito melhor que usar só html e js, a abordagem declarativa do React reduz muito a complexidade e a repetição de código. Com js puro precisamos ficar pegando cada elemento em específico e adicionando removendo classes / styles para aplicar interações.

Tailwind também é complexo de configurar sem um vite da vida.

A estratégia de usar a unidade vw para tornar imagens e textos responsivos sem o uso de media-queries foi muito interessante.

Para os próximos: lembrar que é melhor nomes de imagens declarativos do que nomes sequenciais que não dizem do que a imagem se trata.

Box-icons com web components, não achei legal. Bem limitado. Era melhor o famoso font awesome com seus ícones roots.
