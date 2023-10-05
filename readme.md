

# Next.js App Router Playground
<img width="1419" alt="Screenshot 2023-10-05 at 1 25 37 AM" src="https://github.com/sudo-self/Playground/assets/119916323/6bc3d1f9-3ecf-49da-88dc-da6206d67bb3">

Next.js recently introduced the App Router with support for:

- **Layouts:** Easily share UI while preserving state and avoiding re-renders.
- **Server Components:** Making server-first the default for the most dynamic applications.
- **Streaming:** Display instant loading states and stream in updates.
- **Suspense for Data Fetching:** `async`/`await` support and the `use` hook for component-level fetching.

The App Router can coexist with the existing `pages` directory for incremental adoption. While you **don't need to use the App Router** when upgrading to Next.js 13, we're laying the foundations to build complex interfaces while shipping less JavaScript.

## Running Locally

1. Install dependencies:

```sh
pnpm install
```

2. Start the dev server:

```sh
pnpm dev
```

## Documentation

https://nextjs.org/docs
