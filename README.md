# Nextjs on STACKIT Cloud Foundry SCF

This repo was bootstrapped with `npx create-next-app@latest nextjs-scf1 --yes`

What has been added is the `manifest.yml` file and a few changes to `package.json`.
Inspect the Git log for infos.

## General getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deploy on SCF

Run `cf push nextjs-scf1 -b https://github.com/cloudfoundry/nodejs-buildpack`

Works.
