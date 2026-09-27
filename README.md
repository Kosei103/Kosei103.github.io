# 畠山広聖 研究者ウェブサイト

公開URL： https://kosei103.github.io/ （英語版は `/en/`）

## 文章を更新する

GitHub のファイルを開き、鉛筆アイコン「Edit this file」で編集して「Commit changes」で保存すると、GitHub Pages が自動公開します。`main` ブランチのルートを公開しています。

| 掲載先 | 日本語 | 英語 |
| --- | --- | --- |
| ホーム、研究紹介、プレスリリース、受賞歴、経歴、連絡先 | `index.html` | `en/index.html` |
| 論文・プレプリント | `publications/index.html` | `en/publications/index.html` |
| 発表 | `talks/index.html` | `en/talks/index.html` |
| 公開資料 | `resources/index.html` | `en/resources/index.html` |
| 教育歴 | `teaching/index.html` | `en/teaching/index.html` |
| 見た目 | `style.css` | 共通 |

論文と発表は `<ol reversed>` の先頭に `<li>…</li>` を追加すると、最新を上に置いたまま最も古い項目が1になるよう番号が自動更新されます。日英両方の該当ファイルを更新してください。

資料を公開するときは `files/` にアップロードし、日英の `resources/index.html` にリンク、説明、公開日、版、ライセンスを追記します。公開リポジトリには権利を確認したファイルだけ置いてください。

新しいページを作った場合のみ `sitemap.xml` にURLを追記します。サイト所有者確認用の `index.html` 内の `google-site-verification` メタタグは残してください。
