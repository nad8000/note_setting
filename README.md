# 概要

VSCodeの個人のメモ用設定を共有するためだけのリポジトリ

Ctrl + Shift + P
「VSNotes: Run setup」

## ショートカット登録

Ctrl + shift + P
「VSNotes: Create a New note」 のとなりの設定マーククリックしてショートカットキーを追加する
※Alt+Nで登録してる

## スニペット登録

ファイル→ユーザー設定→ユーザースニペットの構成→markdown

```json
{
  "vsnote_template_tags": {
    "prefix": "vsnote_template_note",
    "body": [
      "---",
      "tags:",
      "  - main$1",
      "---",
      "\n",
      "# Title",
      "\n",
    ],
    "description": "Template with Tags",
  }
}
```
