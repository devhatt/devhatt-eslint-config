# Devhat ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:

```
npm i -D eslint @devhatt/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": [
    "@devhatt/eslint-config/next",
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:

```
npm i -D eslint @devhatt/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": "@devhatt/eslint-config/react"
}
```

### Node.js

Install dependencies:

```
npm i -D eslint @devhatt/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": "@devhatt/eslint-config/node"
}
```
