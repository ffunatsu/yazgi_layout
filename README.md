# 矢次配列 - Yazgi Layout

～～<br>
新下駄配列の哲学を継承しつつ、より覚えやすく身近に。<br>
～～<br>

中指同時シフト・拗音拡張・外来語拡張・清濁同置。<br>
新下駄および、JIS下駄、薙刀式、新JISなどに影響を受けつつ、N-gramを強く意識して設計。

![docs/yazgi_layout.png](docs/yazgi_layout.png)

![docs/yazgi_youon.png](docs/yazgi_youon.png)

## 打ち方

- 左手の★と右手キー → 左上のかな（薄赤色）
- 右手の★と左手キー → 左上のかな（薄赤色）
- 濁音・半濁音も同じく、反対の手のキーと同時押し
  - 薙刀式と同じく、★（薙刀式でいうシフトにあたる）で打たれるキーについても、濁音・半濁音の場合は★は不要なよう設計。
- 小文字についても同じく、キーに薄黄色（右上に記載）で印字のあるキーについては小文字入力が可能
  - 拗音拡張にも留意
- 拗音拡張については、左右の対応するキーを同時押し（例えば、り + よ = りょ）
- 灰色のキーは予備。同時シフトがうまく打てない場合の予備。
- 各種特殊記号（`！`/`？`/`「」`/`（）`）は新下駄やJIS下駄に準ずる。

## 設定ファイル

- やまぶきR (Windows): [Yazgi.yab](./Yazgi.yab)
- 紅皿 (Windows): [Yazgi.bnz](./Yazgi.bnz)
- Karabiner-Elements (macOS): [Yazgi.karabiner.json](./Yazgi.karabiner.json) (Complex modificationsに追加。追加方法は割愛。)

## 設計思想

see [docs/design.md](docs/design.md)
