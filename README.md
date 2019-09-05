# vue-cli-tailwind-boilerplate

## Commands used to generate the project structure

1. Scaffolding a nice dev environment with Vue CLI:

```
vue create vue-cli-tailwind-boilerplate
```

1. Installing Tailwind CSS:

```
npm install tailwindcss
```

1. Creating file postcss.config.js and add:

```js
module.exports = {
    plugins: [
        require('tailwindcss'),
        require('autoprefixer')
    ]
}
```

1. Deleting postcss entry from package.json

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
