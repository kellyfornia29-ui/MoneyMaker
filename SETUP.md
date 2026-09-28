# 🚀 Guia de Configuração MoneyMaker

## ⚡ Inicio Rápido (5 minutos)

### 1️⃣ Backend (Servidor)

```bash
# Entre na pasta
cd backend

# Instale as dependências
npm install

# Rode o servidor
npm start
```

O servidor vai ficar em: `http://localhost:5000`

### 2️⃣ Frontend Web (Site)

```bash
# Nova aba do terminal
cd frontend-web

# Instale
npm install

# Rode o site
npm start
```

O site vai ficar em: `http://localhost:3000`

### 3️⃣ Mobile (App)

```bash
# Nova aba do terminal
cd mobile

# Instale
npm install

# Para Android
npm run android

# Para iOS (Mac)
npm run ios
```

---

## 📋 Pré-requisitos

Você precisa ter instalado:
- **Node.js** (https://nodejs.org/) - clique em LTS
- **npm** (vem com Node.js)
- **Git** (https://git-scm.com/)

---

## 🎯 O que cada pasta faz?

| Pasta | O que é |
|-------|---------|
| `backend/` | Servidor que fornece os dados |
| `frontend-web/` | Site que você acessa no navegador |
| `mobile/` | App para celular (Android/iOS) |

---

## 🔧 Troubleshooting

### "Porta já está em uso"
```bash
# Mude a porta no arquivo backend/server.js
# Linha: const PORT = process.env.PORT || 5001;
```

### "npm não encontrado"
Reinstale Node.js em https://nodejs.org/

### Backend não conecta com Frontend
Verifique se o backend está rodando:
```
http://localhost:5000/api/health
```

---

## 📱 Próximas Features

- ✅ Sistema de login
- ✅ Banco de dados de ideias
- ✅ Dashboard de ganhos
- ✅ Sistema de referência
- ✅ Gamificação

---

**Qualquer dúvida, me chama!** 💪
