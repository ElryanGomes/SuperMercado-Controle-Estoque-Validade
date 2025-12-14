# 📦 SISTEMA DE CONTROLE DE ESTOQUE E VALIDADE

*Gerenciando produtos, evitando perdas e apoiando decisões no comércio*

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-Markup-orange.svg)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Style-blue.svg)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)

> Construído com as tecnologias:
> **HTML**, **CSS**, **JavaScript (POO)**

---

## 🔎 Visão geral

O **Sistema de Controle de Estoque e Validade** é uma aplicação web desenvolvida com **JavaScript orientado a objetos**, que simula o funcionamento de um sistema real utilizado em comércios para gerenciamento de produtos.

O foco principal do projeto é o **controle de validade de produtos perecíveis**, permitindo identificar itens longe do vencimento, próximos de vencer e já vencidos, ajudando a reduzir perdas e melhorar a organização do estoque.

---

## 🧠 Por que este projeto?

Este projeto foi criado com o objetivo de praticar conceitos fundamentais de **Programação Orientada a Objetos (POO)**, **manipulação do DOM** e **lógica de negócio**, aplicando tudo em um cenário próximo da realidade.

Principais recursos:

- 📥 **Cadastro de produtos**
  - Perecíveis e não perecíveis
  - Controle de quantidade e distribuidor

- 🔍 **Busca inteligente**
  - Pesquisa por **nome** ou **código**
  - Filtros por tipo de produto

- 📦 **Tela de estoque**
  - Listagem organizada dos produtos
  - Filtros dinâmicos

- ⏳ **Controle de validade**
  - Classificação automática:
    - 🟢 Longe de vencer
    - 🟡 Em risco
    - 🔴 Vencidos
  - Contadores de produtos por status
  - Filtro por situação da validade

---

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura da aplicação  
- **CSS3** — estilização e layout  
- **JavaScript (ES6)** — lógica, POO e manipulação do DOM  

---

## 📁 Estrutura do projeto

```bash
📂 projeto
├── index.html
├── css/
│   └── style.css
├── js/
│   ├── Produto.js
│   ├── ProdutoPerecivel.js
│   ├── ProdutoImperecivel.js
│   ├── Estoque.js
│   └── main.js
