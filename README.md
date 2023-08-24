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

## 1. @nuxt/image Module POC

Step 1. Add @nuxt/image as a dev-dependency using yarn : 

```bash
yarn add -D  @nuxt/image@rc

# Note: rc is current version, so, it may change [ set accordingly ]
```

Step 2. Register @nuxt/image as a module in your nuxt.config.ts : 

```bash
export default defineNuxtConfig({
    modules: [
        '@nuxt/image',
    ]
})
```
Step 3. Set image global image configuration under image section in your nuxt.config: 

```bash
image: {
  // Options
}
```
See the [ image configuration ](https://image.nuxtjs.org/configuration) for all available options and features to customize.

## NOTE : In case for Error related to node-fetch-native or polyfills.mjs 
    ```bash
    # add this package to your project's package.json
    "node-fetch-native": "^1.4.0"
    ```

Step 4. Usage of nuxt-img and nuxt-picture tags in Project.

i). For nuxt-img follow  : [ nuxt-img Implementation ](https://image.nuxtjs.org/components/nuxt-img)

ii). For nuxt-picture follow : [ nuxt-picture Implementation ](https://image.nuxtjs.org/components/nuxt-picture)


Check out the [Module Documentation](https://image.nuxtjs.org) for more information.