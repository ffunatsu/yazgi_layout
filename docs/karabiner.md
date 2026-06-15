# Karabiner変換作業メモ

- 「やまぶきRの設定ファイル(*.yab)をおおよそKarabiner-ElementsのJSONにするやーつ」 https://potting.syuriken.jp/webApps/Yama2Kara/index.html を使用。

## 手修正

（メモ: いずれも、diffをみるとわかりやすいです。）

- `／` のために、一部 "to" に "option" が入ってしまうので "option" をすべて除去
- "q" などが謎に "hyphen" になってしまうので修正
- なぜか "f", "e" などが単打でオンになってしまうので、修正
- タイピング練習用の場合、二箇所修正が必要な点に留意