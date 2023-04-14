astro-html-terser
===

Astro plugin to minify HTML by using Terser

Usage
---

Install dependencies into your Astro site

```
pnpm add -D astro-html-terser
```

Then add into your Astro config file

```js
import html from 'astro-html-terser'

export default defineConfig({
  integrations: [
    html()
  ]
})
```
