# 畠山広聖 研究者ウェブサイト

公開URL： https://kosei103.github.io/ （英語版は `/en/`）

## 文章を更新する

GitHub のファイルを開き、鉛筆アイコン「Edit this file」で編集して「Commit changes」で保存すると、GitHub Pages が自動公開します。`main` ブランチのルートを公開しています。

| 掲載先 | 日本語 | 英語 |
| --- | --- | --- |
| ホーム、研究紹介、プレスリリース、受賞歴、経歴、連絡先 | `index.html` | `en/index.html` |
| 論文・プレプリント | `publications/index.html` | `en/publications/index.html` |
| 発表（日英共通） | `talks/index.html` | 同じページを表示 |
| 公開資料 | `resources/index.html` | `en/resources/index.html` |
| 教育歴 | `teaching/index.html` | `en/teaching/index.html` |
| 見た目 | `style.css` | 共通 |

論文と発表は `<ol reversed>` の先頭に `<li>…</li>` を追加すると、最新を上に置いたまま最も古い項目が1になるよう番号が自動更新されます。論文は日英両方、発表は `talks/index.html` だけを更新してください。

発表は日英共通の `talks/index.html` だけを編集します。英語側の `/en/talks/` は共通ページへ転送されます。同じページ内で「国際学会」と「国内学会」の一覧を分けています。それぞれの `<ol reversed>` に項目を追加すると、その分類内で番号が振り直されます。各項目は学会名・形式・年月の次に発表題目を入力してください。

資料を公開するときは `files/` にアップロードし、日英の `resources/index.html` にリンク、説明、公開日、版、ライセンスを追記します。公開リポジトリには権利を確認したファイルだけ置いてください。

新しいページを作った場合のみ `sitemap.xml` にURLを追記します。サイト所有者確認用の `index.html` 内の `google-site-verification` メタタグは残してください。
