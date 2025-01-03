# ①課題番号-プロダクト名

体調に関するアンケート DB連携バージョン

## ②課題内容（どんな作品か）

- 前回提出したアンケートアプリを多少進化させて、本物のアンケートに近づけました

## ③DEMO

https://gsus08-05.sakura.ne.jp/kadai8_db/post.php

## ④作ったアプリケーション用のIDまたはPasswordがある場合

- ID: なし
- PW: なし

## ⑤工夫した点・こだわった点

- アラートやエラーが出るように設定したのでどこで引っ掛かっているかすぐにわかり、確認する箇所が減りました。
- 居住地を入れ、複数回答数の上限を設定してよりリアルなアンケートにしました。
- 本来であればグラフが出ますが、現時点でDBにデータが入らない状態です。ローカルでは大丈夫だったので、コードを含めて12/20 12:19現在確認中⇨解決済

## ⑥難しかった点・次回トライしたいこと(又は機能)

- 案の定、DBの接続に手こずりました。また、うっかりDBのPWなどをUPするところでした。
- localhostにアップした時点で、最後にcvsを出力するファイルを構築しましたが、そのファイルがあるとXAMMPのMySQLが勝手に停止するという謎現象が発生してかなりの時間を溶かしました。結局ファイルを削除して、再起動して解決。DB接続を含め解決しそうであれば実装を試みます。
- 12/20 21:40追記 キャッシュが残っていたため、古いファイルを参照していたという現象が起こっていたために上手く作動しなかったことが判明しました。phpは繊細ですね。

## ⑦質問・疑問・感想、シェアしたいこと等なんでも

- PHPを極めたい気持ちはありますが、かなり難しいですし、繊細な感じがします。極めたら楽しそうなので、もう少し仲良くなりたいです！
- 業務との兼ね合いで時間に余裕がなく、消化不良感が半端ないのですが、ここが踏ん張りどきだと思っております。年末年始で復習をしっかりやりたいと思います。
- phpを学習してみて、なぜフロントエンドとバックエンドに分かれるのか、なんとなくわかる気がしてきました。奥が深い世界ですね。

##【参考にしたサイト】
- 今回はキャッシュが残ると参照が上手くいかないということを学びました。解決策を探しているときに、ヒントになりました。
https://terakoya.sejuku.net/question/detail/30771