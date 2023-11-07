# Nuxt 3.8.1 Router Warning

This repro is about the router warning shown when using Nuxt 3.8.1 with SASS files:
```shell
[Vue Router warn]: No match found for location with path "/_nuxt/@plugin-vuetify/lib/components/VLocaleProvider/VLocaleProvider.sass".
```

There are also errors in dev tools resolving `@vite/client`, base seems to be `/` instead of `/_nuxt/` (error on page refresh on Nuxt 3.8.0 and 3.8.1):
![img.png](img.png)

![img_1.png](img_1.png)

## Run Nuxt 3.8.0

To run this repro using Nuxt 3.8.0 checkout the [main branch]() and run `pnpm install && pnpm dev`.

## Run Nuxt 3.8.1

You can run this repro using Nuxt 3.8.1 using the [nuxt-3.8.1 branch]().

