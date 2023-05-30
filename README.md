# [PT-BR] Projeto Docker e Docker Compose - Aplicativo de Tarefas

Este repositório contém um projeto criado com o objetivo de praticar os conceitos de Docker e Docker Compose. A aplicação full-stack é um aplicativo de tarefas e precisa ser conteinerizada para funcionar. Os arquivos de configuração foram desenvolvidos para cada frente específica: Front-end, Back-end e um aplicativo de teste que valida a comunicação entre as aplicações.

## Funcionalidades

- Conteinerização de aplicações
- Criação de conexão entre as aplicações
- Orquestração do funcionamento das aplicações

## Pré-requisitos

Certifique-se de ter o Docker e o Docker Compose instalados em seu sistema antes de prosseguir.

## Configuração

1. Clone este repositório para o seu ambiente local: `git clone https://github.com/seu-usuario/nome-do-repositorio.git`
2. Navegue até o diretório do projeto: cd nome-do-repositorio
3. Execute o comando apropriado para criar as imagens Docker para cada aplicação (Front-end, Back-end e aplicativo de teste):
- Front-end: ` docker build -t frontend -f frontend/Dockerfile . `
- Back-end: ` docker build -t backend -f backend/Dockerfile . `
- Testes: ` docker build -t testapp -f testapp/Dockerfile . `

4. Configure o Docker Compose para orquestrar as aplicações. Edite o arquivo docker-compose.yml conforme necessário para definir as dependências e configurações desejadas.
5. Execute o Docker Compose para iniciar as aplicações: `docker-compose up`

Aguarde até que as aplicações sejam iniciadas e estejam prontas para uso.

# Uso
Após a conclusão da configuração e inicialização, você poderá acessar as aplicações nos seguintes URLs:
Front-end: `http://localhost:3000`
Back-end: `http://localhost:8000`

# Licença
Este projeto é apenas para estudos e não possui uma licença específica.

# [EN] Docker and Docker Compose Project - Task Application

This repository contains a project created to practice the concepts of Docker and Docker Compose. The full-stack application is a task application that needs to be containerized to function properly. Configuration files have been developed for each specific component: Front-end, Back-end, and a test application that validates communication between the applications.

## Features

- Containerization of applications
- Creation of connections between applications
- Orchestration of application functioning

## Prerequisites

Make sure you have Docker and Docker Compose installed on your system before proceeding.

## Configuration

1. Clone this repository to your local environment: `git clone https://github.com/your-username/repository-name.git`
2. Navigate to the project directory: `cd repository-name`
3. Execute the appropriate command to build Docker images for each application (Front-end, Back-end, and test application):
   - Front-end: `docker build -t frontend -f frontend/Dockerfile .`
   - Back-end: `docker build -t backend -f backend/Dockerfile .`
   - Test application: `docker build -t testapp -f testapp/Dockerfile .`

4. Configure Docker Compose to orchestrate the applications. Edit the `docker-compose.yml` file as needed to define dependencies and desired configurations.
5. Run Docker Compose to start the applications: `docker-compose up`

Wait for the applications to start and be ready for use.

## Usage

After the configuration and initialization are complete, you can access the applications at the following URLs:
- Front-end: `http://localhost:3000`
- Back-end: `http://localhost:8000`

# License
This project is for studies only and does not have a specific license.
