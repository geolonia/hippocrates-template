# hippocrates-template

Excel / CSV / GeoJSON 形式の、位置情報データをシンプルに可視化するテンプレートリポジトリです。

![スクリーンショット 2024-01-24 18 07 09](https://github.com/geolonia/hippocrates-template/assets/8760841/0ddd1bee-164c-4ea0-b0c5-c4d88c32f325)


## 使い方

### **:black_medium_square: 初期設定**

* [[Use this template]](https://github.com/geolonia/smartcity-data-upload-template/generate) ボタンをクリックして、このテンプレートを自分のリポジトリにコピーしてください。
* GitHub Pages の設定をしてください。

### **:black_medium_square: データを追加する**
* Excel / CSV / GeoJSON ファイルをリポジトリにアップロードして下さい。
* Excel / CSV の列名、GeoJSON のプロパティは、デジタル庁の[自治体標準オープンデータセット（正式版）](https://www.digital.go.jp/resources/open_data/municipal-standard-data-set-test) に準拠しています。
* サンプルの列名は [山形市指定緊急避難場所一覧（オープンデータ）](https://www.city.yamagata-yamagata.lg.jp/_res/projects/default_project/_page_/001/006/196/062014_evacuation_space.csv)をご覧ください。
* 点形式のデータのみに対応しています。

### **:black_medium_square: カスタマイズ**

[package.json](https://github.com/geolonia/hippocrates-template/blob/main/package.json#L10C1-L15C5) 内の以下の項目を変更することでカスタマイズが可能です。

```
"settings": {
  "title": "Hippocrates Template",
  "description": "Hippocrates Template はデータ可視化用のテンプレートです。package.json 内の description を書き変えることで、この文章を置き換えることができます。",
  "logo": "https://geoloniamaps.github.io/pwamap/icon-pwamap.svg",
  "ogp": "https://geoloniamaps.github.io/pwamap/apple-splash-1136-640.jpg"
},
```


## 開発者向け

依存関係のインストール
```
$ npm install
```

データのプレビュー　（http://localhost:8080 が立ち上がります）
```
$ npm start
```

ビルド
```
$ npm run build
```

## クレジット
- [[山形市指定緊急避難場所一覧]](https://www.city.yamagata-yamagata.lg.jp/_res/projects/default_project/_page_/001/006/196/062014_evacuation_space.csv)、山形市、クリエイティブ・コモンズ・ライセンス 表示 4.0 国際（https://creativecommons.org/licenses/by/4.0/deed.ja）
