## YAML スキーマ

| key    | 説明                           | 必須 |
|--------|--------------------------------|------|
| type   | roadmap / org / card / …       | ✔ |
| text   | 付箋やカードに表示する文字        | ✔ |
| frame  | 置くフレーム名（省略可＝自動）      |   |
| quarter| roadmap 用 (例 2025Q3)          |   |
| id     | org 用ノード ID                 |   |
| parent | org 用 親ノード ID              |   |
| start  | card 用 開始日 (YYYY-MM-DD)     |   |
| end    | card 用 終了日 (YYYY-MM-DD)     |   |
