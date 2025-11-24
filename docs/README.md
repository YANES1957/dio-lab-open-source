# 🔴 Beer API - Desafio DIO/Bradesco 

Este projeto é uma **API REST** de um fork para gerenciamento de estoques de cerveja, desenvolvida em **Spring Boot**, criada para demonstrar boas práticas de desenvolvimento de software, com foco em **testes unitários, testes de integração e TDD (Test-Driven Development)**.  

O objetivo é validar funcionalidades importantes da API, garantindo qualidade e confiabilidade do código, enquanto aprende e aplica conceitos de **testes avançados e automação**.

---

## 🛠 Funcionalidades da API

- Criar cervejas no estoque
- Listar todas as cervejas
- Consultar cervejas por nome
- Excluir cervejas do estoque

> Cada funcionalidade foi testada para garantir que a API funciona corretamente, mesmo quando submetida a diferentes cenários de uso.

---

## 📂 Estrutura do Projeto

```text
src/
├── main/
│   ├── java/
│   │   └── one.digitalinnovation.beerstock
│   │       ├── controller/   # Endpoints da API
│   │       ├── service/      # Lógica de negócio
│   │       ├── repository/   # Interfaces JPA
│   │       ├── model/        # Entidades do sistema
│   │       ├── mapper/       # MapStruct DTO <-> Entity
│   │       └── config/       # Configurações do Spring Boot
│   └── resources/
│       └── application.yml   # Configurações gerais
└── test/
    ├── java/
    │   ├── service/          # Testes unitários JUnit + Mockito
    │   └── bdd/              # Testes BDD com Cucumber
    └── resources/
        └── features/         # Features de teste (Cucumber)
🧪 Testes Implementados
O projeto possui testes unitários, testes de integração e testes automatizados, utilizando as principais ferramentas do mercado:

✅ JUnit
Framework de teste unitário para Java.

Permite criar e validar cenários de teste isolados, garantindo que cada função se comporte corretamente.

Exemplo: testar se uma cerveja foi criada corretamente ou se uma consulta retorna a cerveja certa.

✅ Mockito
Framework de mocking, utilizado para simular dependências em testes unitários.

Permite testar apenas a unidade de código, sem depender de outros componentes.

Exemplo: testar o serviço da cerveja sem acessar o banco de dados real.

✅ Cucumber
Framework para BDD (Behavior Driven Development).

Permite escrever cenários de teste legíveis, como "Dado, Quando, Então".

Exemplo: verificar o fluxo de criação de cervejas do ponto de vista do usuário.

✅ Uncrest / Automation
Ferramenta de teste automatizado de APIs.

Permite executar requisições HTTP e validar respostas.

Testes automatizados garantem que alterações no código não quebrem funcionalidades existentes.

✅ Testes Unitários e TDD
O TDD (Test-Driven Development) é uma prática onde primeiro escrevemos o teste, depois o código.

Isso garante que o código atenda aos requisitos antes mesmo de ser implementado.

No projeto, funcionalidades como criação, listagem, consulta e exclusão de cervejas foram desenvolvidas usando TDD, garantindo alta confiabilidade.

⚡ Objetivo dos Testes
Garantir que cada unidade de código funcione de forma isolada (testes unitários)

Garantir que os fluxos do sistema funcionem como esperado (testes de integração e BDD)

Automatizar testes para evitar regressões ao evoluir o código (automation)

Permitir desenvolvimento seguro e rápido, aplicando TDD para validar cada funcionalidade antes da implementação.

Em resumo: os testes garantem que a API funcione corretamente, de forma confiável, segura e documentada.

🔴 Tecnologias Utilizadas
Java 17

Spring Boot 3.5.7

Spring Data JPA

H2 Database (em memória)

Maven

MapStruct (mapeamento DTO <-> Entity)

JUnit 5 (testes unitários)

Mockito (simulação de dependências)

Cucumber (BDD)

Uncrest (teste de API automatizado)

📌 Como Rodar o Projeto
Pra clonar o repositório:

bash
Copiar código
git clone https://github.com/YANES1957/beer_api_digital_innovation_one_desafio_final_roberto.git
Entre na pasta do projeto:

bash
Copiar código
cd beer_api_digital_innovation_one_desafio_final_roberto
Build e run com Maven:

bash
Copiar código
mvn clean install
mvn spring-boot:run
Acesse a API via http://localhost:8080

📝 Autor
🔴 Roberto Cesar Yanes – GitHub YANES1957 🚀

