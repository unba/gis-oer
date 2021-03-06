# 地理情報科学　GISスタンダード構成
>浅見 泰司, 貞広 幸雄, 湯田 ミノリ, 矢野 桂司 編 (2015)『地理情報科学　GISスタンダード』　古今書院

## １ 地理情報科学
* 1.1	実世界とその概念モデル
* 1.2	地理情報と地理データ
* 1.3	地理情報科学
* 1.4	地理情報科学の研究内容
* 1.5	地理情報科学の関連分野

## ２ 地理情報システムと地理情報科学の歴史
* 2.1 世界のGISの歴史
 * 2.1.1 創始期(1950年代・1960年代)
 * 2.1.2 拡大・成長期(1970年代・1980年代)
 * 2.1.3 発展・成熟期(1990年代)
* 2.2 日本のGISの歴史
 * 2.2.1 創始期(1970年代)
 * 2.2.2 拡大期(1980年代)
 * 2.2.3 発展期(1990年代)

## ３ 空間的思考とGIS
* 3.1 空間的思考と関連する概念
* 3.2 空間的思考の構成要素
 * 3.2.1 空間的概念
 * 3.2.2 空間的表現(表現ツール)
 * 3.2.3 空間的推論(推論過程)
* 3.3空間的思考の応用
* 3.4空間的思考の教育とGIS
 * 3.4.1 学校教育における空間的思考の指導
 * 3.4.2 空間的思考におけるGISの役割
 * 3.4.3 GIS教育における空間的思考
* 3.5 おわりに

## ４ 空間事象のモデル化と形式化
* 4.1空間的事象の認知
* 4.2 モデルの記述
* 4.3 モデルの形式化
* 4.4 UML
* 4.5 空間情報のためのメタモデル
* 4.6 平面上の空間スキーマ
* 4.7 一般地物モデル
* 4.8 応用スキーマ
* 4.9 インスタンスモデル
* 4.10 まとめ

## ５ 測量
* 5.1 地上測量
 * 5.1.1 水準測量
 * 5.1.2 トラバース測量
* 5.2 GNSS測量
 * 5.2.1 単独測位
 * 5.2.2 干渉測位
* 5.3 写真測量
 * 5.3.1 次元計測の原理
 * 5.3.2 単写真評定
 * 5.3.3 相互評定
* 5.4 レーザー測量

## ６ リモートセンシングとその解析
* 6.1 センサとその観測波長帯
* 6.2 プラットフォーム
* 6.3 画像のカラー合成と強調
* 6.4 画像の幾何補正（オルソ幾何補正）
* 6.5 可視・赤外リモートセンシングデータの解析（土地被覆分類図）
* 6.6 熱赤外リモートセンシングデータの解析（地表面温度分布図）
* 6.7 合成開口データによって得られたデータの解析
* 6.8 データの入手

## ７ 既存データの地図データと属性データ
* 7.1 国・地方自治体のGISデータ
 * 7.1.1 国土交通省のGISデータ
 * 7.1.2 環境省のGISデータ
 * 7.1.3 農林水産省のGISデータ
 * 7.1.4 総務省のGISデータ
 * 7.1.5 属性データを地図化するためのデータ
 * 7.1.6地方自治体のGISデータ
* 7.2 民間のGISデータ
 * 7.2.1 地図データ
 * 7.2.2 住宅地図
 * 7.2.3 道路のGISデータ
 * 7.2.4 郵便番号区のGISデータ
 * 7.2.5 施設に関する民間データ
 * 7.2.6 ジオデモグラフィックス(Geodemographics)
* 7.3 デジタル化されていない地理空間情報のGIS化
* 7.4 おわりに

## ８ 空間データ
* 8.1 空間データの品質
* 8.2 空間データの変換
 * 8.2.1 解像度・空間構成単位の変換
 * 8.2.2 空間座標の変換（測地系変換、投影変換）
 * 8.2.3幾何補正（代表点を用いたジオリファレンス）
 * 8.2.4 オルソ補正（オルソ補正）
