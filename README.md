# Learning Sapper

Just one of the things I'm learning. <https://github.com/hchiam/learning>

From <https://sapper.svelte.dev/docs#Getting_started>:

```bash
npx degit "sveltejs/sapper-template#rollup" my-app
# or: npx degit "sveltejs/sapper-template#webpack" my-app
cd my-app
npm install
npm run dev
```

The template comes with [Cypress](https://github.com/hchiam/learning-cypress) tests [set up](https://github.com/sveltejs/sapper-template/blob/master/cypress/integration/spec.js) for use with `npm test`

To prep files for static site hosting:

```bash
npx sapper export
```

[ndb](https://github.com/GoogleChromeLabs/ndb) is suggested for debugging server code:

```bash
npm install -g ndb
# and then run Sapper
ndb npm run dev # or ndb npx sapper dev
```
