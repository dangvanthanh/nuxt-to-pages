# Nuxt To Pages

> Starter template or boilerplate using Nuxt, Turborepo and Vite

## What's inside?

This turborepo uses [bun](https://bun.sh/) as a package manager. It includes the following packages/apps:

### Apps, Layers and Packages

- `web`: Nuxt app
- `biome-config`: Biome config for the repo
- `typescript-config`: TypeScript config for the repo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [Biome](https://biomejs.dev/) for code linting and formatting
- [Shadcn-vue](https://www.shadcn-vue.com) - Beautifully designed components
- [Vue Email](https://vuemail.net/) for generation of writing emails

### Build

To build all apps and packages, run the following command:

```
cd nuxt-to-pages
bun build
```

### Develop

To develop all apps and packages, run the following command:

```
cd nuxt-to-pages
bun dev
```

### Remote Caching

Turborepo can use a technique known as [Remote Caching](https://turbo.build/repo/docs/core-concepts/remote-caching) to share cache artifacts across machines, enabling you to share build caches with your team and CI/CD pipelines.

By default, Turborepo will cache locally. To enable Remote Caching you will need an account with Vercel. If you don't have an account you can [create one](https://vercel.com/signup), then enter the following commands:

```
cd my-turborepo
npx turbo login
```

This will authenticate the Turborepo CLI with your [Vercel account](https://vercel.com/docs/concepts/personal-accounts/overview).

Next, you can link your Turborepo to your Remote Cache by running the following command from the root of your Turborepo:

```
npx turbo link
```

## Useful Links

Learn more about the power of Turborepo:

- [Tasks](https://turbo.build/repo/docs/core-concepts/monorepos/running-tasks)
- [Caching](https://turbo.build/repo/docs/core-concepts/caching)
- [Remote Caching](https://turbo.build/repo/docs/core-concepts/remote-caching)
- [Filtering](https://turbo.build/repo/docs/core-concepts/monorepos/filtering)
- [Configuration Options](https://turbo.build/repo/docs/reference/configuration)
- [CLI Usage](https://turbo.build/repo/docs/reference/command-line-reference)

## License

MIT © [Dang Van Thanh](https://dangthanh.org)