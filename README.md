# 85_ESE_microservices

# Trabalho 1: Arquitetura de Microserviços

## Definição de Escopo da Aplicação

- Permitir a criação de 4 microserviços:
  - 1 Microserviço para Autenticação
  - 1 Microserviço como API Gateway
  - 2 Microserviços adicionais (a serem definidos)

## Especificação/Análise da Aplicação

### Formato da Especificação

- **Casos de Uso**: Documentar os principais casos de uso da aplicação.
- **Casos de Uso 2.0**: Detalhamento avançado dos casos de uso.
- **Histórias de Usuário**: Descrição das funcionalidades sob a perspectiva do usuário.

### Ferramenta de ALM

- Ferramentas sugeridas: Jira, Trello, Tuleap, GitLab.

### Planejamento do Desenvolvimento

- Adicionar backlog na ferramenta de ALM escolhida.

## Definição dos Serviços

### Documentar

- **Servidor de Autenticação**: Definir e documentar o serviço responsável pela autenticação de usuários.
- **API Gateway ou Mensageria**:
  - **API Gateway**: Centraliza o acesso aos microserviços.
  - **Mensageria**: Utilizar Kafka ou RabbitMQ para comunicação entre microserviços.

## Definição da Arquitetura

### ADRs (Architectural Decision Records)

- Documentar pelo menos 3 ADRs relacionados às decisões arquiteturais.

### Estilo de Arquitetura

- **Estilo Arquitetural Principal**: Microservices ou FaaS (Functions as a Service).

### Estrutura da Aplicação

- **Estilo Arquitetural Principal**: Definir um estilo arquitetural principal.
- **Padrões Arquiteturais**: Utilizar pelo menos 1 padrão arquitetural para os microserviços:
  - Layered
  - Clean/Onion
  - DDD (Domain-Driven Design)
  - Hexagonal
  - MVVM (Model-View-ViewModel)

- **SOLID**: Apontar o uso dos princípios SOLID na arquitetura.

### Boas Práticas

- Identificar e aplicar boas práticas de desenvolvimento e arquitetura.

### Padrões de Projeto (GoF)

- Utilizar 3 padrões de projeto do livro "Gang of Four" (GoF).

### Padrões de Comunicação

- Definir os padrões de comunicação entre microserviços:
  - REST
  - SOAP
  - GraphQL
  - gRPC
  - WebSockets
  - Webhooks
  - CQRS (Command Query Responsibility Segregation)

### Ferramentas de Testes

- Definir ferramentas de testes apropriadas para a arquitetura selecionada.
- **Métrica de Cobertura de Teste**: Definir uma métrica de cobertura de teste, por exemplo, 80%.

### Arquitetura de Microserviços

- **Docker Compose**: Criar e documentar a arquitetura de microserviços utilizando Docker Compose.

