# Docker Todo List Project

# Contexto
Este projeto trata-se de uma aplicação de uma lista de afazeres com frontend, backend e arquivo de testes utilizando Docker. 
Realizei a "containerização" das aplicações, criei também uma conexão entre elas e orquestrei seu funcionamento.
Também criei imagens das aplicações e as configurei com docker compose.

## Tecnologias usadas

Front-end:
> Desenvolvido usando: React, Context API, CSS3, HTML5, Javascript ES6

Back-end:
> Desenvolvido usando: Docker, Docker Compose

## Habilidades treinadas

* Usar comandos dockers no CLI - Interface de linha de comando;
* Criar um contêiner Docker para uma aplicação de front-end;
* Criar um contêiner Docker para uma aplicação de back-end;
* Criar um contêiner Docker para uma aplicação de testes;
* Orquestrar os três contêineres utilizando o Docker compose.

## Clonando o repositório

  * `git clone git@github.com:juan-formoso/docker-todo-list-project.git`.
  * Entre na pasta do repositório clonado:
    * `cd docker-todo-list-project`

## Instalando Dependências

> Backend
```bash
cd ./todo-app/back-end/ 
npm install
``` 
> Frontend
```bash
cd ./todo-app/front-end/
npm install
``` 
## Executando aplicação

* Para rodar o back-end:

  ```
  cd ./todo-app/back-end/ && npm start
  ```
  - Por padrão, essa aplicação funciona a partir da porta `3001`;

* Para rodar o front-end:

  ```
  cd ./todo-app/front-end/ && npm start
  ```
  - Por padrão, essa aplicação funciona a partir da porta `3000`;

## Executando Testes

* Para rodar todos os testes:

  - ⚠️ Essa aplicação só funciona **se associada a uma rede Docker**;
  ```
    cd ./todo-app/front-end
    npm install
    npm test
  ```
