# 設計思想

## 基本構想

- 新下駄配列の感覚を容易に取得できるように。
- 拗音拡張を覚えやすく。ベースは[JIS下駄](https://github.com/ffunatsu/jis_geta)。

## 影響を受けた配列

- 新下駄: 同時シフト、拗音拡張、外来語拡張
- JIS下駄: 拗音拡張
- 薙刀式: 濁音・半濁音、清濁同置
- 新JIS: 単打かなの配置

## 設計方法

- [wikipedia_ja_ngram](https://github.com/oktopus1959/wikipedia_ja_ngram) などのN-gramを基準に、頻度に基づいた設計
- 新下駄で打ちづらいパターンを極力回避（基本的には、新下駄の打鍵経験から直感・試行錯誤により配置を変更）
- 薙刀式・新JIS・新下駄を参考に、単打をまず設計しつつ、JIS下駄ゆずりの拗音拡張・外来語拡張を実現するために、左右配置を調整

## 配列の名称

- ***Y***et ***A***nother Next (Tsugi = ***zgi***) Japanese Input Layout
  - or/and: ***Y***et ***A***nother ***Z***-***G***eneration ***I***nput Layout
- 作者の作成した配列が、JIS下駄に続いて2作目なので。新下駄の意思を継ぐ意味合いもあり。次の将来的な理想の配列にバトンを渡すまでの橋渡し的意味合い。
