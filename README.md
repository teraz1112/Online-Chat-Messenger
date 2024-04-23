# Online-Chat-Messenger

## 概要
グループチャットができるアプリケーション

## デモ
![output](https://github.com/Recursion-Group-Backend-c/Online-Chat-Messenger/assets/119317071/ac773301-d79c-4e7b-9ca3-df7c9fb2f0e3)

## 説明
グループチャットができるアプリケーションです。

このアプリケーションでは、リアルタイムでのグループチャットが可能です。

友達を招待してすぐにグループチャットを始めることができます。

基本的な機能として、チャットルームの作成/参加/ユーザー同士でのグループチャットができます。

## 学習内容
- プロセス間通信(パイプ,ソケット)
- RPCプロトコル層アーキテクチャ
- UDP/TCP
## インストール

1. リポジトリをクローンする
```
git clone https://github.com/teraz1112/Online-Chat-Messenger.git
```

2. クローンしたリポジトリへ移動する
```
cd Online-Chat-Messenger
```

## 使用方法
1. ターミナルを3つ起動します。<br>起動した3つのターミナルについては、以降の手順では下記名称で呼ぶこととします。

| ターミナル | 名称 |
| ------- | ------- |
| ターミナル1 | サーバ用ターミナル |
| ターミナル2 | クライアント用ターミナル1 |
| ターミナル3 | クライアント用ターミナル2 |

2. サーバ用ターミナルに下記コマンドを入力する
```
python3 server.py
```
3. クライアント用ターミナル1に下記コマンドを入力する
```
python3 client.py
```
4. クライアント用ターミナルに表示される指示に従い、チャットルームを作成する
5. クライアント用ターミナル2に下記コマンドを入力する
```
python3 client.py
```
6. クライアント用ターミナルに表示される指示に従い、手順4.で作成したチャットルームに参加する
7. ユーザー同士でグループチャットを楽しむ
8. グループチャットを終了したい場合は、クライアント用ターミナル1に`exit`と入力して終了する

## 使用技術
<table>
<tr>
  <th>カテゴリ</th>
  <th>技術スタック</th>
</tr>
<tr>
  <td>開発言語</td>
  <td>Python</td>
</tr>
<tr>
  <td rowspan=3>インフラ</td>
  <td>Ubuntu</td>
</tr>
<tr>
  <td>Docker</td>
</tr>
<tr>
  <td>VirtualBox</td>
</tr>
<tr>
  <td rowspan=3>その他</td>
  <td>Git</td>
</tr>
<tr>
  <td>Github</td>
</tr>
</table>

## 機能一覧
### サーバ用ターミナル
![image](https://github.com/Recursion-Group-Backend-c/Online-Chat-Messenger/assets/119317071/9e5667e1-7333-41ae-9081-2615424d374e)

### クライアント用ターミナル1(user1)
![image](https://github.com/Recursion-Group-Backend-c/Online-Chat-Messenger/assets/119317071/d850f3f5-51ba-495e-9681-7bc7611f473c)

### クライアント用ターミナル2(user2)
![image](https://github.com/Recursion-Group-Backend-c/Online-Chat-Messenger/assets/119317071/56ed2c38-2a2a-4366-a10b-d11ae5595a95)
