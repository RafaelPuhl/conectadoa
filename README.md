# ConectaDoa

O ConectaDoa é um projeto desenvolvido com a proposta de aproximar pessoas e iniciativas sociais por meio da organização de doações.

A ideia é construir uma ferramenta simples e acessível, que possa ajudar uma ONG a organizar suas atividades e acompanhar suas ações.

Neste primeiro momento, o projeto está na sua estrutura inicial, com uma aplicação web e uma API funcionando de forma integrada.

## Tecnologias utilizadas

- Vite+ e JavaScript
- Node.js
- Express
- dotenv
- Git e GitHub

## Como executar o projeto

Antes de começar, é necessário ter o Git, o Vite+ e o VS Code instalados.

### 1. Baixar o projeto

```bash
git clone https://github.com/RafaelPuhl/conectadoa.git
cd conectadoa
```

### 2. Instalar as dependências

```bash
pnpm install
```

### 3. Iniciar a API

Em um terminal, execute:

```bash
pnpm api
```

A API ficará disponível na porta 3000.

### 4. Iniciar a aplicação web

Em outro terminal, dentro da pasta do projeto, execute:

```bash
vp dev
```

O endereço local será:

http://localhost:5173

## Verificação da API

A aplicação possui uma rota para verificar se o servidor está funcionando:

`GET /api/health`

Para testar diretamente, acesse:

http://localhost:3000/api/health

A resposta apresenta o status do serviço, o nome da aplicação e a data e hora da consulta.

## Organização do projeto

- `src/` — arquivos da aplicação web.
- `server/` — código da API.
- `public/` — arquivos públicos.
- `.env` — configurações locais.
- `.env.example` — exemplo das variáveis necessárias.

## Desenvolvimento

Este projeto faz parte da disciplina Projeto Integrador Extensionista II.

A aplicação será desenvolvida gradualmente, começando pela estrutura inicial e pela comunicação entre o frontend e o backend.

## Como executar o projeto

Para iniciar a aplicação, abra o terminal na pasta do projeto e execute:

vp dev

A interface web ficará disponível em http://localhost:5173.

A API utiliza a porta 3000 e pode ser testada pelo endereço:

http://localhost:3000/api/health
