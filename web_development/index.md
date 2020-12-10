---
layout: default
title: product
---

# Development
公開している開発物を紹介します。

## Owner
### [procon-qa](https://procon-qa.herokuapp.com/#/)
<img width="387" alt="スクリーンショット 2020-10-04 18 40 39" src="https://user-images.githubusercontent.com/47474057/95012165-219de880-0671-11eb-953c-e922506883a7.png">

![procon-qa](https://user-images.githubusercontent.com/47474057/95019358-d3540e00-069f-11eb-853b-aa5ac7dd1479.gif)


競技プログラミング専用の Q&A サイトです。

一通りの CRUD 機能を持った Web アプリケーションの開発経験をつけたいというモチベーションがあり、開発を始めました。
途中で挫折せず、公開することが最大の目標であり、そのために以下のような工夫を取り入れました。

- 早い段階で β 版を公開し、ユーザーからフィードバックを得る
- とりあえず動くものを作ることを優先する（done is better than perfect）

結果、当初の目標通り公開することができました。
一方で、安定して運用・保守していくためには、仕様変更に耐えうるアーキテクチャを設計したり、十分なテストコードを書く必要があることを実感しました。
また、ユーザ数や質問数が増えてもパフォーマンスが低下しないような、パフォーマンスチューニングをする必要もあると感じています。

誰でも気軽に質問ができるプラットフォームを作り出し、価値を生み出したいです。

 - 使用技術：Go, echo, Vue, TypeScript, PostgreSQL, Docker

### [GRAPH × GRAPH](https://hello-world-494ec.firebaseapp.com/)
<img width="266" alt="スクリーンショット 2020-10-04 18 41 33" src="https://user-images.githubusercontent.com/47474057/95012181-4003e400-0671-11eb-8932-18a1535a6deb.png">

![graph graph](https://user-images.githubusercontent.com/47474057/95019467-6f7e1500-06a0-11eb-8b94-92ea1b3efc51.gif)

グラフ理論可視化サイトです。
go 製の CLI ツール[ggg](https://github.com/monkukui/ggg) を使って起動できます。

競技プログラミングにおいて、サンプルテストケースの確認に役に立ちます。
かなり多くの人から Twitter でフィードバックをもらい、ユーザーに使ってもらえる喜びを感じています。
「GRAPH × GRAPH のおかげで AtCoder のレートが上がった！！」という声を聞いてとても嬉しかったです。

 - 使用技術：Vue, vis.js

### [ggg(go GRAPH × GRAPH)](https://github.com/monkukui/ggg)
![ggg](https://user-images.githubusercontent.com/47474057/95019098-83c11280-069e-11eb-9754-1341b13ede1b.gif)

GRAPH × GRAPH をコマンドラインから起動するための CLI ツールです。
ブラウザからサイトを検索する時間ロスを無くします。

 - 使用技術：Go, cobra
 
### [ac-library-go](https://github.com/monkukui/ac-library-go)
[AtCoder Library](https://atcoder.jp/posts/517) を Golang に移植する OSS 活動を主催しています。
AtCoder Library は、[AtCoder](https://atcoder.jp/) が C++ で実装したアルゴリズムのライブラリであり、AtCoder 上のコンテストで使用できます。
他言語への移植を促す[ツイート](https://twitter.com/atcoder/status/1302977048017694720?s=20) が AtCoder によって投稿されたのをきっかけとして、[ac-library-go](https://github.com/monkukui/ac-library-go) を立ち上げました。
様々なアルゴリズムやデータ構造を Go によって実装しています。

 - 使用技術：Go, Algorithm

### [gpcg(go-procon-code-generator)](https://github.com/monkukui/gpcg)
複数ファイルを単一ファイルにまとめる Go の静的解析ツールを開発しました。
競技プログラミングでは、単一ファイルで記述されたコードを WEB 上で提出しなければいけないため、このツールが役に立ちます。
将来的には、ac-library-go でも使えるようにします。
[ブログ](https://monkukui.hatenablog.com/entry/2020/09/07/183114)

 - 使用技術：Go, 静的解析


### [Visualize Binary Search](https://visualize-binary-search.firebaseapp.com/#/search-age)
「二分探索」を理解するためのアプリケーションです。
「北海道大学 IT サークル」主催の LT 会で登壇した時に使用しました。

- 使用技術：Vue

### その他
- 北大学部 3 年の授業出席システム
    - 使用技術：GAS, Slack api など

- 研究室の出席管理システぷ
    - 使用技術：Vue, Rust など

## Collaborator
### [Library Checker](https://judge.yosupo.jp/)
Library Checker とは、アルゴリズムを実装したプログラムの正当性を、ブラウザ上でテストするための OSS です。
木の直径を求める問題 [Tree Diameter](https://judge.yosupo.jp/) を作成し、OSS に貢献しました。
[ブログ](https://monkukui.hatenablog.com/entry/2020/05/21/133032)

- 使用技術：C++
### [A Tour of Go](https://go-tour-jp.appspot.com/concurrency/7)
Golang の公式チュートリアルの一部を翻訳しました。

### [Logpose](https://logpose-13labo.firebaseapp.com/)
札幌就活情報共有サイトです。
トップページの一部と検索ページを担当しました。
