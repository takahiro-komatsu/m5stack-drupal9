# m5stack-drupal9

「Drupal 9 Web 開発ことはじめ / Drupal Meetup 豊田支部(インプレスR&D)」
M5StackでハイブリッドDrupalはじめの一歩

に関する補足ページです。

書籍内で作成しているUIFlowのサンプルコード例です。

ボタンAを押すと指定したURLの記事コンテンツのタイトルを取得するプログラム
one-shot-request.m5f

5秒おきに指定したURLの記事コンテンツのタイトルを取得して、取得できない場合には音を鳴らすプログラム
drupal-simple-monitor.m5f

(使用方法)
UIFlowで上記いずれかの.m5fファイルを開き、Httpブロック内のURLで指定している https://example.com/jsonapi/node/article/xxxx を適切なホスト名およびarticle uuidに変更してお使いください。
