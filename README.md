# VORLEM 公式サイト

VORLEMのブランド公式サイト用の静的HTML/CSSです。

## ファイル構成

```text
.
├── index.html
├── privacy.html
├── style.css
└── images/
    ├── logo.png
    ├── hero.jpg
    ├── product.jpg
    ├── pump.jpg
    ├── compact.jpg
    └── set.jpg
```

画像は未配置でも表示が崩れにくいように、HTML/CSS側でプレースホルダーを用意しています。実際に公開する前に、上記の画像ファイルを `images` フォルダへ配置してください。

## Xserverへのアップロード手順

1. Xserverのサーバーパネル、またはFTPソフトにログインします。
2. `vorlem.com` の公開フォルダを開きます。一般的には `public_html` 配下の対象ドメインフォルダです。
3. `index.html`、`privacy.html`、`style.css`、`images` フォルダをアップロードします。
4. ブラウザで `https://vorlem.com/` を開き、トップページが表示されるか確認します。
5. `https://vorlem.com/privacy.html` を開き、プライバシーポリシーが表示されるか確認します。

## 公開前チェック

- `images` フォルダに必要な画像が入っているか
- ヘッダーの各メニューが正しい位置へ移動するか
- お問い合わせメールアドレスが `contact@vorlem.com` で問題ないか
- LINE問い合わせやAmazonリンクの正式URLが決まっている場合、`href="#"` を差し替えたか
- スマートフォン表示で文字やボタンがはみ出していないか

## 編集メモ

- ブランドカラー：`#2E4A36`
- 背景色：`#F5F2EC`
- 文字色：`#2B2B2B`
- 誇大表現や、実績を断定する表現は避けています。
- Amazonリンク、LINE問い合わせは未確定前提で `#` にしています。
