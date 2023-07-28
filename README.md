# 明細書Lint 1.3.0のインストール

## １．何をするものなのか
　明細書Lintとは、明細書原稿の細かな不具合を検査するソフトウェアです。Wordのプラグインとして実現されており、Word画面上でチェックが可能です。

## ２．概略手順
（１）　旧バージョン（1.2.x）のアンインストール（旧バージョンがインストール済みの場合）

（２）　新バージョン(1.3.x)のインストール

## ３．詳細手順
（１）旧バージョンのアンインストール

（１－１）　コントロールパネルを開き、「プログラムのアンインストール」をクリック。

（以下は、カテゴリ表示の例）

<img width="562" alt="00_conpane" src="https://github.com/k-ayaki/AppLint_Setup/assets/40140916/d299398f-74da-4840-9fed-37c03513512c">

（１－２）　「プログラムと機能」画面の「明細書Lint」をクリック。

<img width="685" alt="01_conpane" src="https://github.com/k-ayaki/AppLint_Setup/assets/40140916/f6bb0bd6-f1e1-456a-aedf-b0a98c69019b">

適宜、ＵＡＣダイアログでＯＫボタン等をクリックすると、旧バージョンのアンインストールが完了します。

（２）　新バージョンのインストール

（２－１）　setup.exeをダブルクリックして起動させると、保護画面が表示されます。

<img width="400" alt="保護画面00" src="https://github.com/k-ayaki/AppLint_Setup/assets/40140916/0dc89f8a-3e04-48c5-a287-9e284bd749fd">

（２－２）　詳細情報をクリックして、実行ボタンをクリックします。

<img width="400" alt="保護画面01" src="https://github.com/k-ayaki/AppLint_Setup/assets/40140916/2a6ab158-071f-4513-9a12-0816fc59d155">

（２－３）　「次へ」ボタンをクリック。

![インストール00](https://github.com/k-ayaki/AppLint_Setup/assets/40140916/08892853-68cc-404e-824a-80bf15756fac)

（２－４）　「次へ」ボタンをクリック。

![インストール01](https://github.com/k-ayaki/AppLint_Setup/assets/40140916/fe1198d0-e68d-46e1-b179-a789547998c7)

（２－５）　「次へ」ボタンをクリック。

![インストール02](https://github.com/k-ayaki/AppLint_Setup/assets/40140916/29090366-40e1-4350-80a1-04e02ade943c)

（２－６）　プログレスバーの進捗待ち。

![インストール03](https://github.com/k-ayaki/AppLint_Setup/assets/40140916/1d99edf7-f39f-488d-9024-929c9f803ad7)

（２－７）　インストールが終了しました。

![インストール04](https://github.com/k-ayaki/AppLint_Setup/assets/40140916/debbe0fd-2bcc-497a-9f1c-1bb9e6baae5f)

# 明細書Lint 1.3.0の機能一覧
## １．明細書Lintのリボン・インタフェース
　明細書LintをインストールしたのちにWordを起動すると、明細書Lintのリボン・インタフェースが現れます。

<img width="223" alt="リボン" src="https://github.com/k-ayaki/AppLint_Setup/assets/40140916/9bc9d77e-3dfb-405a-9595-75a14d65b3c5">

 明細書Lintのリボン・インタフェースには、請求項／明細書／サポート要件／文長の主要機能があります。消去機能は、チェック結果のマーカやコメントを消去するものです。40x50と36x29は、WORDの段落を明細書の書式に合わせ、かつインターネット出願ソフトの形式に合わせるものです。

## ２．各機能の紹介

### ２．１．請求項
請求項の引用関係と前記の記載をチェックします。前記された名詞は緑色、その先行詞は水色でマークされ、修正が必要な部分についてはWordのコメントで不具合が指摘されます。

以下の画面は、前記されていない「前記接続腕」を指摘している例です。

<img width="978" alt="請求項" src="https://github.com/k-ayaki/AppLint_Setup/assets/40140916/8adfacd0-9c3e-4c2e-9cde-3beb01cb53c6">



以下の画面は、プリアンブルの語句「再配信サーバ」と、請求項１の発明の名称「映像再配信サーバ」との相違を指摘している例です。

引用先の請求項１の発明の名称「映像再配信サーバ」と、引用している請求項２の発明の名称「再配信サーバ」との相違を指摘します。

<img width="954" alt="請求項2" src="https://github.com/k-ayaki/AppLint_Setup/assets/40140916/13588973-9b55-471c-93e4-05080cdb2a6b">

### ２．２．明細書
明細書の符号と要素名の対応をチェックします。符号は緑色、対応する要素名は水色でマークされ、修正が必要な要素名はWordのコメントで不具合が指摘されます。

<img width="957" alt="明細書" src="https://github.com/k-ayaki/AppLint_Setup/assets/40140916/3c704b68-0a4c-41cd-ba3f-9ea3c729ec9e">

### ２．３．サポート要件

請求項の名詞が、発明を実施するための形態に記載されていれば水色で表示されます。請求項の名詞が、発明を実施するための形態に記載されていないとき、Wordのコメントで指摘されます。

<img width="923" alt="サポート要件2002-332438" src="https://github.com/k-ayaki/AppLint_Setup/assets/40140916/eaf0e37f-9cea-475d-a1ff-b009c95318b2">

### ２．４．文章長さ
明細書の文章の長さが１００文字以上、または、文章に主語が記載されていないものなどを指摘します。

主語が記載されて、かつ短文であることが文章の理解しやすさ、翻訳しやすさに大きく寄与します。これをチェックするものです。

その他、読点にカンマが使われていること、文末に句点が使われていないことなども検出します。

<img width="919" alt="文章の長さ2002-332438" src="https://github.com/k-ayaki/AppLint_Setup/assets/40140916/e71803f7-46cd-448e-ae46-ff11b16eb158">
