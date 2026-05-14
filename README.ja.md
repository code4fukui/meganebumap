# MEGANEBU MAP


アニメ『メガネブ！』のオープニング映像に登場する現実世界のロケ地への「聖地巡礼」のためのインタラクティブマップです。

## デモ

**[http://codeforfukui.github.io/meganebumap/](http://codeforfukui.github.io/meganebumap/)**

## 機能

- 📍 アニメのオープニングに登場するすべてのロケ地を表示するインタラクティブマップ。
- 📸 マーカーをクリックすると、その場所の写真、シーンの詳細、Google マップで開くリンクが表示されます。
- 🗺️ 地図の下部に全スポットのスクロール可能なリストを表示し、素早い閲覧とナビゲーションが可能。
- 🛰️ 現在のGPS位置を中心に地図を表示し、近くのスポットを検索。
- 🔍 「すべて表示」ボタンで、全スポットが地図上に収まるようにズーム調整。

## データとAPI

- ロケ地データは、Linkdata.orgのオープンデータセット [Meganebu! Location RDF](https://linkdata.org/work/rdf1s1093i) から取得しています。
- インタラクティブマップには [Google Maps API](https://developers.google.com/maps) を使用しています。

## 開発環境のセットアップ

このプロジェクトをローカルで実行するには、Google Maps APIキーが必要です。

1. リポジトリをクローンします。
2. `index.html` を開き、`<script>` タグのURLに含まれるAPIキーをご自身のものに置き換えます:
    ```html
    <script src="https://maps.google.com/maps/api/js?key=YOUR_API_KEY_HERE&language=ja"></script>
    ```
3. `index.html` をウェブブラウザで開きます。

## ライセンスとクレジット

本プロジェクトは MIT License の下で公開されています。詳細は [LICENSE](LICENSE) を参照してください。

同梱されている `fukuno.js` ライブラリは、Taisuke Fukuno (@taisuke) により CC BY ライセンスの下で提供されています。