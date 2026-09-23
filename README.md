# 🎮 The Legend of Zelda: Ocarina of Time — Blog

Um projeto acadêmico de desenvolvimento web inspirado no clássico **The Legend of Zelda: Ocarina of Time**.

O projeto foi desenvolvido com **HTML5 e CSS3**, utilizando estrutura semântica, formulário de inscrição e conceitos de Flexbox para organização e estilização da interface.

## 📌 Sobre o projeto

O blog apresenta informações sobre a história e a aventura de Link pelo reino de Hyrule, além de um formulário para inscrição dos visitantes.

O objetivo do projeto é praticar conceitos fundamentais de desenvolvimento web, como:

* Estrutura semântica do HTML
* Formulários HTML
* Validação de campos
* Método GET
* CSS
* Flexbox
* Responsividade
* Acessibilidade
* Organização visual de interfaces

## 🛠️ Tecnologias utilizadas

* HTML5
* CSS3
* Flexbox
* Visual Studio Code
* Live Server

## 📂 Estrutura do projeto

```text
zelda-ocarina-of-time-blog/
│
├── index.html
└── README.md
```

## 🧩 Funcionalidades

### Blog

O projeto possui:

* Cabeçalho com título do blog
* Menu de navegação
* Seção sobre a história do jogo
* Seção sobre a aventura em Hyrule
* Imagens relacionadas ao jogo
* Rodapé

### Formulário

O formulário de inscrição possui:

* Campo para nome
* Validação de nome com mínimo de 3 caracteres
* Campo para e-mail
* Validação de e-mail
* Campo para idade
* Validação de idade entre 18 e 120 anos
* Seleção de assunto
* Checkbox de aceite dos termos
* Botão de envio
* Envio dos dados utilizando o método `GET`

## 🎨 Estilização

A interface utiliza:

* Cores inspiradas no universo de Zelda
* Fundo escuro
* Destaques em tons dourados
* Container estilizado para o formulário
* Bordas arredondadas
* Espaçamento entre os elementos
* Efeito `hover` no botão
* Flexbox para organização dos campos

O formulário também possui um layout responsivo. Em telas maiores, os campos de **Nome** e **E-mail** ficam lado a lado. Em telas menores, eles são organizados verticalmente.

## ▶️ Como executar

1. Clone este repositório:

```bash
git clone https://github.com/SEU-USUARIO/zelda-ocarina-of-time-blog.git
```

2. Abra a pasta do projeto no Visual Studio Code.

3. Abra o arquivo:

```text
index.html
```

4. Utilize a extensão **Live Server** para executar o projeto no navegador.

Também é possível abrir o arquivo `index.html` diretamente no navegador.

## 🧪 Validação

O projeto pode ser validado utilizando o **W3C Markup Validation Service**, verificando a estrutura e a sintaxe do HTML.

## 📱 Responsividade

O layout possui uma regra de media query para dispositivos menores:

```css
@media (max-width: 600px) {
    .linha-campos {
        flex-direction: column;
    }
}
```

Dessa forma, os campos do formulário se adaptam ao tamanho da tela.

## 🎓 Projeto acadêmico

Este projeto foi desenvolvido como atividade prática para aplicação dos fundamentos de **HTML, CSS, semântica, formulários e Flexbox**.

---

🎮 **The Legend of Zelda: Ocarina of Time**

*Uma pequena homenagem a uma das aventuras mais marcantes de Hyrule.*
