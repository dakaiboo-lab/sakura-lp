# Sakura LP

女性向けコミュニティ「Sakura｜一人で頑張らない働き方」の静的LPです。

## 開き方

`index.html` をブラウザで開くと表示できます。

## 申し込みURLの変更

申し込み先URLは `script.js` の先頭にある `CTA_URL` を変更してください。

```js
const CTA_URL = "https://lin.ee/63XROGn";
```

HTML内のCTAリンクにも仮URLを入れていますが、表示時に `script.js` が同じURLへ統一します。

## 画像の差し替え

ヒーロー画像は `assets/hero-sakura.png` です。

文字なし・顔なしの画像に差し替える場合は、同じファイル名で置き換えるか、`index.html` 内の画像パスを変更してください。

## ファイル構成

- `index.html`: ページ本文、OGP、FAQ
- `styles.css`: デザイン、レスポンシブ、スクロール表示アニメーション
- `script.js`: CTA URLの統一、FAQの開閉、スクロール表示
- `assets/hero-sakura.png`: 生成したヒーロー画像
