# m5stack-drupal9

「Drupal 9 おいしいレシピ集3 / Drupal Meetup 豊田支部」
M5StackでハイブリッドDrupalはじめの一歩

に関する補足ページです。

書籍内で作成しているUIFlowのサンプルコード例です。

* one-shot-request.m5f
ボタンAを押すと指定したURLの記事コンテンツのタイトルを取得するプログラム

* drupal-simple-monitor.m5f
5秒おきに指定したURLの記事コンテンツのタイトルを取得して、取得できない場合には音を鳴らすプログラム

(使用方法)
UIFlowで上記いずれかの.m5fファイルを開き、Httpブロック内のURLで指定している https://example.com/jsonapi/node/article/xxxx を適切なホスト名およびarticle uuidに変更してお使いください。
