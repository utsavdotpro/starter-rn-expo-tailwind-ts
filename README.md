# Subminder

WIP

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

## Development Strategy
### Branches
- `main` is the main development branch.
- New branches are created for new features and bug fixes.
- All branches are named as `SUB-<ticketId>`. Where _ticketId_ is the ticket number on the [Linear](https://linear.app/subminder/team/SUB/all) board.
- All branches are merged into the `main` branch with a Pull Request.
### Pull Requests
- Pull requests are created for all the features and bug fixes branches.
- Pull request title is the ticket title on the [Linear](https://linear.app/subminder/team/SUB/all) board.
- Fellow team members are to be asked to review the pull request.
- Only after the pull request is approved, the branch is squashed & merged.
### Commits
- Commit messages are always in the future tense.
- Commit messages are the extension of the sentence "**If this change is merged it will...**". For example:  
  "make the primary button bigger"    
  "fix color of secondary button".
- For small changes, following commit messages are also accepted:  
  "minor change"  
  "minor fix"

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