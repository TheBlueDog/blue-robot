# Project: Blue Robot


## Setting up Tailwind and PostCSS
- `npm init -y`
- `npm install tailwindcss postcss-cli autoprefixer`
- `npx tailwind init`
- `touch postcss.config.js`
- Add plugins require to `postcss.config` file
- Create new `css/tailwind.css` file
- Add `@tailwind base, components, utilities` to `tailwind.css`
- Add `build` script to `package.json` file
- Run `npm run build`
- Create `index.html`
- `npm install -g live-server`
- Run `live-server public`