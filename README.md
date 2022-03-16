<p>
  <img width="100%" src="./banner.png" alt="Solid And Capacitor Vite Templates">
</p>

# Capacitor Templates for [SolidJS](https://www.solidjs.com/) (and [vite](https://vitejs.dev/))

This repository holds production ready Capacitor templates for building native mobile applications using SolidJS + vite. Using Capacitor, you can quickly build out a native mobile application for iOS and Android using web technology, such as SolidJS.

## Getting Started

Be sure to follow our [getting started guide](https://capacitorjs.com/docs/getting-started) for Capacitor to setup your environment correctly. Once your environment is set up for mobile development, you can use [degit](https://github.com/Rich-Harris/degit) to clone one of these Capacitor templates and start building your native app with SolidJS!

When developing, you can use vite just as you would for a standard web application. For these templates, you can run `npm start` to boot up the vite dev server with Hot Module Replacement (HMR). Once you are ready to test your app on mobile, you can use one of the following commands to build and run your native app on your mobile device.

#### iOS

```bash
npm run build
npx cap run ios
```

#### Android

```bash
npm run build
npx cap run android
```

_note: The Capacitor + SolidJS dependencies are maintained via [pnpm](https://pnpm.io) via `pnpm up -Lri`. This is the reason you see a `pnpm-lock.yaml`. That being said, any package manager will work. The `pnpn-lock.yaml` file can be safely be removed once you clone a template if you would like to use another package manager like `npm` or `yarn`._

### Deploying to App Stores

Once you are ready to deploy your app, you can follow our guides building your native application for the [Apple App Store](https://capacitorjs.com/docs/ios/deploying-to-app-store) or the [Google Play Store](https://capacitorjs.com/docs/android/deploying-to-google-play).

## Template List

#### Javascript template

```bash
npx degit ionic-team/capacitor-solidjs-templates/js my-project
cd my-project
npm install # or pnpm install or yarn install
```

#### Typescript template

```bash
npx degit ionic-team/capacitor-solidjs-templates/ts my-project
cd my-project
npm install # or pnpm install or yarn install
```

#### Typescript minimal template

```bash
npx degit ionic-team/capacitor-solidjs-templates/ts-minimal my-project
cd my-project
npm install # or pnpm install or yarn install
```

#### Typescript unocss template

```bash
npx degit ionic-team/capacitor-solidjs-templates/ts-unocss my-project
cd my-project
npm install # or pnpm install or yarn install
```

#### Typescript windicss template

```bash
npx degit ionic-team/capacitor-solidjs-templates/ts-windicss my-project
cd my-project
npm install # or pnpm install or yarn install
```

#### Typescript windicss template + basic file base routing

```bash
npx degit ionic-team/capacitor-solidjs-templates/ts-router my-project
cd my-project
npm install # or pnpm install or yarn install
```

#### Typescript bootstrap (5) template

```bash
npx degit ionic-team/capacitor-solidjs-templates/ts-bootstrap my-project
cd my-project
npm install # or pnpm install or yarn install
```

#### Typescript + tailwindcss template

```bash
npx degit ionic-team/capacitor-solidjs-templates/ts-tailwindcss my-project
cd my-project
npm install # or pnpm install or yarn install
```

#### Typescript + sass template

```bash
npx degit ionic-team/capacitor-solidjs-templates/ts-sass my-project
cd my-project
npm install # or pnpm install or yarn install
```

#### Typescript + vitest template

```bash
npx degit solidjs/templates/ts-vitest my-solid-project
cd my-solid-project
npm install # or pnpm install or yarn install
```

#### Typescript + uvu template

```bash
npx degit solidjs/templates/ts-uvu my-solid-project
cd my-solid-project
npm install # or pnpm install or yarn install
```

## I don't see a template that matches my need?

You wish there was a template with your favorite library?

Feel free to make a pull request. Copy one of the template already available, tweak it, name it properly and make a PR. See [contributing](#contributing) below.

## Contributing

This project is managed with [pnpm](https://pnpm.io). You should [install it](https://pnpm.io/installation) first to test out your template or contribute to an existing one.

You can create your own template and prefix it with `ts-` or `js-` and giving it a name that describe the purpose.

To update all dependencies you can run:

`pnpm up -Lri`

## Community

You learn more about Capacitor on the [Capacitor Website](https://capacitorjs.com) and come chat with us the [Ionic Discord](https://discord.gg/UPYYRhtyzp) if you have any questions. For Solid questions, you can learn more on the [Solid Website](https://solidjs.com) and join the [SolidJS Discord](https://discord.com/invite/solidjs)
