# typescript-base

TypeScriptのプロジェクト用テンプレート

## 環境

```
$ node -v
v12.19.0
$ npm -v
6.14.8
```


## 開発サポートツール

- EditorConfig
- ts-node
  
  ```
  $ npx ts-node src/index.ts
  ```
- ts-node-dev

  ```
  $ npx ts-node-dev --respawn src/index.ts
  ```

- eslint

  ```
  npx eslint src/index.ts
  ```

- Prettier
  
  ```
  npx prettier --write src/index.ts
  ```

## 参考

- [TypeScript + Node.js プロジェクトのはじめかた2020](https://qiita.com/notakaos/items/3bbd2293e2ff286d9f49)