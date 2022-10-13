[![Node.js CI](https://github.com/am1ru1/nextjs-base/actions/workflows/node.js.yml/badge.svg)](https://github.com/am1ru1/nextjs-base/actions/workflows/node.js.yml)
[![CodeQL](https://github.com/am1ru1/nextjs-base/actions/workflows/codeql.yml/badge.svg)](https://github.com/am1ru1/nextjs-base/actions/workflows/codeql.yml)

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

NextJS Template based on

1. Node locked to v16.x
2. Yarn locked and no npm
3. Configured ESLint to extend eslint:recommended and next
4. Prettier configured
5. Husky git hooks. Prepared install through Yarn Prepare.
6. Git Pre-commit with Lint
7. Git Pre-push with Build
8. Git commit-msg Lint with @commitlint/config-conventional. Refer to commitlint.config.js for accepted commit subjects.
9. VScode configured with Prettier and NextJS debug settings. Install https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode.
10. Directory structure with components and lib
11. GitHub codeql scan and dependabot

To consider for your own customization

1. Use Tailwind/MantineUI
2. Use Storybook. Then ESlint to extend "plugin:storybook/recommended".

Inspired by: https://github.com/alexeagleson/nextjs-fullstack-app-template

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
