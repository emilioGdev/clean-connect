# Clean Connect

**Clean Connect** é uma aplicação full stack composta por um backend em **Node.js (Fastify)** e um frontend mobile em **React Native (Expo)**. Seu propósito é conectar prestadores de serviço (como faxineiros) a clientes, permitindo o gerenciamento de contratos, produtos, postagens e perfis de usuários.

---

## ✨ Funcionalidades

### Backend (Fastify + Node.js)
- Cadastro e gerenciamento de:
  - Fornecedores
  - Lojas
  - Produtos
  - Faxineiros
  - Postagens
  - Serviços
  - Contratos
- Suporte a CORS
- API REST modularizada por rotas

### Frontend (React Native + Expo)
- Autenticação (Login e Registro)
- Cadastro de produtos e serviços
- Criação de postagens
- Navegação com React Navigation (Stack)

---

## 🚀 Tecnologias

| Backend | Frontend |
|--------|---------|
| Node.js + Fastify | React Native (Expo) |
| TypeScript/JavaScript | React Navigation |
| @fastify/cors | Expo Stack |
| Modular Routing | Styled Components (opcional) |

---

## 📂 Estrutura do Projeto

```
clean-connect/
├── backend/
│   ├── routes/
│   │   ├── fornecedorRoutes.js
│   │   ├── lojaRoutes.js
│   │  
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── screens/
│   │   ├── routes/
│   │
│   └── App.js
├── README.md
└── ...
```

---

## ⚙️ Como rodar o projeto

### 📥 Clone o repositório

```bash
git clone https://github.com/emilioGdev/clean-connect.git
cd clean-connect
```

### 🔧 Backend

1. Vá para a pasta do backend:
   ```bash
   cd backend
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Inicie o servidor:
   ```bash
   npm start
   ```

> O servidor escutará na porta `3333` ou definida pela variável `PORT`.

### 📱 Frontend (Expo)

1. Vá para a pasta do frontend:
   ```bash
   cd frontend
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Rode o app com Expo:
   ```bash
   npx expo start
   ```

> Escaneie o QR code com o aplicativo Expo Go.

---

## 📌 Requisitos

- Node.js ≥ 16
- Expo CLI (opcional): `npm install -g expo-cli`
- Emulador Android/iOS ou celular com **Expo Go**
