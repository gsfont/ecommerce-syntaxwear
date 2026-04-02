# SyntaxWear — E-commerce de Tênis e Sneakers

SyntaxWear é uma landing page de e-commerce para venda de tênis e sneakers, desenvolvida com HTML e CSS puro. O projeto apresenta um design moderno e responsivo, com navegação mobile, seções de categorias, grid de produtos em destaque e footer completo.

## Funcionalidades

- Header fixo com menu de navegação e hamburger menu para mobile
- Seção hero com imagem de destaque e call-to-action
- Seção de categorias (Casual, Esporte, Moderno, Futurista)
- Grid de produtos em destaque com layout assimétrico
- Footer com formulário de newsletter, links de navegação e redes sociais
- Design totalmente responsivo

## Estrutura do Projeto

```
ecommerce-syntaxwear/
├── index.html
├── css/
│   ├── reset.css
│   ├── variables.css
│   ├── base.css
│   └── components/
│       ├── header.css
│       ├── hero.css
│       ├── product-category.css
│       ├── product-grid.css
│       └── footer.css
└── images/
    ├── logo/
    ├── icons/
    ├── banners/
    └── products/
```

## Tecnologias

- HTML5 semântico
- CSS3 (Flexbox, Grid, media queries)
- Google Fonts — [Ubuntu](https://fonts.google.com/specimen/Ubuntu)

## Responsividade

| Breakpoint | Comportamento |
|---|---|
| `> 1280px` | Layout desktop completo |
| `≤ 1280px` | Header compacto, hamburger menu ativo |
| `≤ 768px` | Hero, grid de produtos e footer adaptados para mobile |
| `≤ 500px` | Cards de categoria com altura reduzida |

## Como rodar

Por ser um projeto estático, basta abrir o arquivo `index.html` no navegador — sem dependências ou build necessário.

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/ecommerce-syntaxwear.git

# Abra o arquivo no navegador
open index.html
```

## Seções da Página

- **Header** — Logo, navegação principal (Masculino, Feminino, Outlet) e ícones de conta, ajuda e sacola
- **Hero** — Banner com produto em destaque (Krypton One) e botões de ação
- **Categorias** — Cards para Casual, Esporte, Moderno e Futurista
- **Grid de Produtos** — Layout assimétrico com 6 produtos em destaque
- **Footer** — Newsletter, redes sociais (Instagram, WhatsApp, TikTok, Facebook) e links de navegação

## Licença

Este projeto foi desenvolvido para fins educacionais.
