# 01 Webとは
---
- 正式名称は World Wide Web
- ハイパーテキストという言語で構成されている
- ハイパーテキストは一つのWebページの中にハイパーリンク（他ページのリンク）を埋め込むことができる
---
# 04 HTMLとWebブラウザ
---
- ハイパーテキストを記述するための言語が**HIML**である
---
# 05 WebサーバーとHTTP
---
- Webページが表示される際は、WebブラウザからWebサーバーにコンテンツを要求し、Webサーバーが要求されたコンテンツをWebブラウザに送信するというやりとりが行われる
- この世界共通のハイパーテキストのやりとりを**HTTP**という
- HTTP(Hyper Trensfer Protocol)
---
# 07　静的ページと動的ページ
---
- 何度アクセスしても同じものが表示されるものが**静的ページ**（企業の紹介サイトなど）
- アクセスした時の状況に応じて異なる内容が表示されるものが**動的ページ**（検索サイトなど）
---
# 08 動的ページの仕組み
---
### CGI
- WebサーバーがWebブラウザからの要求に応じてプログラムを起動させるための仕組み
### サーバーサイド・スクリプト
- CGIから呼び出されるプログラム
- 一般的にはスクリプト言語がつかわれる
### クライアントサイド・スクリプト
- サーバーサイド・スクリプトに対し、HTMLに埋め込まれ、読み込まれる際に実行されるもの
- 主にJavaScriptが用いられる
---
# 02 インターネットの標準プロトコル
---
## プロトコルとは
---
- あらかじめ決められた共通のルールみたいなもの
- プロトコルはよく狼煙に例えられる
---
## TCP/IPとは
---
- 様々なサービスを実現するためのプロトコルの集まり
-　HTTPもTCP/IPの一部
---
# 03 TCP/IP
---
## TCP/IPは役割ごとに、以下4つの階層（レイヤー）がある
---
- アプリケーション層(HTTP SMTP FTP など)
- トランスポート層(TCP UDP)
- インターネット層(IP ICMP)
- ネットワークインターフェース層(イーサーネット Wi-Fi など)
---
## TCPとUDPの違い
---
- TCPはお互い確認をとりながら通信を行うコネクション型
- UDPは送信側と通信側で確認を取らないコネクション型
---
## 04 IPアドレスとポート番号
---
- IPアドレスで接続するコンピューターを指定し、ポート番号でコンピューターが提供するサービスを指定する
- 一般的にWebサーバーは80番と決まっている
---
# 05 URLとドメイン
---
## URL
---
- URLは、 スキーム :// ホスト名（ドメイン名）: ポート番号 / パス名    などで構成されている
```
http://example.com:80/test.html
```
---
## ドメイン
---
- 数字で表記されるIPアドレスは私足しにとっては覚えにくいため代わりにドメインが使われている（上記のexample.comの部分）
---
# DNS
---
- ドメインからIPアドレスがわかる(紐づいている)
---
#HTTP
---
## Webサイト閲覧までの5ステップ
---
1.　閲覧するURL入力 <br>
2.　Webサーバーにデータ要求 <br>
3.　要求内容確認＆データ用意 <br>
4.　WEbブラウザへ応答 <br>
5.　受け取ったデータをWebブラウザが解析し表示 
---
