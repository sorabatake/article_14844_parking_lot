# article_14844_parking_lot
日本発の衛星データプラットフォーム Tellus のオウンドメディア「宙畑」の記事、https://sorabatake.jp/14844 で利用しているコードです。
人工衛星のデータを使って、遊園地の駐車場の満車率を可視化できないかというチャレンジになります。

- いつ空いてるの!? 無料衛星データでディズニーランドの混雑予想チャレンジ（前編）
- https://sorabatake.jp/349/
- 衛星データで遊園地の混雑予測！（Tellusコード付き）
- https://sorabatake.jp/14844/

## 構成
- parking_lot.ipynb
    - 駐車場の満車率を計算するコード
-  disneysisaku.geojson
    - 駐車場の形に切り抜くためのGeojson 
## ライセンス、利用規約
ソースコードのライセンスは CC0-1.0（Creative Commons Zero v1.0 Universal）ライセンスです。  
今回コード内で Sentinel-1 データを用いております。利用ポリシーは以下をご参考下さい。
https://sentinel.esa.int/web/sentinel/user-guides/sentinel-1-sar

## 貢献方法
プルリクエストや Issue はいつでも歓迎します。
