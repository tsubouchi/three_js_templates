# Three.js プロジェクトルール

## GitHubプッシュルール

このプロジェクトでは、以下のディレクトリのみをGitHubリポジトリにプッシュします：

- `short/`: 短いThree.jsデモやサンプルを格納
- `slides/`: プレゼンテーション用のファイルを格納
- `caption/`: キャプション付きのデモを格納

以下のディレクトリやファイルはGitHubにプッシュしないでください：

- `.specstory/`: ローカルの作業ログやメタデータ
- `h`で始まるファイル: 一時ファイルやログファイル
- 他の一時ファイルやディレクトリ

## コードスタイル

- HTML/JS混在ファイル: 各Three.jsデモは独立した単一HTMLファイルとして作成します
- コードフォーマット: インデントは2スペース
- コメント: 重要な処理や複雑な部分には日本語コメントを付ける

## ファイル命名規則

- すべてのファイル名は小文字で、単語の区切りはアンダースコア(_)を使用します
- 例: `spinning_cube.html`, `particle_system.html`

## バージョン管理

- 重要な機能追加や大きな変更の際は、コミットメッセージに詳細な説明を記載
- 小さな変更や修正は簡潔なコミットメッセージで構いません

## プロジェクト構造

```
Three_js/
├── short/             # 短いThree.jsデモ集
│   ├── spinning_square.html
│   ├── particle_system.html
│   └── ...
├── slides/            # プレゼンテーション資料
│   ├── presentation.html
│   └── ...
├── caption/           # キャプション付きデモ
│   ├── caption_test.html
│   └── ...
├── .cursor/           # Cursorエディタ設定
│   └── rules/         # プロジェクトルール
│       └── basic.design.md
└── .gitignore         # Git除外設定
``` 