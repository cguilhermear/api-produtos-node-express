# API de Produtos com Node.js e Express

API REST simples para gerenciamento de produtos, desenvolvida com **Node.js** e **Express**.  
O projeto implementa um CRUD completo e demonstra conceitos importantes de backend como **middlewares**, **modularização** e **estruturação de rotas**.

---

## 🚀 Tecnologias utilizadas

- Node.js
- Express.js
- body-parser
- Postman (para testes de endpoints)

---

## 📁 Estrutura do projeto


projeto
└ src
├ servidor.js
└ bancoDeDados.js


- **servidor.js** → configuração do servidor, rotas e endpoints da API  
- **bancoDeDados.js** → lógica de armazenamento e manipulação dos produtos

---

## 📦 Endpoints da API

### Listar produtos


GET /produtos


Resposta:

```json
[
  {
    "id": 1,
    "nome": "Notebook",
    "preco": "1259.99"
  }
]
Buscar produto por ID
GET /produtos/:id
Criar produto
POST /produtos

Body:

{
  "nome": "Notebook",
  "preco": 1259.99
}
Atualizar produto
PUT /produtos/:id

Body:

{
  "nome": "Notebook atualizado",
  "preco": 1399.99
}
Remover produto
DELETE /produtos/:id
▶️ Como executar o projeto

Clone o repositório:

git clone https://github.com/cguilhermear/api-produtos-node-express.git

Entre na pasta do projeto:

cd api-produtos-node-express

Instale as dependências:

npm install

Execute o servidor:

node projeto/src/servidor.js

O servidor iniciará em:

http://localhost:3003
📌 Objetivo do projeto

Este projeto foi desenvolvido com foco em revisão e aprofundamento de fundamentos de APIs REST com Node.js, reforçando conceitos essenciais de backend antes de evoluir para arquiteturas mais complexas com banco de dados e camadas de serviço.

👨‍💻 Autor

Carlos Guilherme
