# mklink

> シンボリックリンクを作成します。
> もっと詳しく: <https://learn.microsoft.com/windows-server/administration/windows-commands/mklink>。

- ファイルへのシンボリックリンクを作成します:

`mklink {{リンクパス}} {{ソースファイルのパス}}`

- ディレクトリへのシンボリックリンクを作成します:

`mklink /d {{リンクパス}} {{ソースディレクトリパス}}`

- ファイルへのハードリンクを作成します:

`mklink /h {{リンクパス}} {{ソースファイルのパス}}`

- ディレクトリジャンクションを作成します:

`mklink /j {{リンクパス}} {{ソースファイルのパス}}`
