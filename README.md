# zaruba.email

Personal website, built with [Astro](https://astro.build) and served by Cloudflare Pages.

- Content: `src/data/*.ts` (links, publications, talks, chips) and `src/pages/` (any `.md`/`.astro` file becomes a page).
- Local: `npm install`, `npm run dev`.
- Deploy: push to `master`; Cloudflare Pages runs `npm run build` and serves `dist/` (Node version in `.node-version`).
- The email link is protected by Cloudflare Email Address Obfuscation on the live domain.
