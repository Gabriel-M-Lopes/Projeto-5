# Resumo do Projeto 05 - Animações CSS

Este projeto foi desenvolvido com o objetivo principal de praticar e aprender animações utilizando CSS.

## O que foi feito

- Estruturei uma página com cards de trabalhos recentes usando HTML semântico.
- Implementei animações CSS para dar vida à interface:
  - Animação de entrada para o header (`topdown`).
  - Animação de entrada para o conteúdo principal (`downtop`).
  - Efeito de hover nas imagens dos cards (zoom e escurecimento).
- Trabalhei com responsividade usando Grid e Flexbox.
- Organizei variáveis CSS para facilitar a manutenção dos estilos.

## Como foi feito

- **HTML:** Estrutura básica com `header`, `main` e cards, usando classes para estilização.
- **CSS:**
  - Defini animações com `@keyframes` (`topdown` e `downtop`) e apliquei usando a propriedade `animation` nos elementos desejados.
  - No hover das imagens dos cards, utilizei `transform: scale()` para o efeito de zoom e `filter: brightness()` para escurecer.
  - Usei variáveis CSS para fontes, cores e tamanhos.
  - Implementei responsividade com media queries, adaptando o layout para diferentes larguras de tela.
- **Aprendizado:** 
  - Como aplicar animações de entrada em elementos ao carregar a página.
  - Como criar efeitos visuais interativos com hover.
  - Como organizar o CSS para facilitar futuras manutenções e reutilizações.

---

Este resumo serve para revisar rapidamente os conceitos de animações CSS aplicados neste projeto e como cada parte foi implementada.
