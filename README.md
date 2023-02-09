# 開発実績
GitHubの正しい使い方では無いかも知れませんが、まとめておいたほうが良いと思いましたのでここにまとめさせていただきます。

## 父親の仕事の手伝いでの開発
※私の製品では無いのでソースコード及び完成品は公開出来ません。ご了承下さい。<br>
使用言語はC++ 使用フレームワークはQtです。
### ファイル同期アプリ
ソケット通信を用いて複数のクライアント間で特定ディレクトリ内のファイルを共有、同期するgitのようなアプリケーションを開発。<br>

以下のURLに実際に動作させた様子を記録しています。<br>
今回はlocalhostで実験している様子です。IPアドレスを指定すれば別機でも出来ます。


### 変数同期アプリ
ソケット通信を用いて複数のクライアント間で変数を共有、同期するアプリケーションを開発。<br>
入力欄に数値を入れると他のサーバーに情報が送信され、全てのクライアント間でデータが同期される。<br>
入力欄の左の数値は配列のインデックスで動画ではデバッグ用に全ての値を固定している。<br>
以下のURLに実際に動作させた様子を記録しています。<br>
https://youtu.be/wkmX3OqCcGs

### 数値データの圧縮関数
詳しくは説明出来ませんが<br>
・大量の数値データを渡すと圧縮したデータを返す関数、<br>
・圧縮されたデータを渡すと元の数値データを返す関数、<br>
をそれぞれ開発しました。<br><br>
圧縮率はものによって差はありますがいくつか試した所<br>
135891->28337となり20.8%まで圧縮<br>
1214284->90919となり7.5%まで圧縮出来ています。(単位はbyte)<br>
大きな差があるのは連続データの有無だと思われます。

### その他
ー

## 大学での開発
### 3人グループで開発した翻訳Webアプリ
英語を日本語に翻訳するWebアプリの開発を行いました。開発期間は約3ヶ月です。<br>
以下のURLにデモ動画を掲載します。<br>
私は主にHTML+CSSによるページ作成を行い、またPython(Flask)を使用して翻訳機とページの接続を行いました。<br>
https://youtu.be/2P3neB9b5Bo

### 6人グループで開発したサークル等部員管理Webアプリ
コロナ禍における部/サークル活動のメンバー管理の効率化を行うWebアプリの作成を行いました。開発期間は約4ヶ月です。<br>
使用言語はPHP,HTML,CSS,SQLite、GitLabを利用しての開発です。<br>
私は主にフロントのデザイン、フローチャートの作成、外注phpなどの修正、SQLiteを扱う関数の作成、テストを行いました。（全員でやったものも含める）
