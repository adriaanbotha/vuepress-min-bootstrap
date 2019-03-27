# Quick Setup of a default VuePress Example

## Project setup
```html
copy the docs folder to your project

```
add the docs lines from the package.json in this folder to your proejct

    "docs:dev": "vuepress dev docs",
    "docs:build": "vuepress build docs"

### To Run
```bash
yarn install
yarn run docs:dev
```

###To Build Static
```bash
yarn run docs:build
```

Copy the static generated directory or serve it from docs/.vuepress/dist
