# vue-cli-tailwind-boilerplate

Boilerplate project with Vue CLI and Tailwind CSS integration.

## Commands used to generate this boilerplate

Scaffolded a development environment with Vue CLI:

```
vue create vue-cli-tailwind-boilerplate
```

Installed Tailwind CSS:

```
npm install tailwindcss
```

Created style.css file and imported Tailwind:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Created file postcss.config.js and added:

```js
module.exports = {
    plugins: [
        require('tailwindcss'),
        require('autoprefixer')
    ]
}
```

Deleted postcss entry from package.json

```json
  "postcss": {
    "plugins": {
      "autoprefixer": {}
    }
  },
```

### Compiles and hot-reloads for development
```
npm install -g @vue/cli-service-global
```
```
npm run serve
```
