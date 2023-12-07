# Sistema de Gerenciamento de Tarefas

## Visão Geral

Este é um sistema de gerenciamento de tarefas desenvolvido em .NET (C#). Ele permite aos usuários organizar e monitorar suas tarefas diárias, bem como colaborar com colegas de equipe.

## Funcionalidades

- Listagem de Projetos: listar todos os projetos do usuário
- Visualização de Tarefas: visualizar todas as tarefas de um projeto específico
- Criação de Projetos: criar um novo projeto
- Criação de Tarefas: adicionar uma nova tarefa a um projeto
- Atualização de Tarefas: atualizar o status ou detalhes de uma tarefa
- Remoção de Tarefas: remover uma tarefa de um projeto

## Como executar

### Pré-requisitos

- .NET 7.0 ou superior
- Docker

### Execução local

1. Clone o repositório
2. Navegue até a pasta do projeto
3. Execute o comando `dotnet run`

### Execução via Docker

1. Clone o repositório
2. Navegue até a pasta do projeto
3. Construa a imagem Docker com o comando `docker build -t nome-da-imagem .`
4. Execute o container com o comando `docker run -p 8000:80 nome-da-imagem`

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
