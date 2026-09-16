# Portfólio | Erik Kohagura

Portfólio pessoal desenvolvido do zero com HTML e CSS puros, sem frameworks. O site apresenta quem eu sou, minha formação em Engenharia de Sistemas Ciber-Físicos na PUC-SP e os links para minhas redes profissionais.

## Sobre o projeto

O objetivo deste projeto foi praticar a construção de páginas web estáticas com foco em organização de código, boas práticas de nomenclatura e responsividade. Todo o layout foi feito à mão, usando Flexbox para o posicionamento dos elementos e media queries para adaptar a página a telas menores.

## Páginas

**Home** (`index.html`): página inicial com apresentação, foto e botões de acesso ao LinkedIn e ao GitHub.

**Sobre mim** (`about.html`): texto de apresentação com minha trajetória acadêmica, projetos em controle, sistemas embarcados e robótica, e os objetivos profissionais.

## Tecnologias utilizadas

HTML5, CSS3 e Google Fonts (Krona One e Montserrat).

## Destaques técnicos

O CSS segue a metodologia **BEM** (Block, Element, Modifier), o que deixa as classes legíveis e fáceis de manter, como em `cabecalho__menu__link` e `apresentacao__conteudo__texto`.

As cores e fontes são centralizadas em **variáveis CSS** no `:root`, permitindo alterar a identidade visual do site inteiro mudando poucos valores.

O layout é **responsivo**: abaixo de 1300px de largura, o conteúdo passa a ser exibido em coluna, com a foto acima do texto e o menu centralizado.

## Estrutura de pastas

```
portfolio/
├── index.html
├── about.html
├── styles/
│   └── style.css
└── assets/
    ├── minha_foto.jpg
    ├── linkedin.png
    └── github.png
```

## Como executar

Não é necessário instalar nada. Basta clonar o repositório e abrir o arquivo `index.html` no navegador.

```bash
git clone https://github.com/ErikVks/portfolio.git
```

## Contato

Erik Vitor Kohagura Silva
[LinkedIn](https://linkedin.com/in/erik-vitor-kohagura-silva-907653325) | [GitHub](https://github.com/ErikVks) | erik.vks@icloud.com
