Reproduces an issue with TS's `project reference` + `baseUrl`. (https://github.com/microsoft/TypeScript/issues/38711)

Command:
```
yarn build
```

The error:
```
../pkg2/build/index.d.ts:1:24 - error TS2307: Cannot find module 'const' or its corresponding type declarations.

1 export { TheNum } from 'const';
```
