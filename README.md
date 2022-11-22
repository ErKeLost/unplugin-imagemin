📦📦          unplugin Picture compression


### ✨✨ Continuous iterative development in testing


## Install

```ts
pnpm install unplugin-imagemin -D
```


## Useage

```ts
import { defineConfig } from 'vite';
import vue from '@vitejs/plugin-vue';
import imagemin from 'unplugin-imagemin/vite';
// https://vitejs.dev/config/
export default defineConfig({
  plugins: [
    vue(),
    imagemin(),
  ],
});

```
