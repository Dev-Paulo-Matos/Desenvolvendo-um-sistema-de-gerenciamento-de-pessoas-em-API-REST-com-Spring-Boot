# 🧠 API REST – Sistema de Gerenciamento de Pessoas

API REST desenvolvida com **Spring Boot**, focada em demonstrar boas práticas de desenvolvimento backend, arquitetura limpa, padronização de APIs e integração com banco de dados.

Este projeto faz parte do meu portfólio técnico e foi pensado para apresentar de forma clara e profissional como construir um sistema backend completo, com persistência e recursos essenciais para serviços REST.

---

## 🔍 Visão Geral

O **Sistema de Gerenciamento de Pessoas** é uma API REST construída com Spring Boot que permite a criação, leitura, atualização e exclusão de registros de pessoas.  
O projeto demonstra conceitos fundamentais de backend, como:

- Arquitetura em camadas (Controller, Service, Repository)
- Modelagem de entidades e mapeamento ORM
- Uso de banco de dados relacional
- Endpoints REST padronizados
- Tratamento de erros
- Validação de dados

Esta API pode ser utilizada como base para sistemas maiores, integrações com frontends ou microserviços.

---

## 🛠️ Tecnologias Utilizadas

Esta API foi construída com as seguintes tecnologias:

- **Java 17**
- **Spring Boot**
  - Spring Web
  - Spring Data JPA
  - Spring Validation
- **Banco de Dados H2** (em memória)
- **Maven** para gerenciamento de dependências
- **Git** para versionamento

---

## 📦 Funcionalidades

A API oferece os seguintes recursos:

✔ Cadastro de pessoa  
✔ Listagem de todas as pessoas  
✔ Busca por ID  
✔ Atualização de dados  
✔ Exclusão de pessoa  
✔ Validações básicas de dados

---

## 🚀 Endpoints

| Método | Endpoint                    | Descrição                       |
|--------|---------------------------|----------------------------------|
| GET    | `/api/pessoas`             | Lista todas as pessoas         |
| GET    | `/api/pessoas/{id}`        | Retorna uma pessoa por ID      |
| POST   | `/api/pessoas`             | Cadastra uma nova pessoa       |
| PUT    | `/api/pessoas/{id}`        | Atualiza dados da pessoa       |
| DELETE | `/api/pessoas/{id}`        | Deleta uma pessoa por ID       |

---

## 📥 Requisições de exemplo

### ✔ POST — Criar Pessoa

```bash
POST /api/pessoas
Content-Type: application/json

{
  "nome": "Paulo Matos",
  "idade": 35,
  "email": "paulo@example.com"
}
```
## 💡 Boas Práticas Aplicadas

### Este projeto aplica alguns conceitos profissionais de backend:

✅ Separação de responsabilidades (Controller/Service/Repository)
✅ Uso de JPA para persistência de dados
✅ Validação com anotações (@Valid, @NotNull, etc)
✅ Tratamento de exceções
✅ Respostas e códigos HTTP padronizados (200, 201, 404, 400)

## 🛠️ Melhorias Futuras

### Este projeto pode ser ampliado com:

✔ Autenticação e autorização (JWT)
✔ Swagger para documentação
✔ Banco de dados real (MySQL, PostgreSQL)
✔ Testes unitários e de integração
✔ Paging & Sorting
✔ Filtros e buscas avançadas

## 📌 Observações

Este repositório serve como base de estudo e portfólio para vagas e projetos freelance, demonstrando:

✔ Capacidade de projetar e desenvolver APIs REST
✔ Conhecimento em Spring Boot e Java
✔ Organização de camadas e padrões arquiteturais
✔ Documentação clara e profissional

## 👨‍💻 Autor

Paulo Matos — Desenvolvedor Full Stack com 4 anos de experiência, atuando com Angular, React, Node.js, Spring Boot e Java, focado em soluções web completas e orientadas a negócio.

📫 Vamos conversar?
🔗 LinkedIn: https://www.linkedin.com/in/paulo-machado-34a0461b1

💻 GitHub: https://github.com/Dev-Paulo-Matos
