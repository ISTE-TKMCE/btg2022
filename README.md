# btg2022
frontend btg 2022 initial setup
1. npm install postcss --save-dev
2. npm install tailwindcss
3. npx tailwind init
# Tailwind utility classes are generated on demand when you actually use them in your code. So you need to tell Tailwind where to search for those utilities inside your project. Open the tailwind.config.js file and replace its content with the following:
 (// module.exports = {
 content: ['./src/**/*.{html,ts}', './projects/**/*.{html,ts}'],
 theme: {
   extend: {},
 },
 plugins: [],
}; //)

5. add in style.css @tailwind base;
@tailwind components;
@tailwind utilities;
