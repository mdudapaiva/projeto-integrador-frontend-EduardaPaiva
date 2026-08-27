# 🌷 Jardim Encantado — Catálogo de Flores

## 📖 Sobre o projeto

O **Jardim Encantado** é um projeto de catálogo virtual de flores desenvolvido utilizando **HTML e CSS**. O objetivo é apresentar diferentes tipos de flores de forma organizada, bonita e simples, permitindo que o visitante conheça as características, descrições e preços de cada espécie.

O projeto foi desenvolvido como uma atividade de aprendizagem em **desenvolvimento Front-End**, utilizando conceitos básicos de estruturação de páginas HTML e estilização com CSS.

## 🌸 Flores disponíveis

O catálogo apresenta diferentes espécies de flores, como:

* 🌹 Rosa Vermelha
* 🌻 Girassol
* 🌷 Tulipa
* 🌼 Margarida
* 🤍 Lírio
* 💜 Orquídea

Cada flor possui uma **imagem, nome, descrição e preço**, facilitando a visualização das informações pelo usuário.

## 🎯 Objetivo

O objetivo do projeto é criar uma página web simples e intuitiva para apresentar produtos de uma floricultura, praticando conceitos fundamentais de desenvolvimento web.

## 💻 Tecnologias utilizadas

* **HTML5** — estrutura da página;
* **CSS3** — aparência, organização e responsividade;
* **YouTube** — vídeo relacionado a flores e arranjos florais.

## 📂 Estrutura do projeto

```text
floricultura/
│
├── index.html
├── estilo.css
└── README.md
```

### 📄 index.html

Contém toda a estrutura da página, incluindo o cabeçalho, menu, catálogo de flores, informações sobre a floricultura, vídeo e contato.

### 🎨 estilo.css

Responsável pela aparência do site, incluindo cores, fontes, espaçamentos, imagens, cards das flores, efeitos ao passar o mouse e organização do catálogo.

### 📘 README.md

Contém a descrição e as informações sobre o projeto.

## 🎥 Vídeo

O site também apresenta um vídeo relacionado a **arranjos florais**, incorporado diretamente do YouTube através da tag `<iframe>`.

## 🌱 Possíveis melhorias futuras

* Adicionar botão de compra;
* Criar um carrinho de compras;
* Adicionar mais espécies de flores;
* Criar uma página individual para cada flor;
* Adicionar formulário de contato;
* Implementar JavaScript para tornar o site interativo;
* Adicionar sistema de busca e filtros.

## 👩‍💻 Projeto acadêmico

Projeto desenvolvido para fins educacionais, com o objetivo de praticar conhecimentos básicos de **HTML e CSS** no desenvolvimento de uma página web.

**Jardim Encantado 🌷 — Flores que transformam momentos em memórias.**











 Avaliação do código
 Pontos positivos
- **Estrutura semântica correta:** uso de `<header>`, `<nav>`, `<section>` e `<footer>` em vez de `<div>` genéricas.
  
Pontos para melhorar

- **Adicionar a tag `<main>`:** falta um `<main>` envolvendo o conteúdo principal da página, entre o `<header>` e o `<footer>`. Isso melhora a estrutura semântica e ajuda tecnologias assistivas a identificar o conteúdo central da página.

- **Organizar a navegação com uma lista:** atualmente, o `<nav>` possui links soltos. O ideal semanticamente é utilizar `<ul>` e `<li>` para estruturar os links de navegação.
