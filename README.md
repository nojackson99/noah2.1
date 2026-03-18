# noah2.1

Turborepo monorepo for the noah2.1 project.

## Structure

```
apps/
  web/          # Next.js app (App Router)
packages/
  core/         # Shared AI/backend logic (@noah/core)
  eslint-config/       # Shared ESLint config
  typescript-config/   # Shared tsconfig
```

## Prerequisites

- [Node.js](https://nodejs.org/) v18+
- [pnpm](https://pnpm.io/) v9+ — install with `npm install -g pnpm`

## Setup

```sh
pnpm install
```

## Development

```sh
pnpm dev
```

Starts the Next.js app at [http://localhost:3000](http://localhost:3000).

## Other commands

```sh
pnpm build      # Build all apps and packages
pnpm lint       # Lint all apps and packages
```
