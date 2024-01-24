# hippocrates-template

Excel / CSV / GeoJSON 形式の、位置情報データをシンプルに可視化するテンプレートリポジトリです。

<img width="897" alt="スクリーンショット 2024-01-19 9 35 42" src="https://github.com/geolonia/hippocrates-template/assets/8760841/f8bfa8a2-d187-4358-84b0-7ace0a2bbd04">

## 使い方

### **:black_medium_square: 初期設定**

* [[Use this template]](https://github.com/geolonia/smartcity-data-upload-template/generate) ボタンをクリックして、このテンプレートを自分のリポジトリにコピーしてください。
* GitHub Pages の設定をしてください。

### **:black_medium_square: データを追加する**
* Excel / CSV / GeoJSON ファイルをリポジトリにアップロードして下さい。
* Excel / CSV の列名、GeoJSON のプロパティは、デジタル庁の[自治体標準オープンデータセット（正式版）](https://www.digital.go.jp/resources/open_data/municipal-standard-data-set-test) に準拠しています。
* サンプルの列名は [山形市指定緊急避難場所一覧（オープンデータ）](https://www.city.yamagata-yamagata.lg.jp/_res/projects/default_project/_page_/001/006/196/062014_evacuation_space.csv)をご覧ください。
* 点形式のデータのみに対応しています。

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
