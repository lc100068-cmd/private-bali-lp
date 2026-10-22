# private -BALI- JSAアイシングクッキー認定講師講座 LP

岡山市北区のアイシングクッキー教室 private -BALI- の、認定講師講座のランディングページです。
スマホで見やすい1ページ構成で、`index.html` 1ファイルで動きます。

## ファイル構成

| ファイル | 内容 |
| --- | --- |
| `index.html` | LP本体 |
| `images/instructor.jpg` | 講師写真（縦長 3:4 推奨）。置くと自動で表示されます |
| `images/hero.jpg` | トップの背景に薄く敷く写真（横長） |
| `images/ogp.jpg` | SNSでシェアしたときのサムネイル画像（1200×630 推奨） |

画像がまだ無いあいだは、講師写真の枠に「講師写真（差し替え）」と表示されます。

## 公開前に差し替えるところ

### リンク先URL

`index.html` の一番下にある `LINKS` に貼り付けます。空のままのボタンは表示されません。

```js
var LINKS={
  line:'',   // LINE公式アカウントの友だち追加URL（https://lin.ee/...）
  form:'',   // 申し込みフォームのURL
  cookpa:'', // クスパの教室ページURL
  policy:''  // レッスンポリシーの記事URL
};
```

### 画像

`images/` フォルダに `instructor.jpg`（講師写真）と `ogp.jpg`（シェア用画像）を入れます。

## GitHub Pages で公開する

1. GitHub のリポジトリで **Settings → Pages** を開く
2. Source を **Deploy from a branch**、Branch を公開したいブランチ・`/ (root)` にして保存
3. 数分後に表示されるURL（`https://<ユーザー名>.github.io/private-bali-lp/`）がLPのURLです
