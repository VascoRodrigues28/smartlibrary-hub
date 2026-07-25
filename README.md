# SmartLibrary Hub

Plataforma full-stack de gestão de biblioteca, desenvolvida no âmbito da unidade curricular de Programação para a Web.

## ✨ Funcionalidades
- Autenticação e autorização com JWT
- Controlo de acessos por perfil (RBAC): administrador, funcionário, utilizador
- Gestão de empréstimos e devoluções de livros
- Cálculo e gestão de multas por atraso
- Reserva de espaços (salas de estudo)

## 🛠️ Stack técnica
- **Frontend:** React 18
- **Backend:** Node.js, Express
- **Base de dados:** MongoDB
- **Autenticação:** JWT

## 🚀 Como correr o projeto localmente

```bash
# clonar o repositório
git clone https://github.com/VascoRodrigues28/smartlibrary-hub.git
cd smartlibrary-hub

# backend
cd backend
npm install
npm run dev

# frontend (noutro terminal)
cd frontend
npm install
npm start
```

Cria um ficheiro `.env` no backend com as variáveis necessárias (ligação à MongoDB, secret do JWT, etc.), ver `.env.example`.

## 📸 Screenshots
_(adicionar aqui 2-3 capturas de ecrã da aplicação: login, dashboard, gestão de empréstimos)_

## 📚 Contexto académico
Projeto desenvolvido para a unidade curricular de Programação para a Web, no CTeSP de Programação para Web e Dispositivos Móveis (ESTG/IPP).