# clip

> 入力コンテンツをWindowsクリップボードにコピーします。
> もっと詳しく: <https://learn.microsoft.com/windows-server/administration/windows-commands/clip>。

- コマンドライン出力をWindowsクリップボードにパイプします:

`{{dir}} | clip`

- ファイルの内容をWindowsクリップボードにコピーします:

`clip < {{path/to/file.ext}}`

- 末尾に改行が付いたテキストをWindowsクリップボードにコピーします:

`echo {{テキスト}} | clip`

- 末尾の改行なしでテキストをWindowsクリップボードにコピーします:

`echo | set /p="テキスト" | clip`
