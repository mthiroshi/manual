## プログラムは無事に動きましたか？ ##

BEARの多くの設計はHTTPなどのRESTをモデルとしているのがお分かりいただけたでしょうか？HTTPでは、リクエストの仕方、レスポンスのフォーマットが（たとえエラーでも）同じで、またサーバーサイドがどの言語で書かれてるかにクライアントは関心を持ちません。同じようにBEARではぺージクライアントまたはCLIクライアントはリソース側でPEAR::MDB2を使用してるかDoctorine ORMなのかに関心がありません。単なるデータソースなのかオブジェクトモデルなのかも分かりません。

モデルが何であるか、テンプレートエンジンが何であるか、各コンポーネントの選択をBEARはアプリケーション側のドメインだと考え、コンポーネントよりむしろその接続に注目しようと考えます。

## カスタマイズ例 ##

更なる理解のためにいくつかカスタマイズしてみましょう。

  * [カスタマイズ編 リソースのページングと表示順](blog_pager.md)
  * [カスタマイズ編 ユーザーエージェントの継承](blog_ua.md)
  * [カスタマイズ編 投稿日時・更新日時の自動挿入(AOP)](blog_aop.md)
  * [カスタマイズ編 キャッシュ](blog_cache.md)