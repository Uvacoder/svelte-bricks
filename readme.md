<p align="center">
  <img src="public/favicon.svg" alt="Svelte Masonry" height=150>
</p>

# Svelte Masonry

This is a naive masonry implementation in Svelte without column balancing. [Live demo](https://svelte-masonry.netlify.app).

## Get started

1. Clone and install dependencies:

   ```sh
   git clone https://github.com/janosh/svelte-masonry
   cd svelte-masonry
   yarn
   ```

2. Start [Rollup](https://rollupjs.org):

   ```sh
   yarn dev
   ```

Navigate to <http://localhost:5000>. You should see this app running. Edit a component file in `src`, save it, and reload the page to see your changes.

## Building and running in production mode

To build and serve an optimized version of the app, run

```sh
yarn serve
```

This uses [sirv](https://github.com/lukeed/sirv), which is included in `package.json` `dependencies` so the app works when deployed to platforms like [Netlify](https://netlify.com).

## Deploying to Netlify

Install `netlify` if you haven't already:

```sh
yarn global add netlify
```

Then, from within this project's folder:

```sh
netlify deploy --prod
```

## Formatting

When using VS Code, install the [official Svelte extension](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode) and add the following to your `settings.json` to enable autoformating Svelte files on save:

```json
"[svelte]": {
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "svelte.svelte-vscode"
}
```

To get ESLint validation, also add

```json
"eslint.validate": ["svelte"]
```
