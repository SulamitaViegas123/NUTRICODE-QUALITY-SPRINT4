# 🥗 NutriCode - Sprint 4 | Compliance & Quality Assurance

---

# 🎯 Objetivo

Este projeto tem como objetivo validar e garantir a qualidade da aplicação NutriCode utilizando testes manuais e automatizados.

A aplicação foi desenvolvida com Spring Boot e Oracle Autonomous Database, permitindo operações relacionadas ao gerenciamento de alimentos e categorias nutricionais.

---

# 🖥️ Tecnologias Utilizadas

- Java
- Spring Boot
- Maven
- Oracle Autonomous Database (OCI)
- Azure Boards
- Postman
- GitHub

---

# 🗂️ Estrutura do Projeto

```text
NUTRICODE-QUALITY-SPRINT4
│
├── postman/
├── evidencias/
├── src/
├── pom.xml
└── README.md
```
## 🔒 Segurança

As credenciais sensíveis da aplicação não ficam expostas diretamente no código-fonte, sendo armazenadas por meio de configurações seguras da aplicação e ambiente.

---

# 🧪 Parte A — Testes Manuais

Os testes manuais foram documentados no Azure Boards contendo:

- Casos de teste;
- Dados de entrada;
- Dados de saída esperados;
- Procedimentos de execução;
- Dados controlados para validação.

## 🔹 Casos de Teste

- CT-01 — Listar alimentos cadastrados
- CT-02 — Cadastrar alimento com dados válidos
- CT-03 — Excluir alimento por ID
- CT-04 — Listar categorias cadastradas
- CT-05 — Cadastrar categoria com dados válidos
- CT-06 — Excluir categoria por ID
- CT-07 — Validar persistência de alimento no banco
- CT-08 — Validar persistência de categoria no banco

---

# 🧪 Parte B — Testes Automatizados

Os testes automatizados foram realizados utilizando Postman.

## 🔹 Testes Automatizados Implementados

### GET /alimentos
Validação da listagem de alimentos cadastrados.

### POST /alimentos
Validação do cadastro de alimentos.

### GET /categorias
Validação da listagem de categorias.

### POST /categorias
Validação do cadastro de categorias.

---

# 🧩 Endpoints da API

## 🍎 Alimentos

```http
GET /alimentos
POST /alimentos
DELETE /alimentos/{id}
GET /alimentos/{id}
```

## 🗂️ Categorias

```http
GET /categorias
POST /categorias
DELETE /categorias/{id}
GET /categorias/{id}
```

---

# 🚀 Execução do Projeto

## 🔹 Rodar aplicação Spring Boot

```bash
mvn spring-boot:run
```

A aplicação ficará disponível em:

```text
http://localhost:8080
```

---

# 🧾 Evidências

As evidências dos testes encontram-se na pasta:

```text
evidencias/
```

---

# 🔄 Automação Postman

A collection utilizada nos testes automatizados encontra-se em:

```text
postman/
```

---

# 💾 Repositório GitHub

Branch utilizada para entrega:

```text
develop
```

# 👥 Integrantes

| RM | Nome |
|---|---|
| RM560914 | Lucas Siqueira de Almeida |
| RM561090 | Matteus Viegas dos Santos |
| RM561089 | Sulamita Viegas dos Santos |
