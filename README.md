<h1 align="center">
    <img src="https://github.com/andrewdourado/gostack-desafio-reactjs-crud/blob/master/src/assets/logo-background.svg" alt="GoRestaurant" width="300px" style="color:blue">
</h1>

<h3 align="center">Desafio 10: React.js CRUD</h3>

<p align="center">
  <img src="https://github.com/andrewdourado/gostack-desafio-reactjs-crud/blob/master/demo.gif" alt="GoRestaurant" />   
</p>

<p align="center">
  <a href="https://github.com/andrewdourado/gostack-desafio-reactjs-crud/blob/master/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/andrewdourado/gostack-desafio-reactjs-crud?style=for-the-badge"></a>
</p>

## Descrição 

Nesse desafio foi desenvolvido a GoRestaurant que consiste na exibição de pratos cadastrados na fake API. Esta aplicação tem como objetivo lidar com o conceito de CRUD (Create, Read, Update, Delete).

## Utilizando uma fake API

Antes de tudo, para que você tenha os dados para exibir em tela, existe um arquivo que você poderá utilizar como fake API para te prover esses dados.

Para isso, existe uma dependência no package.json chamada `json-server`, e um arquivo chamado `server.json` que contém os dados para uma rota `/products`. Para executar esse servidor você pode executar o seguinte comando:

```js
  yarn json-server server.json -p 3333
```

## Funcionalidades da aplicação

- **`Listar os pratos de comida da sua API`**: A página `Dashboard` exibe uma listagem, com o campo `title`, `value`, `description` e `available` de todos os pratos de comida que estão cadastrados na API.

- **`Adicionar novos pratos de comida a sua API`**: Na página Dashboard abre um modal ao clicar no botão `Novo Prato` no Header. Esse modal é responsável por cadastrar uma nova food passando os campos `image`, `name`, `description`, `value`.

- **`Editar pratos de comida da sua API`**: Na página Dashboard abre um modal ao clicar no botão `Editar Prato`. Esse modal é responsável por editar uma food passando os campos `image`, `name`, `description`, `value`.

- **`Remover pratos de comida da sua API`**: Na página Dashboard um prato de comida é removido ao clicar no botão com ícone de lixeira no componente Food.

- **`Alterar disponibilidade dos pratos de comida da sua API`**: Na página Dashboard é possível alterar a disponibilidade de um prato de comida ao clicar no switch que é controlado pelo valor de `available`.


## Instalação

Para executar este projeto é necessário a instalacão prévia do [Git](https://git-scm.com/downloads "Git download") e do [Yarn](https://classic.yarnpkg.com/en/docs/install "Yarn download"):

```bash
# Clona este repositório
$ git clone https://github.com/andrewdourado/gostack-desafio-reactjs-crud.git

# Acessa o repositório clonado
$ cd gostack-desafio-reactjs-crud

# Instala as dependências
$ yarn

# Executa o projeto.
$ yarn start
```

## Tecnologias

- <a href="https://reactjs.org/" target="_blank" rel="noopener noreferrer">React</a>
- <a href="https://www.typescriptlang.org/" target="_blank" rel="noopener noreferrer">TypeScript</a>
- <a href="https://eslint.org/" target="_blank" rel="noopener noreferrer">ESLint</a>
- <a href="https://prettier.io/" target="_blank" rel="noopener noreferrer">Prettier</a>

## Créditos

Este projeto foi desenvolvido durante o Bootcamp GoStack 11 da <a href="https://rocketseat.com.br/" target="_blank" rel="noopener noreferrer">Rocketseat</a>.

## Licença
Esse projeto está sob a licença [MIT](https://github.com/andrewdourado/gostack-desafio-reactjs-crud/blob/master/LICENSE) © [André Dourado](https://github.com/andrewdourado)
