# RN with Expo & Tailwind in TypeScript

A starter template for ReactNative with Expo & Tailwind in TypeScript with a [modular project structure](#project-structure)

### Tech Stack
- [Expo](https://expo.dev/) v46
- [ReactNative](https://reactnative.dev/) v0.69
- [Tailwind-rn](https://github.com/vadimdemedes/tailwind-rn) v4
- [TypeScript](https://typescriptlang.org) v4

[<img src="https://ik.imagekit.io/iutsav/fork-on-codesandbox__e0mFWzr1.png?updatedAt=1641916982302" width="200"/>](https://githubbox.com/utsavdotpro/starter-rn-expo-tailwind-ts)

---

## How to Reuse Locally?

Use `degit` to download the repository locally.

> ### ❓ What is [degit](https://github.com/Rich-Harris/degit)?
> degit downloads a copy of git repository with downloading its entire git history.

Install degit globally.

````bash
npm install -g degit
````

Download the latest version
````bash
degit utsavdotpro/starter-rn-expo-tailwind-ts
````

## Getting Started

Install dependencies
````bash
yarn install
````

Start expo server
````bash
yarn start
````

Launch the development apps
````bash
# start android app
yarn android

# start ios app
yarn ios

# start web app
yarn web
````

Use _Tailwind-rn_
````bash
# start Tailwind class generator (in watch mode)
yarn dev:tailwind

# build Tailwind classes
yarn build:tailwind
````

## Project Structure
```
project
|-- public                    ℹ️ keep your static resource files
|-- src
|   |-- common
|   |   |-- components
|   |   |   |-- elements      ℹ️ keep your state-less components
|   |   |   |                 ℹ️ keep your state-full components
|   |   |-- hoc
|   |   |-- hooks
|   |   |-- layouts
|   |   |-- types
|   |-- modules
|   |-- screens
|   |-- services
|   |-- styles
|   |-- utils
|   |   |-- constants         ℹ️ keep your constants
|   |   |                     ℹ️ keep your util functions
```