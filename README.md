# nx

The purpose of this repo is to provide a reproducible example of a bug in the nx monorepo tooling.

## Steps to reproduce the issue
With an assumption you have `yarn` and `npx` installed globally, run the following commands: 

```
yarn install
npx nx run-many --target=build
npx nx generate @myorg/my-plugin:my-generator mylib
```