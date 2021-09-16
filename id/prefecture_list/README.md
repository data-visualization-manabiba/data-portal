# 日本における行政区分

## ファイルの内容

### resions.csv

日本の地域。法律上の明確な定義はないものの慣習的に使用される分類を採用しています。idはprefectures.csvのregionsと対応しています。

### prefectures.csv

全国地方公共団体コードとして規定されているもののうち都道府県コードをデータ化しました。JIS X 0401として規定されているほか、ISO 3166-2にも番号は引き継がれています。

### prefecturalCapital.csv

都道府県庁の所在する緯度と経度。各都道府県庁ウェブサイトに記載の住所を、Geocoding.jp( http://www.geocoding.jp/ )を用いて緯度経度を算出した。作業日は2014年7月1日。


## データソース / Data Source

都道府県表記は、全国地方公共団体コード( http://www.soumu.go.jp/denshijiti/code.html )として規定されているもののうち都道府県コードをデータ化しました。
JIS X 0401として規定されているほか、ISO 3166-2にも番号は引き継がれています。

英語表記は以下のページに掲載のPDFファイルを参照しています。

- https://www.gsi.go.jp/kihonjohochousa/kihonjohochousa40072.html
- https://www.gsi.go.jp/common/000138865.pdf


## ファイル作成日 / File Creation Date

- 2021-09-16



## ライセンス
使用ライセンスは配布元に準じ、Public Domainとします。