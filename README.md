**FSAEJ(学生フォーミュラ日本大会)公式サイトからお知らせ欄をスクレイピング，それをdiscordのwebhookに流すソフトです．**
## 使い方
### 実行前準備
nodejsを利用しているため，インストールしていなければインストールしてください．
.envファイルをmain.jsと同じディレクトリに設置，その中に```discord_hook=[webhookのURL]```と記載して，その後プロジェクトのルートで```npm i```と実行します．
### 実行
プロジェクトのルートで```node main.js```を実行するだけです．実行時にお知らせ欄をスキャンし，新しいものがあればdiscordにお知らせします．初回は全ての通知が出てしまうので，.envに`example.com`と記載して空撃ちしておいたほうが良いかもしれません．
## ライセンス
NYSL(煮るなり焼くなり好きにしろライセンス)です．詳細はLICENSEの欄を確認してください．
または，CC0のもとでも利用できます．どちらかに基づいて利用ください．

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)
