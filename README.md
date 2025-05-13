# MongoDB CRUD Project

Este é um projeto de exemplo com Node.js, Express e MongoDB utilizando Mongoose para realizar operações CRUD de usuários.

## 🚀 Tecnologias

- Node.js
- Express
- MongoDB + Mongoose
- Dotenv
- Nodemon (para dev)

## 🧱 Estrutura

```
mongodb-crud-project/
├── models/
│   └── User.js
├── routes/
│   └── userRoutes.js
├── .env
├── .gitignore
├── package.json
├── server.js
```

## 📦 Instalação

```bash
git clone https://github.com/seuusuario/mongodb-crud-project.git
cd mongodb-crud-project
npm install
```

Crie o arquivo `.env` com:

```
PORT=3000
MONGO_URI=mongodb://localhost:27017/mongodb_crud
```

## ▶️ Executando

```bash
npm run dev
```

## 🧪 Testando as rotas

Use o Postman ou Insomnia para testar as rotas:
- `POST /api/users`
- `GET /api/users`
- `GET /api/users/:id`
- `PUT /api/users/:id`
- `DELETE /api/users/:id`

---
Feito por Haridade 💚 para você!
