---
title: web production
marp: true
header: 
author: YUKI TAMURA
theme: class
footer: web production
paginate: true
---
# Web制作の沿革とその流れ

## Web制作は、**ウェブサイト**や**ウェブアプリケーション**を作成するプロセス
- **主要な要素**:
  - A.  デザイン
  - B.  開発
  - C.  コンテンツ管理

---
# web ページとは？
インターネット上に存在する文書で、その骨格はHTML（HyperText Markup Language）で作成されています。
![bg right 80%](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSj5K08rKxUEHZsgxTHElnQc6bFEmuVzD6FUg&s)

---
# Webアプリケーションとは？

インターネット上で利用できるアプリケーション。インストール不要で、接続があればパソコンやスマホからアクセス可能。
![bg right](https://pantograph.co.jp/app/wp-content/uploads/blog/2019/11/wa2.png)

---
## WebアプリとWebサイトの違い

Webサイト: 複数のWebページを組み合わせたもので、主に静的な情報提供（文章や画像の閲覧）。
Webアプリ: コメント投稿、商品購入、マップ表示などの多機能を持ち、ユーザーと双方向のコミュニケーションが可能。

---
## ネイティブアプリとの違い

## 利用経路:
ネイティブアプリ: スマホやPCにダウンロードして使用（App StoreやGoogle Play Storeから）。
Webアプリ: Webブラウザで直接アクセスして使用。
## 動作の違い:
ネイティブアプリ:端末のシステムを利用し、通常は動作が早い。
Webアプリ:インターネット接続が必要だが、インストール不要で手軽に利用できる。

---
# A. デザイン要素

- **ユーザーエクスペリエンス (UX)**
  - ユーザーがサイトを使いやすいと感じるかどうか。

- **ユーザーインターフェース (UI)**
  - ユーザーとサイトの接点。ボタン、ナビゲーションメニューなど。

![bg left ](https://www.itra.co.jp/uploads/media/2020/06/20200630105533.jpg)

---
![](https://www.unprinted.design/static/1361193eb6a9a97bda8a210f60cff92b/06f43/22.webp)

---
![](https://blog.nijibox.jp/wp-content/uploads/2019/10/201218_CREATIVE_BLOG-245-1@2x.png)

---
![](https://blog.nijibox.jp/wp-content/uploads/2019/10/201218_CREATIVE_BLOG-245-2@2x.png)

---
# B. 開発
## 開発は、ウェブサイトやウェブアプリケーションを作成するプロセス
- **Web制作の技術要素**:
  - HTML
  - CSS
  - JavaScript
![bg left ](https://www.itra.co.jp/uploads/media/2020/06/20200630105533.jpg)

---
# Web制作の技術要素

1. **HTML (HyperText Markup Language)**
   - ウェブページの構造を定義。
   - 要素: 見出し、段落、リスト、リンク、画像など。

2. **CSS (Cascading Style Sheets)**
   - ウェブページのスタイルやレイアウトを設定。
   - 色、フォント、余白、配置などを制御。

3. **JavaScript**
   - ウェブページに動的な機能を追加。
   - ユーザーとのインタラクションを可能に。
![bg right 100%](https://goat-inc.co.jp/wp-content/uploads/2022/02/htmlcssjs-sum.png)

---
![](https://fastcoding.jp/blog/wp-content/uploads/2017/03/html_css_js_08.png)


---
![bg center 70%](https://creating-homepage.com/wp-content/uploads/2021/09/1061-01.jpg)

---
# C. コンテンツ管理

Web開発におけるコンテンツ管理とは、ウェブサイトやウェブアプリケーションのコンテンツ（テキスト、画像、動画など）を効率的に作成、編集、公開、削除するプロセスを指します。これには、コンテンツ管理システム（CMS）を使用することが一般的で、ユーザーは専門的な技術知識がなくても、簡単にコンテンツを管理できるようになります。コンテンツ管理は、情報の更新や整理を迅速に行うことで、ウェブサイトの鮮度やユーザーエクスペリエンスを向上させる重要な要素です。
![bg left ](https://www.itra.co.jp/uploads/media/2020/06/20200630105533.jpg)

---- 
![50%](https://www.hitachi-solutions.co.jp/digitalmarketing/sp/shared/images/column/column_detail9_03.jpg)

---
## CMSによるコンテンツ編集例
アンケートフォームに入力する体験に近い感覚で、ホームページの情報を更新することができる。
![bg right 70%](https://delaymania.com/wp/wp-content/uploads/2015/03/wordpress-post-howto-02.png)

---
## SEO (Search Engine Optimization)

- 検索エンジンでの順位を向上させるための技術。
- キーワードの最適化、メタタグの設定、コンテンツの質などが重要。
![bg right 90%](https://satori.marketing/wp-content/uploads/2023/05/a8d738e08cef0e8cd7654af7d3ea0548.webp)

---
# まとめ

- Web制作は多様な要素から成り立つ。
- HTML、CSS、JavaScriptを理解することが基本。
- デザインやコンテンツ管理も重要な要素である。

>確認テスト
https://drive.google.com/file/d/1SSM_MI0cwu-TCX7D1_62pwEwiYGs43tT/view?usp=sharing

---
# HTMLを書いてみよう

---
# https://jsfiddle.net
webエディタを使用することで、環境準備不要でコーディングを始めることができる。

---
## <body></body>タグの中身がページに表示される
```html
<body>
  <header>
    <h1>自己紹介</h1>
    <!-- ページのメインタイトルとして表示される見出し -->
  </header>
</body>
```

---
## <section></section>タグでセクションを明示的に分ける
```html
<!-- 自己紹介セクション -->
  <section>
    <h2>名前：山田太郎</h2>
    <!-- 自己紹介の中で名前を表示するための見出し -->

    <p>
      私はWeb開発を学んでいる山田太郎です。趣味は映画鑑賞とハイキングです。最近、HTMLやCSSを学び始めたばかりですが、楽しく学んでいます。
    </p>
    <!-- 自己紹介の内容としての段落。自分について簡単に説明しています -->
  </section>
```

---
## <ul><li></li></ul>タグでリストを追加する
```html
<!-- 趣味・興味のリストを表示するセクション -->
  <section>
    <h3>趣味・興味</h3>
    <!-- このセクションに関連するサブ見出し -->
    <ul>
      <!-- リストの始まり -->
      <li>映画鑑賞</li>
      <li>読書</li>
      <li>カフェ巡り</li>
      <!-- 各趣味をリストとして表示 -->
    </ul>
  </section>
  ```

  ---
## <img>タグで画像を追加する

```html
<!-- 好きな食べ物を表示するセクション -->
<section>
    <h3>好きな食べ物</h3>
    <ul>
      <li>ステーキ</li>
    </ul>  
    <img src="" class="profile-img">
  </section>
  ```

  ---
  ## <a>タグでリンクを設定する
  ```html
  <!-- 連絡先情報を表示するセクション -->
  <section class="contact-info">
    <h3>連絡先情報</h3>
    <!-- 連絡先情報に関連するサブ見出し -->

    <p>Email: <a href="mailto:taro@ex.com">taro@ex.com</a></p>
    <!-- メールアドレスを表示し、クリックするとメールクライアントが開くように設定 -->
  </section>
   ```

   ---
HTML全文
```html
<body>
  <!-- サイト全体のヘッダー -->
  <header>
    <h1>自己紹介</h1>
    <!-- ページのメインタイトルとして表示される見出し -->
  </header>

  <!-- 自己紹介セクション -->
  <section>
    <h2>名前：山田太郎</h2>
    <!-- 自己紹介の中で名前を表示するための見出し -->

    <p>
      私はWeb開発を学んでいる山田太郎です。趣味は映画鑑賞とハイキングです。最近、HTMLやCSSを学び始めたばかりですが、楽しく学んでいます。
    </p>
    <!-- 自己紹介の内容としての段落。自分について簡単に説明しています -->
  </section>

  <!-- 趣味・興味のリストを表示するセクション -->
  <section>
    <h3>趣味・興味</h3>
    <!-- このセクションに関連するサブ見出し -->
    <ul>
      <!-- リストの始まり -->
      <li>映画鑑賞</li>
      <li>読書</li>
      <li>カフェ巡り</li>
      <!-- 各趣味をリストとして表示 -->
    </ul>
  </section>
  
  <section>
    <h3>好きな食べ物</h3>
    <ul>
      <li>ステーキ</li>
    </ul>  
    <img src="https://x.gd/uCmWi" class="profile-img">
  </section>

  <!-- 連絡先情報を表示するセクション -->
  <section class="contact-info">
    <h3>連絡先情報</h3>
    <!-- 連絡先情報に関連するサブ見出し -->

    <p>Email: <a href="mailto:taro@ex.com">taro@ex.com</a></p>
    <!-- メールアドレスを表示し、クリックするとメールクライアントが開くように設定 -->
  </section>
</body>
```

---
# CSSを書いてみよう

---
## タグ内のスタイルを指定する
```css
body {
    font-family: Arial, sans-serif;
    /* ページ全体で使われるフォントを指定。Arialがなければデフォルトでsans-serif */

    background-color: #f4f4f4;
    /* ページの背景色を明るいグレーに設定 */

    color: #333;
    /* テキストの色を濃いグレーに設定 */

    margin: 0;
    /* ページ全体の余白をゼロにして、ブラウザのデフォルトの余白を消去 */

    padding: 20px;
    /* ページのコンテンツに20ピクセルの内側余白を適用 */
}
/* ページのメインタイトルにスタイルを適用 */
h1 {
    color: #4CAF50;
    /* タイトルの色を緑色に設定 */
}

/* 段落にスタイルを適用 */
p {
    line-height: 1.6;
    /* テキストの行間を設定して、読みやすく */
}
```

---
## クラスを指定してのスタイルを指定する
```css
/* プロフィール画像のスタイル */
.profile-img {
    border-radius: 50%;
    /* 画像を円形に表示するために、ボーダーの半径を設定 */
    
    width: 150px;
    /* 画像の幅を150ピクセルに固定 */
    
    height: 150px;
    /* 画像の高さも150ピクセルに固定 */
}

/* 連絡先情報セクションのマージンを調整 */
.contact-info {
    margin-top: 20px;
    /* 上部に20ピクセルのマージンを追加 */
}
```

---
CSS全文
```css
/* ページ全体のスタイル */
body {
    font-family: Arial, sans-serif;
    /* ページ全体で使われるフォントを指定。Arialがなければデフォルトでsans-serif */

    background-color: #f4f4f4;
    /* ページの背景色を明るいグレーに設定 */

    color: #333;
    /* テキストの色を濃いグレーに設定 */

    margin: 0;
    /* ページ全体の余白をゼロにして、ブラウザのデフォルトの余白を消去 */

    padding: 20px;
    /* ページのコンテンツに20ピクセルの内側余白を適用 */
}

/* ページのメインタイトルにスタイルを適用 */
h1 {
    color: #4CAF50;
    /* タイトルの色を緑色に設定 */
}

/* 段落にスタイルを適用 */
p {
    line-height: 1.6;
    /* テキストの行間を設定して、読みやすく */
}

/* プロフィール画像のスタイル */
.profile-img {
    border-radius: 50%;
    /* 画像を円形に表示するために、ボーダーの半径を設定 */
    
    width: 150px;
    /* 画像の幅を150ピクセルに固定 */
    
    height: 150px;
    /* 画像の高さも150ピクセルに固定 */
}

/* 連絡先情報セクションのマージンを調整 */
.contact-info {
    margin-top: 20px;
    /* 上部に20ピクセルのマージンを追加 */
}
```

---
# 技術スタック（使用言語）とファイルの管理

---
![bg right 80%](https://xs691486.xsrv.jp/wp-content/uploads/2023/10/フロントエンドとバックエンドとは何か？%E3%80%802000×2000.jpg)

## 主な技術スタック
### フロントエンド
- HTML, CSS, JavaScript
### バックエンド
- PHP, Java, Ruby

---
# 初回のファイル配置
1. ホームページファイルの開発
2. ドメインの作成
3. サーバーへファイルのアップロード

![bg right 90%](https://monoledge.com/img/hp_sikumi.png)

---
![bg 80%](https://monoledge.com/img/html_page_server.png)

