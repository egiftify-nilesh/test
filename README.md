# Nuxt 3 Minimal Starter

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install
```

## Development Server

Start the development server on `http://localhost:3000`

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.



# Nuxt POC's for Module to be used in Project

## @nuxt/image Module POC

Step 1. Add @nuxt/image as a dev-dependency using yarn : 

```bash
yarn add -D  @nuxt/image@rc
Note: rc is current version, so, it may change [ set accordingly ]
```


Step 2. Register @nuxt/image as a module in nuxt.config.ts : 

```bash
export default defineNuxtConfig({
    modules: [
        '@nuxt/image',
    ]
})
```
Note: rc is current version, so, it may change [ set accordingly ]


Check out the [Module Documentation](https://image.nuxtjs.org) for more information.