# Hello NextJS

Reference: <https://www.apollographql.com/blog/apollo-client/next-js/next-js-getting-started/>

## Note

This project demonstrates a simple SSR and Apollo implementation.

Goals:

- Check that the static page is returned in the page source
- Check that re-hydration happens to load
- Check that the payload correlates with SSG, SSR and CSR pages (refer to Demo section below).

## Quick start

```bash
yarn dev
```

Development build (default `localhost:3000`); Page is regenerated on every reload.

```bash
yarn build
yarn start

# run production on another port
yarn start -p 3001
```

Build server-side static pages and run in production.

## Demo

Open the following pages in browser:

- `localhost:3000` - static page (`2.3kb` initial render, `665b` cached)
- `localhost:3000/server-side` - SSR page (`2.3kb`)
- `localhost:3000/client-side` - CSR page (`5.3kb`)
