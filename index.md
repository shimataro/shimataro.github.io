---
title: Taro ODASHIMA
---
## 略歴

![Author]({{ site.path.img }}author.jpg){: .author srcset="{{ site.path.img }}author.jpg 1x, {{ site.path.img }}author@2x.jpg 2x"}

岩手県盛岡市生まれ、兵庫県在住。
[名古屋工業大学](https://www.nitech.ac.jp/)工学部 学士課程卒業、[奈良先端科学技術大学院大学](http://www.naist.jp/)情報科学研究科 博士前期課程修了。

学部生時代はジェスチャー（動画像）認識、院生時代はARを研究。

大学院修了後、某SI系企業にソフトウェアエンジニアとして就職。
その後**某マジシャン**のもとで数年働き、今度は**ウェブ系エンジニア**に転向するという自分でもよくわからない経歴。

フロントエンド、バックエンド、データベース、インフラ、なんでもござれのフルスタックエンジニア…を目指して日々修行中。

趣味は**手品**と**プログラミング**と**音楽**。
最近は**イベント登壇**も半ば趣味と化す。

手品が好きな人（見る/やる問わず）、プログラミングが好きな人、音楽が好きな人、お友達になりましょう！

---

## ポートフォリオ

### ブログ

[![欅樹雑記]({{ site.path.img }}galleries/blog@800px.png){: .gallery srcset="{{ site.path.img }}galleries/blog@280px.png 320w, {{ site.path.img }}galleries/blog@560px.png 640w, {{ site.path.img }}galleries/blog@800px.png 800w" sizes="(max-width: 800px) 100vw, 800px"}](https://blog.zelkova.cc/)

主に技術系の内容。たまに全く関係ないことも。

### サービス

#### [QiNeel](https://qineel.com)

オンラインブックマークサービスです。
「お気に入り登録はしたけど、整理整頓が面倒」という人のために作りました。

あらかじめ決めておいたルールで自動整理できるので、毎回フォルダ分けする必要がありません。

### ライブラリ

[![value-schema]({{ site.path.img }}galleries/value-schema@800px.png){: .gallery srcset="{{ site.path.img }}galleries/value-schema@280px.png 320w, {{ site.path.img }}galleries/value-schema@560px.png 640w, {{ site.path.img }}galleries/value-schema@800px.png 800w" sizes="(max-width: 800px) 100vw, 800px"}](https://www.npmjs.com/package/value-schema)

ウェブサービスを作るときに必ず必要になるパラメータ処理を、**簡単に**、**可読性高く**、**宣言的に**行えるNode.js用のライブラリです。

宣言的なインターフェースなので「数値かどうかチェックして、数値でない場合は数値化できるかチェックして、数値化した後に値の範囲をチェックして…」といった**ロジックを実装する必要がありません**。
そのため、可読性が高くバグの少ないコードを簡単に書けます。

[![Install SSH Key]({{ site.path.img }}galleries/install-ssh-key@800px.png){: .gallery srcset="{{ site.path.img }}galleries/install-ssh-key@280px.png 320w, {{ site.path.img }}galleries/install-ssh-key@560px.png 640w, {{ site.path.img }}galleries/install-ssh-key@800px.png 800w" sizes="(max-width: 800px) 100vw, 800px"}](https://github.com/marketplace/actions/install-ssh-key)

[GitHub Actions](https://help.github.com/ja/articles/about-github-actions)の仮想環境内にSSH鍵を登録します。

SSH, SCP, rsync over SSH等のSSH系コマンドで鍵認証できるようになります。

### デザイン

[![Google Slides テンプレート]({{ site.path.img }}galleries/slide@800px.png){: .gallery srcset="{{ site.path.img }}galleries/slide@280px.png 320w, {{ site.path.img }}galleries/slide@560px.png 640w, {{ site.path.img }}galleries/slide@800px.png 800w" sizes="(max-width: 800px) 100vw, 800px"}](https://docs.google.com/presentation/d/1CKcu-bZdQ6zQevIFVKtMqiKlnxQMGP9anAR2B_s39Vo)

**デザインセンス0**の人間が[Googleスライド](https://www.google.com/intl/ja_jp/slides/about/)のテンプレートを作ってみました。
背景とフォントをちょっと工夫するだけで意外とイケるもんです。

ビンテージっぽさを意識して作ったのですが、全然ビンテージになりませんでした。

---

## 過去の作品

昔つくった、今は更新していない作品集です。

### [Cazary](https://shimataro.me/cazary/)

`textarea`をWYSIWYGのリッチエディタに変えるjQueryプラグインです。
[デモページ](https://shimataro.me/cazary/demo.html)も用意してあります。

多言語対応しており、ブラウザの言語設定に応じて表示が変わります。
日本語、英語、ポーランド語、ポルトガル語、ブラジルポルトガル語に対応しています。
日本語と英語以外は外国のユーザが翻訳データを送ってくれました。

もっと高機能なリッチエディタはいくらでもあるのですが、~~メジャーなものばかりを取り上げたら他と差別化できないためか~~シンプルさゆえか外国のサイトでいろいろ紹介されていたりします。

* [Simple Html WYSIWYG Editor Plugin with jQuery - Cazary \| Free jQuery Plugins](https://www.jqueryscript.net/text/Simple-Html-WYSIWYG-Editor-Plugin-with-jQuery-Cazary.html)
* [5+ Freemium jQuery WYSIWYG Plugins \| FormGet](https://www.formget.com/jquery-wysiwyg-plugins/)
* [8 jQuery Plugins for Rich Text Editors \| jQuery By Example](http://www.jquerybyexample.net/2017/04/8-jquery-plugins-for-rich-text-editors.html)
* [Please recommend a good JQuery rich text editor - Stack Overflow](https://stackoverflow.com/questions/1901546/please-recommend-a-good-jquery-rich-text-editor)

そもそもjQuery自体が下火なので現在は更新していません。

### [Maxy](http://maxy.osdn.jp/)

Windows用のシンプルなテキストエディタです。
既存のフレームワークを使わず、C++でWindows APIを直に叩いてスクラッチで作成しました。

マルチスレッドモデルを採用しており、複数ウインドウを開いてもとても少ない消費リソースで動作します。
色分けに対応しています…が、機能的には足りないところが多すぎるので常用には耐えません。

現在はWindowsを使っていないので更新停止しています。

### [Mercury::Regex](http://mercury-regex.osdn.jp/)

C++で書いた正規表現ライブラリです。
誰でも、どんな目的にでも、どんな環境でも、どんな文字型でも、どんなデータ構造でも使える自由度の高い正規表現エンジンを作ることを目的としていました。

メタ文字も自分で設定できるほど~~無駄に~~カスタマイズ性が高いのですが、**自由度に力を入れすぎて**遅かったのと、C++11で標準ライブラリ`std::regex`が導入されたのでお役御免になりました。

作ったのが昔すぎて、**なんでMercuryなのか忘れました**。

---

## 開発関連の活動

ポートフォリオに載せられない開発関連の活動一覧です。

### コミュニティ

#### [World Wide Web Kansai](https://w3k.connpass.com/)

関西のウェブ業界で、特定の技術（言語やフレームワークとか）の勉強会はかなりあるのですが、**Web全般を扱った勉強会がないよねー**ということで知人とコミュニティを作りました。

バックエンド、パフォーマンス、セキュリティ、Web標準（WebGL、Web Components、WebAssembly等々）…他の勉強会では話せないけどぜひ語りたいものがあれば奮ってご参加ください。

もちろん聴講のみもOKです。

### 発表資料

#### [SpeakerDeck](https://speakerdeck.com/shimataro)

ここ数年で**技術系の勉強会で**発表した資料です。

技術系の勉強会以外での登壇は含まれていません。そちらは月イチのペースで登壇しています。

### 執筆記事

#### [読みやすいコードを書くために](https://qiita.com/shimataro999/items/ef6cd838d56f1fe87015)

コーディングやレビューの際に個人的に意識していることをまとめた記事です。

意外と反響が大きくてびっくりしました。
こういう記事は需要があるんですかね。

#### [MDN](https://wiki.developer.mozilla.org/ja/docs/Web)

たまーーに更新します。
ちょっとした翻訳や誤字脱字の修正レベルなので「執筆」と呼べるレベルではありませんが。

---

## 哲学・行動原理

### ブラッシュアップ

* 一度作って満足しない。
* 良くないものを良く、良いものをより良く。

### シンプルデザイン

* 完璧なデザインとは、付け加えるものがなくなったものではなく、取り去るものがなくなったもの。

### 再定義

* あらゆるものを見直し、最適な形を模索する。

### アーティスト

* 芸人が与えてくれるのは、**あなたが今まさに欲しいもの**。芸術家が与えてくれるのは、**あなた自身が欲しいかどうかすらわかっていないもの**。

### 長期的・総合的な利益

* 一時的に生産性を落としてでも、今後の生産性のための準備を。

### ストレスフリー

* わかりにくい、遅い、面倒、覚えることが多い…あらゆるストレスを取り除く。
