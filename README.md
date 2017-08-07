# 函館市電GTFSデータ
函館市電オープンデータのGTFS化データ（「標準的なバス情報フォーマット」準拠）です。
函館市の公開するオープンデータを基に作成しています。

https://tshimada291.github.io/hakodateshiden/hakodate_shiden_gtfs.zip

## 適用例
* [GTFS Viewer](http://www1.ttn.ne.jp/~shima/ict/opendata/apps/gtfs-viewer/)（日本国内で公開されているGTFSデータ・標準的なバス情報フォーマットデータの表示）
* [函館まっぷ](http://www1.ttn.ne.jp/~shima/ict/opendata/apps/gtfs-viewer/hakodate-map.html)（函館市電データと市内施設の表示（指定時間での営業状況・時刻表の表示に対応））

## ライセンス
使用データに基づき，[CC BY-SA](https://creativecommons.org/licenses/by-sa/2.1/jp/) を適用します。

### （データ出典元）
* 位置情報以外：「市電の運行時刻」「市電の乗車料金・営業距離」、[函館市オープンデータ](http://www.city.hakodate.hokkaido.jp/docs/2016072200055/)（[CC BY](https://creativecommons.org/licenses/by/2.0/)）
* 緯度経度情報（stops.txt, shapes.txt）： [OpenStreetMap](http://openstreetmap.org/copyright)（[CC BY-SA](https://creativecommons.org/licenses/by-sa/2.0/)）

### 更新情報
* 2017.07.24 shapes更新(OSM版)，office_jp・transfer追加（試行版）
* 2017.06.01 公開

## 参考
* [GTFSとは（Google）](https://developers.google.com/transit/gtfs/?hl=ja)
* [「標準的なバス情報フォーマット」（国土交通省）](http://www.mlit.go.jp/sogoseisaku/transport/sosei_transport_tk_000067.html)
