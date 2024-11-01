# diff-raster-tile
MapLibre で２種類のタイルの差分を表示する方法

https://mghs15.github.io/diff-raster-tile/

## 参考資料

* MapLibre https://github.com/maplibre/maplibre-gl-js
* MapLibre GL JSと地理院標高タイルで3D地形を表示する https://qiita.com/Kanahiro/items/1e9c1a4ad6be76b27f0f
* Maplibre GL JS の addProtocol の使い方を調べる https://qiita.com/mg_kudo/items/cc88be1ed46fa77871fd
* PMTiles 消費における MapLibre GL JS v4 の破壊的変更への対応 https://qiita.com/mg_kudo/items/f6cadbc06bc5d13fe387
* その他、ChatGPT の力を借りています。

## サンプルデータ
* ハザードマップポータルサイト https://disaportal.gsi.go.jp/hazardmapportal/hazardmap/copyright/opendata.html
  * 浸水継続時間（想定最大規模）
  * 浸水継続時間（想定最大規模）_国管理河川
* 標高タイル https://maps.gsi.go.jp/development/ichiran.html#dem
