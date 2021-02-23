# comical_blog
技術系のことを記録するサイトのテーマ

# wordpress_first
WordPressをインストールするところからスタートする。  
 
作業フォルダに移動して、docker-compose up -dでWordPressとMySQLのコンテナが起動する  
削除する際はdocker-compose down  
  
下記ページを参考にして作成している。  
データベースのバージョンは5.7としている。  
個人のテーマフォルダとしてtestフォルダを最初から作成している。  
testフォルダはテーマ表示に必要な最低限のファイルを集めた空のテーマである。  
  
  
↓にwordpress01の説明文を示す。  
https://github.com/kensuke0518/wordpress01  
# wordpress01
Docker-Composeと.envファイルを用いてWordPressとMySQLの環境を構築したリポジトリ  
データをDL後、作業フォルダへcdして、docker-compose up -d を実行するとwordpressとmysqlのコンテナがスタートします。  
その後、localhost:9000（このポート番号はdocker-compose.yml内の値を変えると複数URLで作業ができる）にアクセスすると、  
wordpressのスタート画面に移動します。  
  
外観→テーマでawsのロゴがある物が今回新しく用意したテーマとなる。  
このテーマを編集してもいいし、  
新しくテーマを作成する場合は、作業フォルダ内のthemeフォルダに新しく任意の名前のフォルダを作成してindex.phpとstyle.cssを作成してください。  
外観→テーマを確認すると作成したテーマが1つ追加されているはずです。  

# 修正情報
1. スタート画面がすでにログイン状態の画面なので、DLした際にアカウント情報の入力から開始できるように変更しておいた方がいい。  