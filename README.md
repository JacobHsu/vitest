# quicktest-with-vitest

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
yarn
```

### Compile and Hot-Reload for Development

```sh
yarn dev
```

### Compile and Minify for Production

```sh
yarn build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
yarn test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
yarn lint
```


## pnpm test

[mount()](https://v1.test-utils.vuejs.org/api/mount.html)

 ```bash
 ✓ src/components/__tests__/NotificationToast.test.js (6)
   ✓ Notification component (6)
     ✓ renders the correct style for error
     ✓ renders correct style for success
     ✓ renders correct style for info
     ✓ slides up when message is empty
     ✓ emits event when close button is clicked
     ✓ renders correct message to viewer

 Test Files  1 passed (1)
      Tests  6 passed (6)
 ```