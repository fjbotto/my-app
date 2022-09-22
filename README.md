This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Reproduce the issue

1. Checkout
2. `npm install`
3. `npm run dev`

## Issue:

```bash
error - ./node_modules/@open-wa/wa-automate/dist/api/Client.js:55:0
Module not found: Can't resolve 'fs'

Import trace for requested module:
./node_modules/@open-wa/wa-automate/dist/index.js
./pages/index.js

https://nextjs.org/docs/messages/module-not-found

```