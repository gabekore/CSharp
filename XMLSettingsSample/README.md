# 概要
C#で設定情報をxmlファイルに保存するサンプル

# ポイント
- クラスを丸ごとシリアライズ／デシリアライズしているので、xmlの項目名をプログラムでは気にしない
- 変数で型を指定できるので、int.Parse()みたいな煩わしさは不要
- 設定情報を初期値（工場出荷時設定みたいなもの）に戻すのも簡単
- 設定情報はxmlファイルに書き出されるのでファイルを差し替えれば全く別の内容にすることが簡単
    - 複数のxmlファイルをプログラムで管理することも容易
- NuGetとか参照設定とか不要なので、開発環境としてはシンプル


# ちなみに、

Writeボタンを押すと、exeと同じ場所にsettings.xmlというファイルができます

これが設定情報のファイルです
