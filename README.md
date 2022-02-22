<p>
  <img width="100%" src="https://raw.githubusercontent.com/ionic-team/capacitor-solidjs-templates//master/banner.png" alt="Solid And Capacitor Vite Templates">
</p>

# Solid Templates (using [vite](https://vitejs.dev/)) & Capacitor

This repository holds most of the official starter templates for [vite](https://vitejs.dev/).

You get:

- HMR out of the box
- Minimal bundle size
- All the vite features
- A bootstrapped Capacitor project

To see the official SolidJS templates, check out the [SolidJS Template Repo](https://github.com/solidjs/templates).

### Learn more on the [Solid Website](https://solidjs.com) and come chat with us on our [Discord](https://discord.com/invite/solidjs)

### Learn more on the [Capacitor Website](https://capacitorjs.com) and come chat with us on our [Discord](https://discord.gg/UPYYRhtyzp)

## Get started

Those templates dependencies are maintained via [pnpm](https://pnpm.io) via `pnpm up -Lri`.

This is the reason you see a `pnpm-lock.yaml`. That being said, any package manager will work. This file can be safely be removed once you clone a template.

These templates are meant to be used as is via the [degit](https://github.com/Rich-Harris/degit) utility.

```bash
# Javascript template
$ npx degit ionic-team/capacitor-solidjs-templates/js my-project
$ cd my-project
$ npm install # or pnpm install or yarn install
```

```bash
# Typescript template
$ npx degit ionic-team/capacitor-solidjs-templates/ts my-project
$ cd my-project
$ npm install # or pnpm install or yarn install
```

```bash
# Typescript minimal template
$ npx degit ionic-team/capacitor-solidjs-templates/ts-minimal my-project
$ cd my-project
$ npm install # or pnpm install or yarn install
```

```bash
# Typescript unocss template
$ npx degit ionic-team/capacitor-solidjs-templates/ts-unocss my-project
$ cd my-project
$ npm install # or pnpm install or yarn install
```

```bash
# Typescript windicss template
$ npx degit ionic-team/capacitor-solidjs-templates/ts-windicss my-project
$ cd my-project
$ npm install # or pnpm install or yarn install
```

```bash
# Typescript windicss template + basic file base routing
$ npx degit ionic-team/capacitor-solidjs-templates/ts-router my-project
$ cd my-project
$ npm install # or pnpm install or yarn install
```

```bash
# Typescript bootstrap (5) template
$ npx degit ionic-team/capacitor-solidjs-templates/ts-bootstrap my-project
$ cd my-project
$ npm install # or pnpm install or yarn install
```

```bash
# Typescript + tailwindcss template
$ npx degit ionic-team/capacitor-solidjs-templates/ts-tailwindcss my-project
$ cd my-project
$ npm install # or pnpm install or yarn install
```

```bash
# Typescript + sass template
$ npx degit ionic-team/capacitor-solidjs-templates/ts-sass my-project
$ cd my-project
$ npm install # or pnpm install or yarn install
```

## I don't see a template that matches my need?

You wish there was a template with your favorite library?

Feel free to make a pull request. Copy on of the template already available, tweak it, name it properly and make a PR. See [contributing](#contributing) below.

## Contributing

This project is managed with [pnpm](https://pnpm.io). You should [install it](https://pnpm.io/installation) first to test out your template or contribute to an existing one.

You can create your own template and prefix it with `ts-` or `js-` and giving it a name that describe the purpose.

To update all dependencies you can run:

`pnpm up -Lri`
