# Best Svelte + TailwindCSS template

Another Svelte + TailwindCSS template, but this time it doesn't suck

## Features

- Bundled with Webpack 5
- `@apply` and friends working in svelte component's style tags, `lang=postcss` is not required
- Same in `.pcss` files
- Hot module replacement
- Sane reload times - 350 avg ms for Tailwind in components, 250 avg ms for regular component css. Tested on Ryzen 2500u capped at 2GHz
- Uses `@tailwindcss/jit` to get really good performance (thanks to WindiCSS and Girouette)


## Installation

### NPM

```bash
npm install
npm run dev

npm run build
```


## Improve this template

Let me know what's missing. This is absolute minimum that should be in any Svelte + TailwindCSS project, but it can be extended with other stuff.

# License

MIT
