# Portfólio: Desenvolvimento Frontend para Pró Colchões

Este repositório contém o código-fonte de múltiplos componentes e páginas institucionais desenvolvidos por **Matheus Trajano** e atualmente **em produção** no site da Pró Colchões.

O projeto foi construído do zero com **HTML5, CSS3 e JavaScript puro (Vanilla JS)**, com o desafio de integrar soluções personalizadas e de alta performance na plataforma de e-commerce **Agile E-commerce**.

### 🚀 Demonstração Ao Vivo

Você pode ver o código em ação diretamente no site da empresa:
*   **Página "Quem Somos":** [procolchoes.com.br/quem-somos](https://www.procolchoes.com.br/quem-somos)
*   **Página de Catálogos:** [procolchoes.com.br/catalogos](https://www.procolchoes.com.br/conheca-nossa-historia)
*   **Popup de Leads e Barra de Notícias:** Visíveis na navegação geral do site.

---

### ✨ Habilidades e Técnicas Demonstradas

#### 1. Integração Segura em Ambiente de Produção.
-   **CSS Isolado:** Para garantir que os estilos dos componentes não entrassem em conflito com o CSS global da plataforma, todo o código foi encapsulado dentro de um seletor de ID (`#procolchoes-content`).
-   **JavaScript Encapsulado (IIFE):** O código JavaScript foi envolvido em uma IIFE `(function(){ ... })();` para evitar a poluição do escopo global, uma prática essencial para o desenvolvimento em plataformas compartilhadas.

#### 2. Componentes Dinâmicos e Focados em UX
-   **Popup de Leads com Fetch API:** Um modal interativo para captura de leads, que utiliza `localStorage` para não ser exibido repetidamente ao mesmo usuário. O envio é feito de forma assíncrona com `fetch()`, com máscara de telefone e feedback visual de carregamento.
-   **Carrossel de Notícias:** Uma barra de informações no topo do site, construída em JavaScript puro, com navegação e transição automáticas.
-   **Player de Vídeo Otimizado:** O vídeo institucional do YouTube só é carregado após o clique do usuário, uma técnica crucial para otimizar o tempo de carregamento inicial da página (First Contentful Paint).

#### 3. Design Moderno e Otimização de Performance
-   **Layouts Responsivos com Grid e Flexbox:** Construção de layouts complexos e totalmente fluidos, como a timeline e os grids de features, que se adaptam a qualquer dispositivo.
-   **Animações Performáticas com `IntersectionObserver`:** Efeitos de "fade-in" suaves são ativados conforme o usuário rola a página, garantindo uma animação fluida sem impactar a performance.

### 🛠️ Tecnologias
-   **HTML5:** Estrutura semântica e acessível.
-   **CSS3:** Flexbox, Grid, Variáveis, Animações, Gradientes.
-   **JavaScript (ES6+):** `fetch` API, `IntersectionObserver`, `localStorage`, Manipulação do DOM.

---

Este projeto demonstra minha capacidade de entregar soluções frontend robustas, performáticas и seguras, desde a concepção até a implementação bem-sucedida em um ambiente de e-commerce real e de grande escala.
