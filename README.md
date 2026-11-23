# Trailhead Storefront (Starter)

A small React storefront built with Vite. It renders a product catalog read from
`public/products.json`, and it already ships a GitHub Actions workflow that builds
it on every push.

## What Is Already Done

- `npm run build` produces a `dist/` folder of static HTML, CSS, and JavaScript.
- `.github/workflows/ci.yml` runs that build on GitHub's machines on every push.

## What Is Missing

The build output never leaves the runner. Nothing publishes `dist/` anywhere.

## Run It Locally

```bash
npm ci
npm run dev      # http://localhost:5173
npm run build    # writes dist/
```
