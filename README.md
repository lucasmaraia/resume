# resume

Meu currículo em formato de página web: resumo profissional, trajetória, formação acadêmica, competências e contato, em uma single page com navegação por âncoras.

> Projeto pessoal (agosto/2025). Serve tanto como currículo publicável quanto como exercício de layout com o framework Bulma.

## Stack

- HTML e CSS
- [Bulma](https://bulma.io) (classes `title`, `subtitle`, `section`, `navbar`)
- [Splide](https://splidejs.com) (carrossel de fotos)
- JavaScript puro para o menu mobile

## Estrutura

```
index.html    → todo o conteúdo, dividido em <section> com âncoras
js/script.js  → toggle do menu hambúrguer (navbar-burger) e setup do carrossel
images/       → fotos usadas no carrossel
```

As seções são `#inicio`, `#resumo-profissional`, `#trajetoria-profissional`, `#formacao-academica` e `#competencias`, todas alcançáveis pelo menu de navegação.

O carrossel (`#profile-carousel`) roda em loop, uma foto por vez, com autoplay a cada 5 segundos, sem setas e com paginação.

## Como rodar

Abra o `index.html` no navegador. Bulma e Splide são carregados de CDN, então é preciso estar conectado à internet para o layout e o carrossel funcionarem.

Para publicar, basta ativar o GitHub Pages nas configurações do repositório — é um site estático sem build.
