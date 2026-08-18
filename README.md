# VScode
VSCode（Visual Studio Code）は、マイクロソフトが開発したエディターです。様々な拡張機能を入れることが可能です。

以下のページの「Download for Windows」からダウンロードしてください。

https://code.visualstudio.com/

![vscode1](./image/vscode1.png)

.exeファイルを保存してクリックして実行してください。

![代替テキスト](./image/vscode2.png)

ライセンス事項を読んだ後に「同意」してください。

![代替テキスト](./image/vscode3.png)

基本は「次へ」を押してください。
インストールする場所やショートカットをカスタマイズすることもできます。

![代替テキスト](./image/vscode4.png)

基本は「完了」を押してください。
インストールする場所やショートカットをカスタマイズすることもできます。

![代替テキスト](./image/vscode5.png)

日本語化すると便利です。まずは拡張機能を押して、検索で「japanese」と入れてください。
マイクロソフトの日本語化の拡張機能を入れてください。
導入したあとはVScodeを再起動してください。

![代替テキスト](./image/vscode6.png)

そのあとにPythonに対する拡張機能を導入してください。
同じく拡張機能の検索で「Python」と入力してください。

![代替テキスト](./image/vscode7.png)

VScodeはフォルダを規定して使用します。
例として「drone」というフォルダを作成してからそこに「test01.py」とファイルを作成してください。

![代替テキスト](./image/vscode8.png)

Hula-jpの裏面にSSIDが記載されているのでそのIDに接続してください。
Passwordは「12345678」です。
![代替テキスト](./image/vscode9.png)

接続したあとは、
```ptyhon
import pyhula
api = pyhula.UserApi()
if not api.connect():
    print("connect error")
else:
    print("connection to station by wifi")
```
と入力してください。下の出力部分に「connection to station by wifi」と表示されます。
![代替テキスト](./image/vscode10.png)
