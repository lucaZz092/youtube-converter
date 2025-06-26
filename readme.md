# 🔐 Node Auth Backend

Este projeto é uma API simples de autenticação desenvolvida em **Node.js com Express**, utilizando **arquivos JSON como base de dados mock**.

Ideal para fins de aprendizado e prototipagem rápida.

---

## 📁 Estrutura do Projeto

```
meu-backend/
├── server.js                # Ponto de entrada da aplicação
├── routes/
│   └── auth.js              # Rotas de login e registro
├── controllers/
│   └── authController.js    # Lógica de autenticação
├── users.json               # Arquivo mock que armazena os usuários
```

---

## 🚀 Como executar o projeto

1. **Clone o repositório**
```bash
git clone https://github.com/seu-usuario/seu-repo.git
cd meu-backend
```

2. **Instale as dependências**
```bash
npm install express
```

3. **Inicie o servidor**
```bash
node server.js
```

4. Acesse:
```
http://localhost:3000/
```

---

## 📌 Rotas da API

### `POST /auth/register`

Registra um novo usuário.

**Body JSON:**
```json
{
  "email": "usuario@email.com",
  "senha": "123456"
}
```

### `POST /auth/login`

Realiza login do usuário.

**Body JSON:**
```json
{
  "email": "usuario@email.com",
  "senha": "123456"
}
```

---

## ✅ Funcionalidades

- Cadastro de usuários (sem criptografia)
- Login básico com validação
- Armazenamento simples em `users.json`

---

## 🔧 Melhorias Futuras

- Adicionar **criptografia** de senhas com `bcrypt`
- Utilizar **JWT** para autenticação
- Persistência real com **MongoDB** ou **PostgreSQL**
- Middleware de autenticação para proteger rotas

---

## 👨‍💼 Desenvolvido por

**Lucas Mendonça Martins**
