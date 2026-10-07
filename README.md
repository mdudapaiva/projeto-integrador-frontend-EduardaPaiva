# 🌷 Jardim Encantado — Catálogo de Flores

## 📖 Sobre o projeto

O Jardim Encantado é um catálogo virtual de flores desenvolvido com HTML e CSS. Apresenta diferentes espécies de forma organizada e bonita, com imagem, descrição e preço de cada uma.

Projeto desenvolvido como atividade de aprendizagem em Desenvolvimento Front-End.

## 🌸 Flores disponíveis

- 🌹 Rosa Vermelha
- 🌻 Girassol
- 🌷 Tulipa
- 🌼 Margarida
- 🤍 Lírio
- 💜 Orquídea

## 💻 Tecnologias utilizadas

- **HTML5** — estrutura semântica da página
- **CSS3** — variáveis, box model, Flexbox, Grid e pseudo-classes
- **YouTube** — vídeo de arranjos florais incorporado com `<iframe>`

## 📂 Estrutura do projeto

```
projeto-integrador-frontend-EduardaPaiva/
│
├── index.html
├── README.md
└── css/
    ├── reset.css
    └── style.css
```

- **index.html** — cabeçalho, menu, catálogo, tabela de preços, lista de cuidados, sobre, vídeo e contato.
- **css/reset.css** — `box-sizing: border-box` global e remoção de margens/padding padrão.
- **css/style.css** — aparência do site.

## 🎨 Conceitos de CSS aplicados

### Aula 06 — Estilização base

- Variáveis CSS no `:root` (cores, espaçamento, raio de borda e sombras), reutilizadas em várias propriedades
- Seletores de classe reutilizáveis: `.flor`, `.destaque`, `.botao`
- Seletor de ID: `#titulo-principal`
- Combinadores: descendente (`.flor h3`), filho direto (`nav > a`) e agrupamento (títulos de seção), com comentário justificando cada escolha
- Box model explícito (padding, border e margin) em `.flor` e `.botao`
- Estados de link na ordem LoVe/HAte: `a:link`, `a:visited`, `a:hover`, `a:active`
- Tabela com `border-collapse` e lista com `list-style-type` temático
- `font-size` sempre em `rem`, para respeitar a preferência de fonte do usuário
- `object-fit: cover` nas imagens das flores

### Aula 07 — Flexbox, Grid e pseudo-classes

- Barra de navegação com `display: flex`, com `:hover` e `:focus-visible` nos links
- Catálogo com `display: grid` e `repeat(auto-fit, minmax(250px, 1fr))`, responsivo sem media query
- Pseudo-classes estruturais: `:first-child`, `:last-child` e `:nth-child(even)`
- Animação de hover com `transform` (não `width`/`height`), evitando reflow

## 🌱 Possíveis melhorias futuras

- Botão de compra e carrinho de compras
- Mais espécies de flores e uma página individual para cada uma
- Formulário de contato
- JavaScript para interatividade, busca e filtros

## 👩‍💻 Projeto acadêmico

Desenvolvido para fins educacionais.

**Jardim Encantado 🌷 — Flores que transformam momentos em memórias**
