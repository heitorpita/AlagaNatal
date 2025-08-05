# Convenção de Projeto — HTML, CSS e JS

Este documento define as principais convenções para organização, nomenclatura e estrutura de um projeto utilizando HTML, CSS e JavaScript.

---

## 1. Estrutura de Diretórios

```
/project-root
│
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── img/
│       └── logo.png
└── README.md
```

---

## 2. Nomenclatura de Arquivos

- **HTML:** minúsculo, palavras separadas por hífen  
  `index.html`, `about-us.html`
- **CSS:** minúsculo, palavras separadas por hífen  
  `style.css`, `responsive-header.css`
- **JS:** minúsculo, palavras separadas por hífen  
  `main.js`, `form-handler.js`
- **Imagens:** minúsculo, palavras separadas por hífen  
  `logo.png`, `banner-home.jpg`

---

## 3. Convenções de Código

### HTML

- Use indentação de **2 espaços**.
- Utilize tags semânticas (`<header>`, `<main>`, `<footer>`, etc).
- Sempre defina o atributo `alt` para imagens.
- Use aspas duplas para atributos.

### CSS

- Use indentação de **2 espaços**.
- Classes e IDs: minúsculo, palavras separadas por hífen  
  `.menu-principal`, `#form-contato`
- Agrupe estilos por componente/seção.
- Evite o uso de `!important`.

### JavaScript

- Use indentação de **2 espaços**.
- Nomes de variáveis e funções em **camelCase**  
  `getUserName`, `formSubmitHandler`
- Agrupe scripts por funcionalidade.
- Comentários explicativos para funções e trechos complexos.

---

## 4. Boas Práticas

- Separar responsabilidades: HTML para estrutura, CSS para estilo, JS para comportamento.
- Manter o código limpo e organizado.
- Escrever comentários claros e objetivos.
- Nomear arquivos e pastas de forma descritiva e consistente.
- Atualizar o README.md com instruções de uso e estrutura do projeto.

---
