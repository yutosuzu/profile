# satooru-hugo-theme

## プロジェクトの作成
### ディレクトリの作成
```shell
hugo new site [dirName]
```
`dirName` は変更可能

### VScode で開く
```shell
code profile
```

### テーマの追加
```shell
git submodule add https://github.com/SatooRu65536/satooru-hugo-theme themes/satooru-hugo-theme
```

### サンプルデータの追加
```shell
cp -r ./themes/satooru-hugo-theme/exampleSite/* ./ 
```

### 不要なファイルの削除
```shell
rm -r ./hugo.toml
```

## ローカルサーバの立ち上げ
```shell
hugo server
```

## ブログの追加
```shell
hugo new posts/memorandum/[title]/index.md
```
`[title]` は適宜変更

作成された `index.md` を適宜変更する必要がある

```
---
title: "タイトル"
date: 2023-06-03T22:26:29+09:00
weight: 20230603
menu:
  sidebar:
    name: "タイトル"
    identifier: 2023-06-03T22:26:29+09:00
    weight: 20230603
    parent: "親フォルダー名"
---
```


## LICENSE
[MIT](./LICENSE)
