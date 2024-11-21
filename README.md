# 放送部マニュアル
主に高校の放送部で使えそうな機材のTipsや企画のノウハウ、言い伝えなどをまとめてみました。 私が在籍していた高校の放送部用に作ったものですが、高校自体とは一切関係ないのであしからず。

## 使用方法
下記Urlでホストしているのでそこを見るのが良いでしょう。

- https://housou.pages.dev/

### ローカルで見る
もし、学校の制約などでローカルでホストする必要がある場合は、このリポジトリをcloneして自分でビルドできます。

#### Linuxの場合

1. 事前に`Python3`と`Git`をインストールして、`pip`、`git`コマンドが使える状態にしておきます。
2. このリポジトリをcloneします。
3. リポジトリ内の`build.sh`を実行します。
4. `housou-manual/site`ディレクトリにサイトがビルドされています。

ここまでの手順は、以下のシェルスクリプトを一行ずつ実行すればできます。

```sh
#!/bin/sh
git clone https://github.com/taiseiue/housou-manual.git
cd housou-manual
. build.sh
```

## Windowsの場合

1. Windowsに`Python3`をインストールします。
2. このリポジトリの緑のボタン、「Code」>「Download ZIP」からファイルをダウンロードします。
3. ダウンロードしたZipファイルを解凍して、そのフォルダ内の`build.bat`をダブルクリックして実行します。
4. 正常に実行できたら、`site`フォルダ内にサイトができています。

### リンクについて
当サイトへのリンクは自由です。なんなら記事のタイトル下のメニューからUrlをSNSなんかにシェアできます。
ただし、記事のUrlは突然変わることがあるのでご了承ください。

Iframeでサイトに埋め込むのもOK。埋め込みたい時は記事のUrlの末尾に`?embed`を追加することで埋め込み時にいらないUIを非表示にできます。

```txt title="例"
https://housou.pages.dev/?embed
```

### 問い合わせ
マニュアルの内容については保証できませんが、聞きたいことがあれば、下のアカウントに連絡してもらって構いません。

|||
|-|-|
X(Twitter)|[@taiseiue](https://x.com/taiseiue)|
|メール|[taisei@wsoft.ws](mailto:taisei@wsoft.ws)|


## お願い
共同作成の方針はWSOFTDocsにならいます。
誤字脱字などを見つけたら、[ドキュメントの編集](https://docs.wsoft.ws/contribute/edit-document/)にしたがって修正していただけると幸いです。
そのほか、ご意見や要望などがあれば[GitHubのIssues](https://github.com/taiseiue/housou-manual/issues)へお願いします。
