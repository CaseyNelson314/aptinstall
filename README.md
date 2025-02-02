# APT. install

「apt install」を「aptinstall」とタイポしたときに「あぱつ」が実行されるパロディアプリです。

![Demo](demo.gif)

リリースページから実行ファイルをダウンロードできます。

<https://github.com/CaseyNelson314/aptinstall/releases/latest>

環境変数を設定すると次のように使えます。

```bash
aptinstall
```

ローカルでビルドする場合は次のようにします。Go が必要です。

```bash
git clone https://github.com/CaseyNelson314/aptinstall.git
cd aptinstall
go run .
```
