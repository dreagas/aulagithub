# Mercado Frescor & Cia — Site institucional de supermercado

O projeto foi remodelado para representar claramente um **supermercado** (e não uma empresa de serviços), com foco em setores reais da loja e ofertas para consumidores.

## Páginas do site

- `index.html` — Home com destaque para experiência do mercado e principais categorias.
- `sobre.html` — História da loja, compromissos e proposta de valor.
- `servicos.html` — Página de setores (frutaria, padaria e açougue).
- `planos.html` — Página de ofertas da semana com produtos e preços promocionais.
- `contato.html` — Canais de contato para dúvidas e encomendas.

## Estrutura e comportamento

- Navegação integrada entre todas as páginas (desktop e mobile).
- Estilo visual único em `styles.css` para manter consistência e elegância.
- Animações de entrada por seção usando `.reveal` em conjunto com `app.js`.
- Menu mobile com botão hambúrguer para telas menores.
- Imagens externas temáticas de supermercado/produtos (frutas, padaria, açougue, mercearia), sem pasta local de assets.

## Tecnologias

- HTML5
- CSS3
- JavaScript Vanilla

## Executar localmente

Abra `index.html` diretamente no navegador ou rode um servidor estático:

```bash
python3 -m http.server 8000
```

Acesse:

- `http://localhost:8000/index.html`
