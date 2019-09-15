# vue-tailwind-boilerplate

Boilerplate project for [Vue.js](https://vuejs.org/) and [Tailwind CSS](https://tailwindcss.com/) integration.

## Commands used to generate this boilerplate

Scaffolded project structure and development environment with command:

```
vue create vue-tailwind-boilerplate
```

Installed Tailwind CSS:

```
npm install tailwindcss
```

Created file `./assets/css/style.css` and imported Tailwind:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Created file `postcss.config.js` and added:

```js
module.exports = {
    plugins: [
        require('tailwindcss'),
        require('autoprefixer')
    ]
}
```

Deleted `postcss` entry from `package.json`

```json
  "postcss": {
    "plugins": {
      "autoprefixer": {}
    }
  },
```

## Compiles and hot-reloads for development
```
npm install -g @vue/cli-service-global
```
```
npm run serve
```
