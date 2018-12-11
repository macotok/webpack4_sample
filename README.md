## 処理内容

- es6の記述をbabelでes5に変換
- sassファイルをcssに変換
- postcssのautoprefixでprefixを作成
- imgファイルを圧縮
- eslint導入
- devServerでlocal作業
- jQueryを一応入れてます

## ディレクトリ構成

```
├── dist　(compileしたものを管理)
├── package.json
├── src (作業場)
│   ├── img
│   │   └── sample.jpg
│   ├── js
│   │   └── app.js
│   └── sass
│       ├── _base.scss
│       ├── _modules.scss
│       └── style.scss
├── webpack.config.js
└── yarn.lock
```



## バージョン

- webpack ^4.17.2
- yarn 1.9.4
- node 10.5.0
