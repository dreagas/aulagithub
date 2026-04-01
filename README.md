# Mercado Frescor & Cia

Site estático institucional para supermercado, com foco em apresentação de setores (frutaria, padaria, açougue e mercearia), ofertas e canais de contato.

## Stack tecnológica

- **HTML5 semântico** para estrutura de conteúdo por página.
- **CSS3 modular (`styles.css`)** com:
  - design system via custom properties (`:root`),
  - layout responsivo com CSS Grid,
  - componentes reutilizáveis (`.card`, `.btn`, `.hero`, `.cta`),
  - microinterações e animações (`hover`, `pulse`, `shine`, `zoomSlow`),
  - cena de fundo animada (`.bg-scene`, `.bg-orb`, `.bg-grid`).
- **JavaScript Vanilla (`app.js`)** com:
  - toggle do menu mobile,
  - animação de entrada por viewport com `IntersectionObserver`,
  - efeito de parallax leve nos elementos de fundo com `mousemove`.

## Estrutura do projeto

```text
.
├── index.html      # Página inicial e destaques do supermercado
├── sobre.html      # História da loja e compromissos
├── servicos.html   # Setores da loja
├── planos.html     # Ofertas da semana
├── contato.html    # Canais de atendimento
├── styles.css      # Estilos globais, responsividade e animações
├── app.js          # Interações e comportamentos visuais
└── README.md
```

## Arquitetura de interface

- **Navegação global unificada** em todas as páginas (desktop + mobile).
- **Composição visual consistente** baseada em componentes compartilhados.
- **Imagens externas temáticas** (supermercado e produtos) para acelerar prototipação sem pipeline de assets local.
- **Experiência responsiva** com breakpoints principais em `960px` e `700px`.

## Executar localmente

```bash
python3 -m http.server 8000
```

Acesse em: `http://localhost:8000/index.html`.
