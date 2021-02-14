google suggest by selected text.alfredworkflowのメモ

機能：選択した文字列でGoogle Suggestワークフローを起動します

前提：事前にAlfredワークフローのexsampleにあるGoogle Suggestを追加してください

設定：
1.google suggest by selected text.alfredworkflowをダウンロード
2.ファイルをダブルクリックしてワークフローに登録
3.ワークフローでhotkeyを設定（私は⌘Gとしており、ワークフローのdescriptionを"select text & ⌘G"にしています。気になる方は修正してください）

動き方：
コアとなるGoogle Suggestが”g {augument}”というキーワード起動です
Hotkeyの起動によって、"g "（プレフィックス）と選択したテキストをalfredに渡します
するとGoogle Suggestの機能によって検索候補が現れます

開発メモ：
ソースコードがないワークフローです
AlfredワークフローとGithubの練習として公開したものです
実際にはほとんど使っていません

