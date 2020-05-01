# nuxt-vuex-persist-shared-mutations-example

> Example static nuxt SPA with **vuex store** featuring 
> - store **persisted client-side** 
> - mutations **shared between tabs/windows**.

## Live Preview

[Preview here](https://hartmut-co-uk.github.io/nuxt-vuex-persist-shared-mutations-example/)

## Libraries Used :trophy:

Everything built with an out of the box combination of **Nuxt** (+ vuex) + **vuex-persist** + **vuex-shared-mutations**.   
vuex-persist + vues-shared-mutations added as nuxt [plugins](plugins).

All credits go to:
- https://github.com/championswimmer/vuex-persist
- https://github.com/xanf/vuex-shared-mutations
- Last but not least.. [Vue.js](https://vuejs.org/) + [Nuxt.js](https://nuxtjs.org/)

## Build Setup

```bash
# install dependencies
$ yarn

# serve with hot reload at localhost:3000
$ yarn dev

# generate static project
$ yarn generate

# generate static for GitHub Pages
$ yarn generate:gh-pages

# deploy `dist` folder for GitHub Pages (branch 'gh-pages')
$ yarn deploy:gh-pages
```

## Deployment: Github Actions > Github Pages

:muscle: This repo has been setup for fully automated deployment of the [Live Preview](https://hartmut-co-uk.github.io/nuxt-vuex-persist-shared-mutations-example/) via *Github Actions* as *Github Pages*.

For details, check following files + references below:   
`nuxt.config.js` -> `routerBase`   
`package.json` -> scripts `generate:gh-pages` + `deploy:gh-pages`   
`.github/workflows/gh-pages-deploy.yml`   
   
### Credits

- https://nuxtjs.org/faq/github-pages/
- https://github.com/L33T-KR3W/push-dir

### References Github :octocat: :sparkles: 

- https://pages.github.com/   
- https://github.com/features/actions   
