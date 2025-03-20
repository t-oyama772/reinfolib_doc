# 不動産情報データの構成

## 1. 不動産価格データ (real_estate_prices)

| カラム名            | 説明                         |
|--------------------|-----------------------------|
| type               | 取引の種類                   |
| region             | 地区                         |
| municipality_code  | 市区町村コード               |
| prefecture         | 都道府県名                   |
| municipality       | 市区町村名                   |
| district_name      | 地区名                       |
| trade_price        | 取引価格（総額）             |
| price_per_unit     | 坪単価                       |
| floor_plan         | 間取り                       |
| area               | 面積（平方メートル）         |
| unit_price         | 取引価格（平方メートル単価） |
| land_shape         | 土地の形状                   |
| frontage           | 間口                         |
| total_floor_area   | 延床面積（平方メートル）     |
| building_year      | 建築年                       |
| structure          | 建物の構造                   |
| use                | 用途                    |
| purpose            | 今後の利用目的          |
| direction          | 前面道路：方位          |
| classification     | 前面道路：種類          |
| breadth            | 前面道路：幅員（m）     |
| city_planning      | 都市計画                |
| coverage_ratio     | 建蔽率（%）            |
| floor_area_ratio  | 容積率（%）            |
| period             | 取引時点                |
| renovation         | 改装                    |
| remarks            | 取引の事情等            |
| period_year        | 取引時点＿年            |

## 2. 市区町村別の不動産取引の集計データ

| カラム名                     | 説明                               |
|----------------------------|-----------------------------------|
| prefecture                 | 都道府県名                            |
| municipality               | 市区町村名                            |
| district_name              | 地区名                               |
| period                     | 取引時点                              |
| trade_count_quarter        | 取引時点1クォーターの取引件数         |
| total_trade_price_quarter  | 取引時点1クォーターの取引価格の合計   |
| trade_count_last_1_year    | 取引時点から直近1年間の取引件数       |
| total_trade_price_last_1_year | 取引時点から直近1年間の取引価格の合計 |

## データの更新頻度
本データセットは、四半期ごと（3ヶ月に1回）更新 されます。<br>
最新の不動産取引情報を継続的に取得できるようになっています。
