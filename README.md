# React + Vite
This is a "Host your Website" Project made using react + Vite using tailwind css.
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.
#SETUP On Your System
1: Create a TAILWIND (VITE) project by running the following commands:
npm create vite@latest
npm install
npm run dev
2: Open the TAILWIND documentation and go to Get Started page and install the TAILWIND using PostCSS. And follow the instructions afterward.
3: Do not forget to add "jsx" in the content section in "tailwind.config.js" file.
4: Also change "module.export" to export default in postcss.config.js file, otherwise you may get an error. 

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