* 8.3 ジオコーディング（Google Geocoding API）

## ９ 空間データベース
* 9.1 データベースシステム
* 9.2 データベース管理システム
* 9.3 空間検索と空間索引（空間検索）
* 9.4 空間データベース言語
* 9.5 空間データベースの現状と今後（PostGISによる測地系変換、投影変換、データーフォーマット変換、空間演算など）

## 10 空間データの結合・修正
* 10.1 結合(モザイク)（ラスタの結合、ジオリファレンス）
* 10.2 ベクタ編集(データのエラーと修正)（ベクタの編集）
* 10.3 欠落情報の捕捉(統計的手法、補間の概念)（空間補間、demからの等高線抽出）
* 10.4 ラスタ・ベクタ変換（raster to vector or vector to raster）
 * 10.4.1ラスタからベクタの変換
 * 10.4.2 ベクタからラスタの変換

## 11 基本的な空間解析
* 11.1 基本量の測定 (ベクタの長さを測る)
 * 11.2 空間オブジェクトの選択（オブジェクトの選択、属性テーブル）
 * 11.3 その他の空間データの操作（marge , clip , dissolve）
 * 11.4 オーバーレイ分析 (union , intersect)

## 12 ネットワーク分析
* 12.1 最短経路検索
 * 12.1.1 ダイクストラ法
 * 12.1.2 ワーシャルフロイド法
* 12.2 グラフネットワークの用語
* 12.3 最大流問題
* 12.4 ネットワーク構造分析
* 12.5 プログラム例

## 13 領域分析
* 13.1 バッファによる領域分析　(バッファ)
* 13.2 ボロノイ分割による領域分析（ボロノイ分割法）

## 14 点データの分析
* 14.1 視覚的分析
* 14.2 数理的分析

## 15 ラスターデータの分析
* 15.1 視覚的分析（陰影図）
* 15.2 集計と基本統計分析（ラスタのクリップと統計量の集計）
* 15.3 フィルタリング（ラスタのスムージング、フィルタ）
* 15.4 ラスタ演算（demの引き算）
* 15.5 流域解析（流域解析）
* 15.6 コストパス解析（移動コスト解析）
* 15.7 セルオートマン　（土地利用変化の予測など）

## 16 傾向面分析

* 16.1 傾向面分析の基礎
* 16.2 傾向面分析の適用例
* 16.3 残差分析
* 16.4 多項式以外の当てはめ

## 17 空間的自己相関
* 17.1 空間的自己相関分析の系譜
* 17.2 空間的自己相関分析に関する統計量
 * 17.2.1 バリオグラムとコバリオグラム空間重み行列
 * 17.2.2 空間重み行列
 * 17.2.3 ジョイン統計量
 * 17.2.4 Moran's IとGeary's C

## 18 空間補間
* 18.1 補間店近傍の観測値を用いる空間補間法
 * 18.1.1 距離に基づく近傍点選択
   * A) 最近隣法
   * b)半径法
   * c)四分割法・八分割法
 * 18.1.2 不正三角網に基づく近傍点選択が
 * 18.1.3 逆距離加重法
* 18.2 大域的な観測値を用いる空間補間法
 * 18.2.1 補間対象の空間事象の観測値のみ用いる方法
   * a)スプライン補間
   * b)Akima補間法
 * 18.2.2 補間事象の空間事象と相関を持つ空間事象の観測値を用いる方法
   * a) 通常クリギング
   * b) 共クリギング
   * c) 普遍クリギング
   * d) 普遍共クリギング

## 19 空間相関分析
* 19.1 空間的相関関係分析の軽量化
 * 19.1.1 クロスバリオグラム
 * 19.1.2 空間クロス相関
* 19.2 空間的相関関係を組み込んだモデリング
 * 19.2.1 一般的（非空間的）な回帰分析と空間モデル
 * 19.2.2 空間的従属性を取り入れたモデル
 * 19.2.3 空間的異質性を取り入れたモデル

