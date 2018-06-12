# Try-TypeScript-In-React-Native

This repo started by fellow [Microsoft/TypeScript-React-Native-Starter: A starter template for TypeScript and React Native with a detailed README describing how to use the two together.](https://github.com/Microsoft/TypeScript-React-Native-Starter), so it's just a demo.

The repo is inited by steps:

```shell
react-native init Try-TypeScript-In-React-Native
cd Try-TypeScript-In-React-Native

yarn add --dev typescript
yarn add --dev react-native-typescript-transformer
tsc --init --pretty --jsx react    // This is different to Microsoft/TypeScript-React-Native-Starter, as it can not init the tsconfig.json correctly.
touch rn-cli.config.js
yarn add --dev @types/react @types/react-native
```
