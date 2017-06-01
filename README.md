# 使い方

複数のMac PCでSublime Text3の拡張パッケージと個別設定を共有するためのリポジトリです

1. Sublime Text3をインストールする

1. Package Controllをインストールする

1. Sublime Text3を終了する

1. 全ての設定ファイルを`~/Library/Application Support/Sublime Text 3/Packages/User`以下に配置する

```bash
$ cd ~/Library/Application Support/Sublime Text 3/Packages

$ rm -rf User

$ git clone git@github.com:seak0503/SublimeText3.git User
```

1. Sublime Textを起動する

1. しばらく待機すると全てのパッケージのインストールが完了する

# 各種パッケージインストールの補足

## Compass

rbenvを使っている環境では下記のとおり、pathの設定を行う必要がある

### 手順

1. Command + Shift + p
1. List Package
1. Compass を選択
1. Compass/Compass.sublime-buildを開く
1. `"osx" {"path": `のところに`/Users/username/.rbenv/shims:`を追記する

### 設定例

```
"osx":
  {
    "path": "/usr/bin:/bin:/usr/sbin:/sbin:/usr/local/bin:/Users/shyamahira/.rbenv/shims:$PATH"
  }
```

`~/.rbenv/shims`とするとnot foundのエラーになってしまったので注意が必要