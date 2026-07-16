# TaskFlow - Sistema de Gerenciamento de Tarefas

## Descrição

O TaskFlow é um sistema web desenvolvido como projeto da disciplina de Engenharia de Software. O objetivo é permitir o gerenciamento de tarefas utilizando princípios de metodologias ágeis e boas práticas de desenvolvimento de software.

## Objetivo

Desenvolver uma aplicação capaz de:

- Cadastrar tarefas
- Listar tarefas
- Editar tarefas
- Excluir tarefas
- Gerenciar o status das tarefas
- Definir prioridade

## Tecnologias Utilizadas

- Java 21
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
- Git
- GitHub
- GitHub Actions

## Metodologia

O projeto utiliza Kanban para organização das atividades e GitHub como ferramenta de versionamento.

## Estrutura

```
src/
 ├── main
 ├── test
 └── resources
```

## Mudança de Escopo

Inicialmente o sistema possuía apenas operações básicas de CRUD. Durante o desenvolvimento foi adicionada a funcionalidade de prioridade das tarefas (Alta, Média e Baixa), simulando uma alteração de requisitos do cliente.

## Testes

Os testes automatizados serão implementados utilizando JUnit e executados automaticamente através do GitHub Actions.
