# 🎭 Página Cultural

Este projeto é uma **página cultural interativa** desenvolvida com o objetivo de praticar os conceitos de **CSS Flexbox** e **CSS Grid Layout**, aplicados em diferentes seções da página para garantir uma estrutura responsiva e bem organizada.

## ✨ Tecnologias Utilizadas

- HTML
- CSS
  - Flexbox
  - Grid Layout
  - Media Queries

## 🧩 Funcionalidades e Estrutura

A página é composta por diferentes seções estilizadas com Flexbox e Grid para treinar a responsividade e organização dos elementos. 

### 🧱 Flexbox

A Flexbox foi utilizada principalmente nas seguintes seções:

- **Cabeçalho (`.menu`)**: layout flexível com espaçamento entre os itens e ajuste responsivo com `flex-wrap` e `column-gap`.
- **Categorias e Destaques**: organizadas em colunas e linhas com `row-gap`, `flex-direction`, e `align-items`.
- **Eventos e Agenda**: listas de itens que se adaptam ao tamanho da tela com `flex-grow`, `wrap` e alinhamento central.
- **Rodapé**: elementos alinhados com `justify-content: space-between`.

### 🗂️ Grid Layout

O Grid foi aplicado nas seguintes seções para maior controle das posições:

- **Banner (`.banner`)**: layout de imagens com colunas e linhas organizadas por `grid-column` e `grid-row`.
- **Eventos (`.eventos__item`)**: estrutura interna com `grid-template-areas` para posicionar imagens, títulos e botões.
- **Agenda (`.agenda__item`)**: uso de `grid-template-columns` e `grid-template-rows` para definir a estrutura responsiva dos cards de eventos.
- **Categorias (em telas grandes)**: estrutura em grade com destaque visual para título, lista, imagem e destaques.

## 📱 Responsividade

A responsividade é garantida com o uso de media queries:

- **≥ 720px**: ajustes no `gap`, disposição das listas e realocação dos elementos para melhor aproveitamento da tela.
- **≥ 1440px**: estrutura das seções principais convertidas para Grid, alterando a ordem dos elementos no menu e melhorando a hierarquia visual da página.


## 🚀 Aprendizados

Este projeto foi essencial para compreender na prática:

- Como usar Flexbox para criar layouts adaptáveis e distribuídos igualmente.
- Como aplicar Grid Layout para montar estruturas mais complexas com controle total das posições.
- Como combinar Flexbox + Grid em um mesmo projeto para resultados mais ricos.
- Como adaptar os estilos com `media queries` para diferentes tamanhos de tela.
