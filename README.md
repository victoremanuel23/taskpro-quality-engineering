# TaskPro Quality Engineering

Este repositório contém a coleção Postman e o ambiente para testar a API TaskPro, além de instruções para executar os testes usando Newman.

## Como usar

### Pré-requisitos

- [Node.js](https://nodejs.org/) instalado (recomendado versão 14 ou superior)
- Newman instalado globalmente (opcional, você também pode usar via `npx`)

### Instalando o Newman globalmente

Abra o terminal e rode:


newman run ./postman/TaskPro_API.postman_collection.json -e ./postman/TaskPro_Environment.postman_environment.json -r cli


```bash
npm install -g newman
