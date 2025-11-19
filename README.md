# Estudo de Caso - Rotas Web e Mobile

Projeto com **React (Vite)** e **React Native (Expo)** mostrando rotas entre telas.

## 🖥️ Web
- `npm create vite@latest web --template react`
- `npm install react-router-dom`
- `npm run dev`

Rotas:
- `/` → lista de produtos
- `/product/:id` → detalhes do produto

## 📱 Mobile
- `expo init mobile`
- `npm install @react-navigation/native @react-navigation/native-stack`
- `npx expo start`

Rotas:
- `Home` → lista de produtos
- `Details` → detalhes do produto
