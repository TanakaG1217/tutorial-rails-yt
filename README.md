# tutorial-rails-yt
## 流れメモ
rails new フレームワーク作成
routs で特定のパス　が来たときのコントローラーsamples指定(頭小文字)
rails g Samples でコントローラー作成 
(命名規則Abcds)

コントローラー/samples　でdef index を宣言
index.html作成

rails g model Posts title:string content:text でモデルとDB/migrate作成
//db:migrate ?

rails db:migrate　でテーブル作成

Posts コントローラーに@posts = Post.all記述で、 そのviewファイルでDBのデータが使える
＠　はインスタンス変数（そのviewファイルでのみ使える変数）

vieファイルをいじっていく
rubyでは色んなヘルパーが使える。form_withなど