# Portfolio

このリポジトリは、`沢宮いうら`さんのポートフォリオサイトです。

## 概要

- `index.html` : ポートフォリオの静的ウェブページです。
- `cover.png` / `profile.png` : サイトで使用されるカバー画像とプロフィール画像です。
- `videos.csv` / `BKvideos.csv` / `videos.csv.bak` : 動画リストやデータ管理用のCSVファイルです。
- `OutputCSV.ipynb` : CSVデータの加工や出力を行う Jupyter ノートブックです。

## 使い方

### ローカルで表示する

1. このリポジトリをクローンまたはダウンロードします。
2. `index.html` をブラウザで開きます。

### Jupyter ノートブックを使う

1. Python と Jupyter Notebook / Jupyter Lab をインストールします。
2. このリポジトリのルートで `OutputCSV.ipynb` を開きます。
3. 必要に応じて `videos.csv` などの CSV を読み込んでデータ処理を実行します。

## ファイル構成

- `index.html` : ポートフォリオページ本体
- `cover.png` : カバービジュアル画像
- `profile.png` : プロフィール画像
- `videos.csv` : 動画リストのデータファイル
- `BKvideos.csv` : 動画データのバックアップ/別バージョン
- `videos.csv.bak` : `videos.csv` のバックアップファイル
- `OutputCSV.ipynb` : CSV変換・編集用ノートブック

## 備考

- `index.html` は Tailwind CSS、AOS、Font Awesome などの CDN を利用する静的サイトです。
- 必要に応じて画像や CSV を差し替えて、内容を更新できます。
