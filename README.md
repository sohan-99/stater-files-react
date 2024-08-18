# React + Vite
//router-dom 

yarn create vite site-name --template react
cd site-name
yarn add react-router-dom localforage match-sorter sort-by

//tailwind setup

yarn add -D tailwindcss postcss autoprefixer
yarn run tailwindcss init -p


 content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],

//index.css///
@tailwind base;
@tailwind components;
@tailwind utilities;


yarn dev