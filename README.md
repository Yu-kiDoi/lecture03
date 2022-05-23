# lecture03
-AP サーバーの名前とバージョン
-Puma version: 5.6.4(メインブランチに移動してrails sでサーバー起動して確認)

-AP サーバーを終了させた場合、引き続きアクセスできますか？結果を確認して、また AP サーバーを起動してください。
-APサーバーを終了させた場合の結果 Oops　No application seems to be running here!と出てアプリケーションにアクセスできなくなる
-APサーバーの起動 rails sで起動
-ctrl+cで停止させる

-サンプルアプリケーションで使った DB サーバー（DB エンジン）の名前と、今 Cloud9 で動作しているバージョンはいくつか確認してみましょう。
-mysql  Ver 8.0.29 for Linux on x86_64
-$ sudo mysql --version(コマンドで確認)

-DB サーバーを終了させた場合、引き続きアクセスできますか？
-- Can't connect to local MySQL server through socket '/var/lib/mysql/mysql.sock' (2)エラーが出てアクセスできなくなる

-Rails の構成管理ツールの名前は何でしたか？
-bundler

-今回学んだこと・感想
-講座を視聴しながら環境構築進めていて、その中で先生がやってる画面にならずError表示が出ていて焦らずError内容Cloud9などで調べればでるのでErrorが出ても一つ一つ丁寧に解消していこうと思いました。
-講座を見ながら環境構築したので、コマンドだったりを今後必要不可欠になるので使用頻度が高いものに関しては覚えるプラスメモにまとめようと思います。