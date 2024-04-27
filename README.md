# CatchUp-Go

Goのキャッチアップ過程・メモ

<img src="https://skillicons.dev/icons?i=go" />

## 準備の仕方

+ Windowsの場合

[Go言語の公式サイト](https://go.dev/dl/)からmsiファイルをダウンロードする。

※環境変数の設定を忘れずに

+ Macの場合

[Homebrew](https://go.dev/dl/](https://brew.sh/ja/))でインストールする。
```bash
brew install go
```

+ インストールの確認
```bash
go version 
```

でバージョン情報が表示されればOK
```bash
go version
go version go1.17.6 darwin/amd64
```

## プロジェクトの作成と実行

+ 作成の仕方
```bash
go mod init プロジェクト名
```

+ 実行方法
```bash
go run ファイル名
```