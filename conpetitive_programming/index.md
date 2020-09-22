---
layout: default
title: conpetitive programming
---

# Conpetitive Programming

競技プログラミングは、大学 2 年の春から現在（2020/09/24 更新）まで続けています。
現在は、[北海道大学競技プログラミングサークル HCPC](https://hcpc-hokudai.github.io/)の部長を務めています（詳しくは、[Organization](organization/) をご覧ください）。
競技プログラミングの実績や、関連するエンジニアリング活動について紹介します。

## Account
- AtCoder：青（最高レーティング：1983）（[monkukui](https://atcoder.jp/users/monkukui)）
    - 1299 位/63798、上位 2 % の水準（2020/09/24 現在）
- Codeforces：青（[monkukui0283](https://codeforces.com/profile/monkukui0283)）
- PAST：エキスパート
    - PAST（アルゴリズム実技検定）については[こちら](https://past.atcoder.jp)
- Paiza：S ランク

## Achievement
- [ACM-ICPC 2017 国内予選](https://icpc.iisf.or.jp/2017-tsukuba/domestic)
    - 順位：204/358
- [ACM-ICPC 2018 国内予選](https://icpc.iisf.or.jp/2018-yokohama/domestic)
    - 順位：60/388
- [ACM-ICPC 2019 国内予選](https://icpc.iisf.or.jp/2019-yokohama/2019kokunaiyosen)
    - 順位：73/458
- [CODE THANKS FESTIVAL 2018 本戦](https://www.recruit-jinji.jp/recruitment/code_fes)
    - 順位：49/98
- [DISCO presents ディスカバリーチャンネル コードコンテスト2019 本戦](https://www.discoverychannel.jp/campaign/ddcc2019/)
    - 順位：138/196
- [第一回日本最強プログラマー学生選手権決勝](https://atcoder.jp/contests/jsc2019-final)
    - 順位：150/185
- [AtCoder Beginer Contest 157](https://atcoder.jp/contests/abc157)
    - 順位：13/6543

## [解いた問題数](https://rating-history.herokuapp.com/index.html?handle_topcoder=&handle_codeforces=monkukui0283&handle_atcoder=monkukui&handle_aoj=monkukui&handle_yukicoder=monkukui&handle_librarychecker=monkukui&select_handle=TAB)（2020/09/24 現在）

|サイト|解いた問題数|
|Codeforces|163|
|AtCoder|1437|
|AOJ|409|
|yukicoder|0|
|library-checker|13|
|Sum|2026|

## 競技プログラミングに関連する開発

### [Algorithm Library](https://github.com/monkukui/Library)
競技プログラミングで普段使用する、アルゴリズムやデータ構造の実装です。

### [Library Checker](https://judge.yosupo.jp/)
Library Checker とは、アルゴリズムを実装したプログラムの正当性を、ブラウザ上でテストするための OSS です。
木の直径を求める問題 [Tree Diameter](https://judge.yosupo.jp/) を作成し、OSS に貢献しました。
[ブログ](https://monkukui.hatenablog.com/entry/2020/05/21/133032)

### [ac-library-go](https://github.com/monkukui/ac-library-go)
[AtCoder Library](https://atcoder.jp/posts/517) を Golang に移植する OSS 活動を主催しています。
AtCoder Library は、[AtCoder](https://atcoder.jp/) が C++ で実装したアルゴリズムのライブラリであり、AtCoder 上のコンテストで使用できます。
他言語への移植を促す[ツイート](https://twitter.com/atcoder/status/1302977048017694720?s=20) が AtCoder によって投稿されたのをきっかけとして、[ac-library-go](https://github.com/monkukui/ac-library-go) を立ち上げました。
様々なアルゴリズムやデータ構造を Go によって実装しています。

### [gpcg(go-procon-code-generator)](https://github.com/monkukui/gpcg)
複数ファイルを単一ファイルにまとめる Go の静的解析ツールを開発しました。
競技プログラミングでは、単一ファイルで記述されたコードを WEB 上で提出しなければいけないため、このツールが役に立ちます。
将来的には、ac-library-go でも使えるようにします。
[ブログ](https://monkukui.hatenablog.com/entry/2020/09/07/183114)

### [GRAPH × GRAPH](https://hello-world-494ec.firebaseapp.com/index.html)
グラフ理論の可視化サイトです。
go 製の CLI ツール[ggg](https://github.com/monkukui/ggg) を使って起動できます。

### [procon-qa](https://procon-qa.herokuapp.com/)
競技プログラミング専用の Q&A サイトです。

### [ggg(go GRAPH × GRAPH)](https://github.com/monkukui/ggg)
GRAPH × GRAPH を起動するための CLI ツールです。
