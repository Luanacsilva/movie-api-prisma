# 🎬 movie-api-prisma — API RESTful com TypeScript, Express e Prisma

API desenvolvida em **TypeScript** com **Node.js**, utilizando o framework **Express** e o ORM **Prisma**, para gerenciamento de um catálogo de filmes.

Este projeto demonstra a implementação de um **CRUD completo**, com estrutura organizada, tipagem segura e práticas modernas de desenvolvimento backend.

---

![stack: backend](https://img.shields.io/badge/stack-backend-blue)
![language: TypeScript](https://img.shields.io/badge/language-TypeScript-blue)
![framework: Express](https://img.shields.io/badge/framework-Express-lightgrey)
![ORM: Prisma](https://img.shields.io/badge/ORM-Prisma-2D3748)
![DB: PostgreSQL](https://img.shields.io/badge/database-PostgreSQL-336791)
![status: funcional](https://img.shields.io/badge/status-funcional-brightgreen)
![license: MIT](https://img.shields.io/badge/license-MIT-green)

---

## 🚀 Funcionalidades

- 📄 Listagem de filmes
- 🔍 Busca por ID
- ✍️ Cadastro de novos filmes
- 📝 Atualização de informações
- ❌ Remoção de registros
- ✅ Validação de dados com schemas dedicados
- 🔒 Tipagem com TypeScript
- 📂 Arquitetura modular

---

## 🛠️ Tecnologias Utilizadas

- **Node.js** + **Express**
- **TypeScript**
- **Prisma ORM**
- **PostgreSQL**
- **Zod ou Yup** (caso haja validação de schema)
- **Insomnia/Postman** para testes

---

## 📁 Estrutura do Projeto

```bash
movie-api-prisma/
├── prisma/ # Schema do banco + migrations 
 └── schema.prisma
├── src/ 
├── config/ # Configuração do Prisma 
├── http/ # Camada HTTP 
├── controllers/ # Lógica das rotas 
│ └── routes/ # Endpoints 
├── schema/ # Validação de dados
│ └── index.ts # Entry point
├── package.json
├── tsconfig.json
└── .gitignore
```

---

## ▶️ Como Executar o Projeto

### Pré-requisitos:
- Node.js
- PostgreSQL instalado e rodando
- `.env` configurado com sua string de conexão

### Passos:

```bash
# Clone o repositório
git clone https://github.com/Luanacsilva/movie-api-prisma
cd movie-api-prisma
```
# Instale as dependências
```bash
npm install
```
# Rode as migrations do banco
```bash
npx prisma migrate dev
```
# Inicie o servidor
```bash
npm run dev
```
---

## 📬 Endpoints


| Método | Rota           | Descrição              |
|--------|----------------|------------------------|
| GET    | `/movies`      | Listar todos os filmes |
| GET    | `/movies/:id`  | Buscar filme por ID    |
| POST   | `/movies`      | Criar novo filme       |
| PUT    | `/movies/:id`  | Atualizar um filme     |
| DELETE | `/movies/:id`  | Deletar um filme       |

---

## 🧑‍💻 Autora

Luana Cristina da Silva

---

##⚖️ Licença

MIT License




