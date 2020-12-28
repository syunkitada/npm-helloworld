# npm-helloworld

## メモ

- repo 直下に index.js, index.d.ts を置くようにしている
  - github から直接インストールして使うため

```
# インストール
$ yarn add syunkitada/npm-helloworld
```

```
# 利用方法
import { Greeter } from "npm-helloworld";

console.log(Greeter("Carl"));
```

## コマンドなど

```
# tesing
npm test

# formating
npm run format

# linting
npm run lint

# build
npm run build
```

## 参考

- https://itnext.io/step-by-step-building-and-publishing-an-npm-typescript-package-44fe7164964c
