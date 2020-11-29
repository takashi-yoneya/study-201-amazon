# 案件で超使えるシリーズ１
Amamazonからのスクレいピングは案件で頻出のため是非おさえておきましょう
この機能を持ったツールはパッケージで４万程度で販売できることがあります。
（当方は２０万円以上の販売実績あり）
基本的に課題２の内容で対応可能です。

## １
以下のような商品個別ページの情報をスクレイピングしてみましょう。<BR>
（必要情報：商品名、価格、発送リードタイム、Primeかどうか、ASIN）
https://www.amazon.co.jp/%E3%80%90Amazon%E9%99%90%E5%AE%9A%E3%83%96%E3%83%A9%E3%83%B3%E3%83%89%E3%80%91%E3%83%9E%E3%82%B9%E3%82%AF-%E8%80%B3%E3%81%8C%E7%97%9B%E3%81%8F%E3%81%AA%E3%82%8A%E3%81%AB%E3%81%8F%E3%81%84-%E5%91%BC%E5%90%B8%E3%81%97%E3%82%84%E3%81%99%E3%81%84-%E7%B9%B0%E3%82%8A%E8%BF%94%E3%81%97%E4%BD%BF%E3%81%88%E3%82%8B-SS%E3%82%B5%E3%82%A4%E3%82%BA4%E6%9E%9A%E7%B5%84/dp/B08F725R4K/ref=zg_bs_kitchen_home_1?_encoding=UTF8&psc=1&refRID=69W2MBGRT6S8E3WYBSCH

## ２
以下のようなランキング商品ページから商品の一覧をスクレイピングしてみましょう<BR>
（必要情報：商品名、商品ページへのURL）
https://www.amazon.co.jp/gp/bestsellers/kitchen/ref=zg_bs_kitchen_home_all?pf_rd_p=234a2e41-c662-4f1c-987f-e3b33cc421ff&pf_rd_s=center-1&pf_rd_t=2101&pf_rd_i=home&pf_rd_m=AN1VRQENFRJN5&pf_rd_r=69W2MBGRT6S8E3WYBSCH&pf_rd_r=69W2MBGRT6S8E3WYBSCH&pf_rd_p=234a2e41-c662-4f1c-987f-e3b33cc421ff

## ３
レッスン１，２を組み合わせて、ランキング商品ページを指定したら商品をすべてスクレイピングし
情報を取得できるようにしてみましょう（最大１００商品）

## ４
eelを使用して、ランキング商品ＵＲＬを入力として指定し、レッスン３でスクレイピングした結果をＣＳＶに出力できるようにしてみましょう。
なお、このＣＳＶファイルはＥＸＣＥＬで正常に表示できる必要があります。

## ５
ASIN一覧を直接指定して情報を取得できるようにしてみよう。
その際、１で作った関数を使いまわそう。
