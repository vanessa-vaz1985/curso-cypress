# Sobre o projeto
Este projeto foi desenvolvido durante o curso "Testes de aplicações modernas com Cypress", ministrado por "Francisco Wagner Costa Aquino".
https://www.udemy.com/course/testes-cypress/


## Pré-requisitos para utilizar o Cypress no projeto
### Instalar o Node.js
### Possuir um editor de texto (nesse projeto foi utilizado o Visual Studio Code)
### Criar um arquivo "package.json" dentro do projeto, antes de instalar o Cypress:
    npm init -y

## Para instalar o cypress com a última versão disponível:
    npm install cypress

## Para instalar o cypress com uma versão específica:
    npm install cypress@3.6.0

## Configurar script no arquivo "package.json" para abrir o cypress:
    "cypress:open": "cypress open"

## Para executar o script que abre o cypress:
    npm run cypress:open

## Para executar sem o script no terminal:
    node_modules\.bin\cypress open

## Para não executar determinado teste, incluir skip:
    it.skip

## Para não executar determinado grupo de teste, incluir skip:
    describe.skip

## Para executar apenas determinado teste, incluir only:
    it.only

## Para executar um arquivo de teste específico pelo terminal, visualizando a execução e ao final permanecer com a tela aberta:
    npm run cy:run -- --spec cypress/integration/barriga/backend.spec.js --headed --no-exit

