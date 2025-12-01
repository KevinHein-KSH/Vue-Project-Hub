# 🌐 Vue Project Hub  
Multi-project Vue 3 playground (Blog + Weather + more)
A collection of small Vue applications built inside one unified project.

## 🚧 Status: Under Development
This project is actively being built. Additional features, pages, and apps will be added as the project grows.

## 📌 What to Expect
This repository acts as a central hub containing multiple mini-apps, such as:

- 📝 Blog App  
- ☁️ Weather App  
- 🔧 More feature apps coming soon  

All apps are organized under one Vue project using a modular architecture.

## 🧰 Tech Stack
- Vue 3 (Composition API)  
- TypeScript  
- Vite  
- Tailwind CSS  
- Vue Router  
- Organized `/views`, `/features`, and `/components` structure  

Future improvements may include:
- UI component library (shadcn-vue or Vuetify)  
- State management with Pinia  

## 🎓 Inspiration

This project takes reference and inspiration from [**The Net Ninja**](https://www.youtube.com/c/TheNetNinja) Vue and Tailwind tutorials on YouTube.

#
This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Vue (Official)](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Recommended Browser Setup

- Chromium-based browsers (Chrome, Edge, Brave, etc.):
  - [Vue.js devtools](https://chromewebstore.google.com/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd) 
  - [Turn on Custom Object Formatter in Chrome DevTools](http://bit.ly/object-formatters)
- Firefox:
  - [Vue.js devtools](https://addons.mozilla.org/en-US/firefox/addon/vue-js-devtools/)
  - [Turn on Custom Object Formatter in Firefox DevTools](https://fxdx.dev/firefox-devtools-custom-object-formatters/)

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```