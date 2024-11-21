# Projeto Spring Lista de Games Back-End

## Linguagem
- Java Spring Boot

## Software
- Spring Tool Suite
- PostgreSQL
- Docker
- Postman

## Requisitos 
- H2 Database
- Spring Framework
- Maven

## Conceitos
- Sistemas web e recursos
- Cliente/servidor, HTTP, JSON
- Padrão REST para API web
- Estruturação de projeto Spring REST
- Entidades e ORM
- Database seeding
- Padrão camadas
  - Controller
  - Service
  - Repository
- Padrão DTO

[![PADR-O-CAMADAS.png](https://i.postimg.cc/TwSLhKcG/PADR-O-CAMADAS.png)](https://postimg.cc/dk2txtXS)
[![UML.png](https://i.postimg.cc/02bgpcq9/UML.png)](https://postimg.cc/svd0zPXL)
[![MODELO-RELACIONAL.png](https://i.postimg.cc/GhkfPN5w/MODELO-RELACIONAL.png)](https://postimg.cc/bswLp6P3)


---

## Objetivo
1. Criar uma lista de jogos vertical com títulos, descrição curta e descrição longa exibida quando o usuário clicar em um jogo.
2. Permitir que o usuário clique em um jogo e arraste para alterar sua posição na lista.

---

## Perfis de Projeto

### Perfil de desenvolvimento de testes do projeto
- `test`
- Banco de dados: H2

### Perfil de homologação / staging
- `dev`
- Banco de dados: PostgreSQL de homologação

### Perfil de produção
- `prod`
- Banco de dados: PostgreSQL de produção

---

## Preparação do Ambiente

### Utilizando Docker
1. Configurar container Docker para PostgreSQL.

### Utilizando PostgreSQL + pgAdmin ou DBeaver
1. Instalar e configurar PostgreSQL localmente.
2. Configurar pgAdmin ou DBeaver para gerenciar o banco de dados.

---

## Homologação Local

1. Criar perfis de projeto:
   - Adicionar configurações ao arquivo `system.properties`.
2. Gerar script da base de dados:
   - Apagar o arquivo gerado automaticamente após validação.
3. Criar base de dados de homologação.
4. Rodar o aplicativo no modo `dev` e validar o funcionamento.



---

## [Meu Linkedin](https://www.linkedin.com/in/alexsandro-j-a-almeida/)
