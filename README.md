# Frescor & Cia — Site institucional multi-páginas

Este projeto agora possui uma estrutura completa de páginas de negócio conectadas entre si, com foco em visual moderno, responsividade e animações suaves.

## Páginas criadas

- `index.html` — Página inicial com proposta de valor, destaque visual e CTA principal.
- `sobre.html` — História da empresa, posicionamento e valores.
- `servicos.html` — Soluções oferecidas para crescimento do negócio.
- `planos.html` — Planos de contratação (Essencial, Profissional, Elite).
- `contato.html` — Canal de contato e convite para diagnóstico gratuito.

## Como o site funciona

- Todas as páginas compartilham:
  - **Navegação conectada** no topo (desktop + menu mobile).
  - **Identidade visual consistente** via `styles.css`.
  - **Animações de entrada** em seções com classe `.reveal` controladas por `app.js`.
- O menu mobile é acionado por botão hambúrguer e funciona em telas menores.
- O layout é responsivo com breakpoints para desktop, tablet e smartphone.
- As imagens são carregadas por URLs aleatórias/externas (Unsplash), evitando pasta local de assets neste momento.

## Tecnologias usadas

- HTML5
- CSS3 (custom, com gradientes, microinterações e transições)
- JavaScript vanilla (menu mobile + IntersectionObserver para animações)

## Rodando localmente

Como o projeto é estático, basta abrir `index.html` no navegador.

Se preferir usar um servidor local simples:

```bash
python3 -m http.server 8000
```

Depois acesse:

- `http://localhost:8000/index.html`

## Experiência visual implementada

- Estilo moderno com efeito glassmorphism suave no topo.
- Cartões com hover animado.
- Botões com gradientes e elevação.
- Transições suaves para navegação e estados interativos.
- Estrutura elegante com foco em clareza, conversão e apresentação premium.
