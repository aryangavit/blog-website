# Steps followed while building

## 1. Setting Up Vite and Tailwind
`npm create vite@latest` then select 'React->Javascript'

`cd weather-app`
`npm install`
`npm run dev`
```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```
```
//tailwind.config.js
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
```
/* Adding Tailwind Directives to './src/index.css'
@tailwind base;
@tailwind components;
@tailwind utilities;
```
`npm run dev
`
## 2. 

1. Created a Template of what the blog is supposed to look like:
    <img width="500" alt="template-1 0" src="https://github.com/aryangavit/blog-website/assets/45901539/94dac9af-8d57-40e7-80fd-6b4d4b1eb40e">


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
