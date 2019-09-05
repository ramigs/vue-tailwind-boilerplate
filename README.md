# vue-cli-tailwind-boilerplate

## Commands used to generate this boilerplate

Scaffolding a nice dev environment with Vue CLI:

```
vue create vue-cli-tailwind-boilerplate
```

Installing Tailwind CSS:

```
npm install tailwindcss
```

Create style.css file and import Tailwind:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Create file postcss.config.js and add:

```js
module.exports = {
    plugins: [
        require('tailwindcss'),
        require('autoprefixer')
    ]
}
```

Deleting postcss entry from package.json

### Compiles and hot-reloads for development
```
npm install -g @vue/cli-service-global
```
```
npm run serve
```
