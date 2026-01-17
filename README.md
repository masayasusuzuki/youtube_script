# YouTube運用ディレクトリ

## 概要
YouTube「じっくりAI駆動開発」チャンネルの運用に関するファイルを管理するディレクトリ。

## ディレクトリ構成

```
youtube/
├── profile/           # 自己紹介・実績
│   ├── profile.md     # プロフィール
│   └── portfolio.md   # 実績・事例
├── strategy/          # 戦略・企画系
│   ├── channel.md     # チャンネル設計
│   ├── content-ideas.md   # コンテンツネタ
│   └── competitors.md # 競合分析
├── scripts/           # 台本
│   └── {番号}_{動画名}/
│       ├── script.md      # 台本本体
│       └── sources/       # ソース情報・参考資料
├── thumbnails/        # サムネ素材・案
└── assets/            # 共通素材（ロゴ等）
```

## ルール

### 台本フォルダの命名規則
- `{3桁の番号}_{動画の内容}`
- 例: `001_cursor-intro`, `002_claude-code-intro`

### 台本フォルダの構成
- `script.md` - 台本本体
- `sources/` - 参考にした記事、公式ドキュメント、メモなど

### ファイル命名
- すべて小文字
- スペースの代わりにハイフン `-` を使用
# youtube_script
