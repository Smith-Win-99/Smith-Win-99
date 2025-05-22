## Hi there 👋

<!--
**Smith-Win-99/Smith-Win-99** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
// Estrutura para projeto React com Vite e TailwindCSS

// package.json export const packageJson = { "name": "smith-win-99", "version": "1.0.0", "private": true, "scripts": { "dev": "vite", "build": "vite build", "preview": "vite preview" }, "dependencies": { "react": "^18.2.0", "react-dom": "^18.2.0" }, "devDependencies": { "vite": "^5.0.0", "@vitejs/plugin-react": "^4.0.0", "tailwindcss": "^3.3.0", "postcss": "^8.4.0", "autoprefixer": "^10.4.0" } };

// vite.config.js export const viteConfig = ` import { defineConfig } from 'vite'; import react from '@vitejs/plugin-react';

export default defineConfig({ plugins: [react()] }); `;

// tailwind.config.js export const tailwindConfig = module.exports = { content: ['./index.html', './src/**/*.{js,jsx}'], theme: { extend: {}, }, plugins: [], };;

// postcss.config.js export const postcssConfig = module.exports = { plugins: { tailwindcss: {}, autoprefixer: {}, }, };;

// index.html export const indexHtml = `

<!DOCTYPE html><html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Smith Win 99</title>
  </head>
  <body class="bg-green-100">
    <div id="root"></div>
    <script type="module" src="/src/main.jsx"></script>
  </body>
</html>
`;// src/main.jsx export const mainJsx = ` import React from 'react'; import ReactDOM from 'react-dom/client'; import App from './App'; import './index.css';

ReactDOM.createRoot(document.getElementById('root')).render( <React.StrictMode> <App /> </React.StrictMode> ); `;

// src/index.css export const indexCss = @tailwind base; @tailwind components; @tailwind utilities;;

// src/App.jsx (é o conteúdo do projeto já criado anteriormente) // O conteúdo já está atualizado e será salvo como App.jsx

