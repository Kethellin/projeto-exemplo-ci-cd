## Objetivo

O objetivo deste projeto, construído em Nest.Js foi apresentar os princípios de CI/CD utilizando o GitHub Actions.

Primeiro definimos os gatilhos (triggers) que ativam o workflow:
```bash
(Push) para os ramos main ou develop

(Pull Request) quando é criado ou atualizado para os ramos main ou develop
```

Esse processo é extremamente útil porque automatiza tarefas essenciais sempre que alguém envia um código novo para os branches main ou develop. Com essa automação, o GitHub Actions baixa o código, instala as dependências, compila o projeto e executa os testes automaticamente. Isso garante que o código novo não quebre a aplicação e que os testes continuem passando, antes mesmo de alguém revisar ou aprovar um pull request. Além disso, essa prática ajuda a manter a qualidade e a estabilidade do projeto, evitando que bugs ou erros de build passem despercebidos e cheguem até a produção.

## Configuração inicial

```bash
$ npm install
```

## Compile e rode o projeto

```bash
# Modo Desenvolvimento
$ npm run start

# Modo Watch
$ npm run start:dev

# Modo Produção
$ npm run start:prod
```
