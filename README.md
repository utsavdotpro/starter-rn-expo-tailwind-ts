# RN with Expo & Tailwind in TypeScript

A starter template for ReactNative with Expo & Tailwind in TypeScript with a [modular project structure](#project-structure)

### Tech Stack
- [Expo](https://expo.dev/)
- [ReactNative](https://reactnative.dev/)
- [Tailwind-rn](https://github.com/vadimdemedes/tailwind-rn)
- [TypeScript](https://typescriptlang.org)

---

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