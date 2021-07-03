### <font size=3>Lesson1.初めてのワークフロー</font><br>
<font size=2>[トップページに戻る](https://kitanotamotsu.github.io/)</font><br>
<br>
### <font size=3>取扱説明</font>
<br>機能:
<br>　選択した文字列でGoogle Suggestワークフローを起動します
<br>インストール:
<br>　1.[alfredworkflow](https://github.com/KitanoTamotsu/googlesuggest/files/6721029/google.suggest.by.selected.text.alfredworkflow.zip)をダウンロード 
<br>　2.ファイルをダブルクリックしてワークフローに登録
<br>　3.ワークフローでhotkeyを設定（例えば⌘G）
<br>使い方:
<br>　事前にAlfredワークフローのexsampleにあるGoogle Suggestを追加してください
<br>　検索したいワードを選択して、設定したHOTKEY（例えば⌘G）を押下
<br>
### <font size=3>開発メモ</font>
<br>1.仕組み
<br>　コアとなるGoogle Suggestが”g {augument}”というキーワード起動です。Hotkeyの起動によって、"g "（プレフィックス）と選択したテキストをalfredに渡します。
<br>　するとGoogle Suggestの機能によって検索候補が現れます
<br>2.メモ
<br>　ソースコードがないワークフローです。AlfredワークフローとGithubの練習として公開したものです