## 20 空間分析におけるスケール
* 20.1 ２つの空間スケール問題
* 20.2 空間分析単位の問題
* 20.3 ローカル・グローバル問題

## 21 視覚的伝達
* 21.1 ビジュアリゼーションとは
* 21.2 空間情報の視覚化の起こり
* 21.3 視覚的伝達の意義
* 21.4 視覚的伝達方法の類型化
* 21.5 錯視（オプティカル・イルージョン）
* 21.6 視覚的分析

## 22 地図表現モデル
* 22.1 表現モデル
 * 22.1.1 基本図
 * 22.1.2 主題図
* 22.2 主題図の表現方法
 * 22.2.1 データの意味性
 * 22.2.2 記号化の基本パターン
 * 22.2.3量的データの分類
 * 22.2.4 誇張と省略
 * 22.2.5 次元操作
 * 22.2.6 座標の対応付け

## 23 地図のデザイン
* 23.1 表示範囲
* 23.2 背景図
* 23.3 地図記号の体系化
* 23.4 地図の整飾とレイアウト
* 23.5 出力図の作成

## 24 双方向環境のマッピング
* 24.1 地図の利用とマッピング環境
* 24.2 ウェブマッピング
* 24.3 ユビキタスマッピング
* 24.4 バーチャルマップ
* 24.5 ユビキタス空間情報社会の展望と課題

## 25 GISの社会貢献
* 25.1 地図自動作成と施設管理
 * 25.1.1 地図自動作成
 * 25.1.2 施設管理
* 25.2 空間意思決定システム
 * 25.2.1 DSSの定義
 * 25.2.2 SDSSの定義
 * 25.2.3 SDSSの構成要素
 * 25.2.4 SDSSの応用
* 25.3 位置情報サービス
 * 25.3.1 LBSの定義
 * 25.3.2 LBSの技術
 * 25.3.3 LBSのサービスタイプ
 * 25.3.4 LBSの最近の動向

## 26 参加型GISと社会貢献
* 26.1 GISのSの意味
* 26.2 社会貢献としてのクライシスマッピング
* 26.3 ハイチ地震での現地活動への貢献
* 26.4 東日本大震災での取り組み
* 26.5 東日本大震災以降の動き
* 26.6 クライシスマッピングの特徴
* 26.7 市民による参加型GISからGeoDesignへ
* 26.8 まとめ

## 27 空間データの流通と共用
* 27.1 空間データ基盤の開発と実践
* 27.2 流通と共用のための空間データ
* 27.3 空間データの流通・共用と法制度

## 28 組織におけるGISの導入と運用
* 28.1 導入に向けた計画作づくり
* 28.2 GISの設計,実装
* 28.3 地理空間情報データの整備
* 28.4 GISの運用、人材育成
* 28.5 地域課題の解決に向けて

## 29 GISと教育・人材育成
* 29.1 学校教育とGIS
 * 29.1.1 学習指導要領とGIS
 * 9.1.2 初等中等教育とGIS
* 29.1.3 初等中等教育でのGIS活用における問題点とこれから
 * 29.1.4 高等教育とGIS
* 29.2 社会におけるGISと教育
 * 29.2.1 国・地方自治体による人材育成
 * 29.2.2 企業向けトレーニング
 * 29.2.3 開かれたGISの教育の場
* 29.3 GISの普及を支える学協会
 * 29.3.1 学協会
 * 29.3.2 GIS関連の資格

## 30 GISと未来社会
* 30.1 高度情報通信ネットワーク
 * 30.1.1 米国　情報スーパーハイウェイ構想
 * 30.1.2 日本の高度情報通信ネットワーク社会
 * 30.1.3 クラウドコンピューティング
 * 30.1.4 ソーシャル・ネットワーキング・サービス（SNS）
 * 30.1.5 オープンデータ
* 30.2 クラウドセンシングと参加型センシング
* 30.3 高度地理空間情報社会
 * 30.3.1 地理空間情報中心で管理される社会
 * 30.3.2 地理時空間ビックデータと人々の流動把握
