# 230130法務省地番データ結合

## 概要
本データは、2023年1月23日に公開された[法務省登記所備付地図データ](https://front.geospatial.jp/houmu-chiseki/)と『檜山郡厚沢部村字名地番変更調書』（昭和35年）掲載の旧字名データを結合し、GISで利用できる地名データです。

北海道分の地図データは北海道庁の喜多耕一さんがGeojsonに変換したものをGitHubにアップロード・公開しているので（[登記所備付地図（Geojson）のダウンロード](https://koukita.github.io/touki_map_hokkaido/index_link.html?fbclid=IwAR0QTgV2eM-y2Pdyc1tgpufsNHvjO5TpnvlCU4_pPMNprYYDuCDg36Vv-LA)）、これを利用しました。

## ディレクトリ

- Rscript　地番結合用のRスクリプト
- data　登記所備付地図データと旧地名データ
- output　結合された旧字名データ

outputディレクトリにはGPKG、GeoJson、KMLの各ファイルが格納されています。