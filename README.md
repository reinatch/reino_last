# Reinatch portfolio prototype

A portfolio interface built with Next.js 15, React 19, TypeScript, and Tailwind CSS. The App Router entry point is `src/app/`, components live in `src/components/`, and project/about entries are defined in `src/data/projects.ts`.

## Status

This checkout has not been confirmed as the source of [Rei's live portfolio](https://reinatch.website). Its project list, copy, imagery, and metadata differ from the live page. Some entries contain placeholder images and unverified descriptions, so they should not be used as evidence of project roles, technologies, dates, or client work.

Before replacing project content or deploying this checkout, establish the deployment repository and revision, then use owner-approved project facts and assets. The existing design and project entries are preserved pending that confirmation.

## Local development

Install dependencies with pnpm:

```sh
pnpm install --frozen-lockfile
pnpm dev
```

Open `http://localhost:3000`. `pnpm lint` runs ESLint. `pnpm build` runs the Next.js production build with Turbopack; `pnpm start` serves that build. The configuration in this checkout does not enable static export. Fonts configured through `next/font/google` require Google Fonts access at build time.

The GitHub Pages workflow is separate from the current application configuration and needs verification before deployment. No deployment is triggered by these local instructions.
