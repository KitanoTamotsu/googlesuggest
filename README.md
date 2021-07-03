### <font size=3>Lesson1.初めてのワークフロー
[トップページに戻る](https://kitanotamotsu.github.io/)</font>


### <font size=3>取扱説明</font>

　機能:
   選択した文字列でGoogle Suggestワークフローを起動します
  
  インストール：
   1.[alfredworkflow](https://github.com/KitanoTamotsu/googlesuggest/files/6721029/google.suggest.by.selected.text.alfredworkflow.zip)をダウンロード 
   2.ファイルをダブルクリックしてワークフローに登録
   3.ワークフローでhotkeyを設定（例えば⌘G）
  
  
  使い方：
   事前にAlfredワークフローのexsampleにあるGoogle Suggestを追加してください
   検索したいワードを選択して、設定したHOTKEY（例えば⌘G）を押下
  



### <font size=3>開発メモ</font>
　
 1.仕組み
　　コアとなるGoogle Suggestが”g {augument}”というキーワード起動です。Hotkeyの起動によって、"g "（プレフィックス）と選択したテキストをalfredに渡します。
   するとGoogle Suggestの機能によって検索候補が現れます

2.メモ
　ソースコードがないワークフローです。AlfredワークフローとGithubの練習として公開したものです

