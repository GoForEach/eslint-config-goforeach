# D1D2 Apps ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Import Helpers plugin;
- Unused Imports plugin;
- TailwindCSS plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @d1d2-apps/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@d1d2-apps/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @d1d2-apps/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@d1d2-apps/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @d1d2-apps/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@d1d2-apps/eslint-config/node"
}
```

### NestJS

Install dependencies:
```
npm i -D eslint @d1d2-apps/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@d1d2-apps/eslint-config/nest"
}
```
