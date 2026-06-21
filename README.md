# VORLEM 公式サイト

VORLEMの輸入販売事業・取扱商品紹介サイト用の静的HTML/CSSです。

公開URLは `https://store.vorlem.com/` を想定しています。

## ファイル構成

```text
.
├── index.html
├── products.html
├── privacy.html
├── style.css
└── images/
    ├── product.jpg
    ├── product-main.png
    ├── product-pump-storage.png
    ├── product-comfort.png
    ├── pump.jpg
    ├── compact.jpg
    └── set.jpg
```

画像は未配置でも表示が崩れにくいように、HTML/CSS側でプレースホルダーを用意しています。実際に公開する前に、上記の画像ファイルを `images` フォルダへ配置してください。

## Xserverへのアップロード手順

1. Xserverのサーバーパネル、またはFTPソフトにログインします。
2. `vorlem.com` の公開フォルダを開きます。一般的には `public_html` 配下の対象ドメインフォルダです。
3. `index.html`、`products.html`、`privacy.html`、`style.css`、`images` フォルダをアップロードします。
4. ブラウザで `https://store.vorlem.com/` を開き、トップページが表示されるか確認します。
5. `https://store.vorlem.com/privacy.html` を開き、プライバシーポリシーが表示されるか確認します。
6. `https://store.vorlem.com/products.html` を開き、取扱商品一覧が表示されるか確認します。

## 公開前チェック

- `images` フォルダに必要な画像が入っているか
- ヘッダーの各メニューが正しい位置へ移動するか
- 取扱商品一覧ページへ移動できるか
- トップページに事業者情報が表示されているか
- 商品一覧ページに取扱カテゴリの詳細、返品・交換案内が表示されているか
- お問い合わせメールアドレスが `contact@vorlem.com` で問題ないか
- Amazonリンクの正式URLが決まっている場合、`href="#"` を差し替えたか
- 事業者の正式名称、所在地、販売条件など、公開前に確定情報へ差し替える必要がないか
- スマートフォン表示で文字やボタンがはみ出していないか

## GitHub Pages カスタムドメイン

GitHub Pagesで公開する場合は、リポジトリ直下の `CNAME` に以下を設定しています。

```text
store.vorlem.com
```

このサイトは静的HTML/CSSで作成しており、ViteやReact Routerは使用していません。CSS、画像、内部リンクは旧GitHub Pagesサブパス前提ではなく、`store.vorlem.com` のルートで表示できる相対パスにしています。

## 編集メモ

- ブランドカラー：`#2E4A36`
- 背景色：`#F5F2EC`
- 文字色：`#2B2B2B`
- 誇大表現や、実績を断定する表現は避けています。
- LINE問い合わせは `https://lin.ee/nqQ9LYh` に設定しています。
- Amazonリンクは未確定前提で `#` にしています。
- 個人名・個人住所は掲載していません。
