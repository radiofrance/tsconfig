# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for projects


## Install

```
$ npm install --save-dev @radiofrance/tsconfig
```


## Usage

`tsconfig.json`

```json
{
  "extends": "@radiofrance/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "target": "es2018",
    "lib": [
      "es2018"
    ]
  }
}
```


## License

[CECILL-B](https://spdx.org/licenses/CECILL-B.html)
