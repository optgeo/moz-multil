# moz-multil
mosaic of experimental_multil

# 出典
出典： 多言語化用ベクトルタイル（https://www.gsi.go.jp/common/000212661.pdf）

多言語化用ベクトルタイルを国連ベクトルタイルツールキットで加工して作成

# ここでのモザイク生産の基本的な考え方
- それぞれのレイヤが出てくる最小のズームレベルのタイルからモザイク生産をします。これは、多言語化用ベクトルタイルは GeoJSON ベクトルタイルなので、ズームレベルによらず座標の分解能は変わらないことが期待されるからです。ベクトルタイルであれば、最大のズームレベルからのモザイク生産をすることになるでしょう。

# See also
- [多言語表記の地図（説明ページ）](https://www.gsi.go.jp/kihonjohochousa/multilingual.html)
- [多言語表記の地図（ウェブ地図）](https://maps.gsi.go.jp/multil/index.html)
