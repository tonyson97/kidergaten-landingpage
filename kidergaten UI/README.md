# Kindergarten UI

Welcome to the Kindergarten UI template! This project is designed to help you kickstart your development journey with Vue 3 and Vite.

## Recommended IDE Setup

For an optimal development experience, we recommend using [Visual Studio Code (VSCode)](https://code.visualstudio.com/) along with the [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) extension. Make sure to disable Vetur to avoid any potential conflicts.

## Type Support for `.vue` Imports in TypeScript

By default, TypeScript does not support type information for `.vue` imports. To address this, we utilize `vue-tsc` in place of the standard `tsc` CLI for accurate type checking. Additionally, the [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) extension is essential for enabling the TypeScript language service to recognize `.vue` types in your editor.

## Customizing Configuration

For detailed information on configuration options, please refer to the [Vite Configuration Reference](https://vite.dev/config/).

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

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
