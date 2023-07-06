npm init -y
npm i -D tailwindcss
npx tailwindcss init

content: ["./src/**/*.{html,js}],

src/input.css:
@tailwind base;
@tailwind components;
@tailwind utilities;

Run:
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
