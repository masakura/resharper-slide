# ❤ ReSharper 草案
* ReSharper って?
* 初心者が使うべき理由
* 初心者を脱却する人が使うべき理由
* 中級者が使うべき理由


## ReSharper って?
* 山本さんが語ると思うので、ちょっとだけ
* JetBrains 社が作っている Visual Studio のアドオン
* サムライズム株式会社は JetBrains 社の製品の正規代理店


## Visual Studio だけで十分では?
* Visual Studio は非常に協力な統合開発環境ですが、弱点もかなり多い
* コード診断・コード生成・コード訂正・リファクタリングなどは正直 Eclipse よりも弱い
  - 少しずつよくなってはいるけど
* この弱点をカバーしてくれるのが ReSharper


## 初心者が使うべき理由
* 個人的には、初心者ほど使うべきだと思っている
* コード診断機能がかなり強力
  - その場で間違いを指摘されれば誰だって直す
  - ほとんどの場合、自動修正で直せる
  - 右側のバーをグリーンにすれば結構綺麗なコードに
* 「ReSharper のコード診断で警告が出ないこと」をコーディングルールに加えておけば結構何とかなる
  - それ以外にも書いちゃいけないコードっていうのはあるけど、大半を ReSharper が潰してくれるのでレビューが楽
  - Microsoft のクラスライブラリ設計者のためのガイドラインや、いろんなガイドライン、アンチパターンの一般的なものはだいたいデフォルトで OK
* ジャンプが強力


## 初心者を脱却したい人が使うべき理由
* コードの提案機能がかなり強力
  - 知らない言語の機能を教えてくれる
* スタックトレースからのジャンプ
* 強力なコード解析
  - ファイル構造
  - 型の継承階層
  - 利用箇所の調査


## 中級者が使うべき理由
* 強力なリファクタリング
  - 名前の変更
  - Safe Delete
* 単体テストサポート


## 価格
| 製品                                 | 価格 (円) |
| ------------------------------------ | --------: |
| VS Ent. w/MSDN                       |   749,876 |
| VS Pro. w/MSDN                       |   149,877 |
| VS Pro. w/MSDN + ReSharper Ultimate  |   200,853 |


## まとめ
* Visual Studio の弱点を補完してくれる
* Visual Studio にある機能もそれよりいいものが入っている
* 初心者ほどおすすめしたい
* VS Ent. w/MSDN 買うくらいなら Pro. + ReSharper がおすすめ
  - InteliTrace は捨てがたいけど...
