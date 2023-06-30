# Vite 2.x + Vue 3.x + TypeScript Starter

[![Author](https://img.shields.io/badge/author-XPoet-orange.svg)](https://github.com/XPoet)
[![License](https://img.shields.io/github/license/XPoet/vite-vue3-starter.svg)](https://github.com/XPoet/vite-vue3-starter/blob/master/LICENSE)
[![Stars](https://img.shields.io/github/stars/XPoet/vite-vue3-starter)](https://github.com/XPoet/vite-vue3-starter)
[![Deploy](https://github.com/XPoet/vite-vue3-starter/workflows/deploy/badge.svg)](https://github.com/XPoet/vite-vue3-starter/actions/workflows/deploy.yml)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-Airbnb-hotpink.svg)](https://github.com/lin-123/javascript)


> A set of robust front-end rapid development templates that perfectly integrate Vite 2.x + Vue 3.x + TypeScript + Vue Router + Vuex + Axios + ESLint

## online preview

https://vite-vue3-starter.xpoet.cn/

## Build tutorial from 0 to 1

1️⃣&nbsp;[Nuggets](https://juejin.cn/post/6951649464637636622)&emsp;2️⃣&nbsp;[XPoet's Blog](https://xpoet.cn/2021/04/%E4%BB%8E-0-% E5%BC%80%E5%A7%8B%E6%89%8B%E6%8A%8A%E6%89%8B%E5%B8%A6%E4%BD%A0%E6%90%AD%E5% BB%BA%E4%B8%80%E5%A5%97%E8%A7%84%E8%8C%83%E7%9A%84-Vue3.x-%E5%B7%A5%E7%A8%8B %E5%8C%96%E9%A1%B9%E7%9B%AE/)


## technology stack

- Programming language: [TypeScript 4.x](https://www.typescriptlang.org/zh/) + [JavaScript](https://www.javascript.com/)
- Build tool: [Vite 2.x](https://cn.vitejs.dev/)
- Front-end framework: [Vue 3.x](https://v3.cn.vuejs.org/)
- Routing tool: [Vue Router 4.x](https://next.router.vuejs.org/zh/index.html)
- State management: [Vuex 4.x](https://next.vuex.vuejs.org/)
- UI framework: [Element Plus](https://element-plus.org/#/zh-CN)
- CSS precompilation: [Stylus](https://stylus-lang.com/) / [Sass](https://sass.bootcss.com/documentation) / [Less](http://lesscss.cn/ )
- HTTP Tools: [Axios](https://axios-http.com/)
- Git Hook tool: [husky](https://typicode.github.io/husky/#/) + [lint-staged](https://github.com/okonet/lint-staged)
- Code specification: [EditorConfig](http://editorconfig.org) + [Prettier](https://prettier.io/) + [ESLint](https://eslint.org/) + [Airbnb JavaScript Style Guide ](https://github.com/airbnb/javascript#translation)
- Commit specification: [Commitizen](http://commitizen.github.io/cz-cli/) + [Commitlint](https://commitlint.js.org/#/)
- Unit testing: [vue-test-utils](https://next.vue-test-utils.vuejs.org/) + [jest](https://jestjs.io/) + [vue-jest]( https://github.com/vuejs/vue-jest) + [ts-jest](https://kulshekhar.github.io/ts-jest/)
- Automatic deployment: [GitHub Actions](https://docs.github.com/en/actions/learn-github-actions)

## Quick start

### Get Items

#### Using Git

```sh
git clone https://github.com/XPoet/vite-vue3-starter.git
```

#### Using NPM

```sh
npm install vite-vue-ts-cli -g

vite-vue-ts-create myapp
```

### Install dependencies

```sh
npm install
# or
yarn add
```

### Startup project

```sh
npm run dev
```

### Project packaging

```sh
npm run build
```

##Q&A

1. Q: `git cz` does not take effect

    A: Please install commitizen globally, command: `npm install commitizen -g`

2. Q: husky reports an error

    A: Please check if there is a Git repository under your project, if not, initialize one with `git init` first

## License

MIT Copyright © 2021 XPoet