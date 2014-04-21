octopress-qiita-aside
=====================

octopress aside for qiita that is Japanese programming knowledge sharing service.

## 使い方

1.このプロジェクトを取得する   
```$ git clone https://github.com/ko2ic/octopress-qiita-aside.git```

2.取得したsourceをoctopressのディレクトリに入れる    

3.取得したnotoverwriteディレクトリにあるhead.htmlの内容を./source/_includes/custom/head.htmlに追記する   
これはqiitaのストックとコメントのアイコンが[Font Awesome](http://fortawesome.github.io/Font-Awesome/)を利用しているからです。   

4.取得したnotoverwriteディレクトリにある_config.ymlの内容を./_config.ymlに追記する   
qiita_popularをtrueにする人気の投稿を表示する。falseにすると最近の投稿を表示する。   
qiita_popularをtrueにすると全記事を取得してjavascriptで整形しているだけなので、パフォーマンスに⚠が必要です。
```
qiita_user: user_name
qiita_popular: true
qiita_display_count: 5
```
