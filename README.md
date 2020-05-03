# Learning Sapper

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Sapper is a web app dev framework powered by [Svelte](https://github.com/hchiam/learning-svelte).

From <https://sapper.svelte.dev/docs#Getting_started>:

## Quick and suggested setup

```bash
npx degit "sveltejs/sapper-template#rollup" my-app
# or: npx degit "sveltejs/sapper-template#webpack" my-app
cd my-app
npm install # or: yarn
npm run dev # or: yarn dev
```

The template comes with [Cypress](https://github.com/hchiam/learning-cypress) tests [set up](https://github.com/sveltejs/sapper-template/blob/master/cypress/integration/spec.js) for use with `npm test`

## Export to static site hosting

To prep files for static site hosting:

```bash
npx sapper export
# you'll see stuff inside: __sapper__/export
surge __sapper__/export https://hchiam-sapper-demo.surge.sh
```

See <https://hchiam-sapper-demo.surge.sh>

## Debugging server code

[ndb](https://github.com/GoogleChromeLabs/ndb) is suggested for debugging server code:

```bash
npm install -g ndb
# and then run Sapper
ndb npm run dev # or ndb npx sapper dev
```
