macOSX10SublimeText3Setting
===========================

使い方
--------

複数のMac PCでSublime Text3の拡張パッケージと個別設定を共有するためのリポジトリです

1. Sublime Text3をインストールする

1. Package Controllをインストールする

1. 全ての設定ファイルを`~/Library/Application Support/Sublime Text 3/Packages/User`以下に配置する

1. Sublime Textを再起動する


SublimeLinterに関して
-----------------------
リアルタイムに構文をチェックする`SublimeLinter`をインストールしています。

言語別に、他にインストール作業が必要な場合もあります。

詳細は下記を確認して下さい

**SublimeLinter-csslint**

* 参考URL: https://github.com/SublimeLinter/SublimeLinter-csslint

* 他にインストールするもの:
   * Node.jpのパッケージマネージャである(npm)[http://nodejs.org]のインストール
   * `sudo npm install -g csslint` にてcsslintをインストール


**SublimeLinter-ruby**

* 参考URL: https://github.com/SublimeLinter/SublimeLinter-ruby

* 他にインストールするもの:
   * 言うまでもないが、rubyのインストールが必要

**SublimeLinter-html-tidy**

* 参考URL: https://github.com/SublimeLinter/SublimeLinter-html-tidy

* 他にインストールするもの:
   * `brew install homebrew/dupes/tidy`を実行

**SublimeLinter-javac**

* 参考URL: https://github.com/SublimeLinter/SublimeLinter-javac

* 他にインストールするもの
   * JDK1.7以上

**SublimeLinter-json**

* 参考URL: https://github.com/SublimeLinter/SublimeLinter-json

* 他にインストールするもの

**SublimeLinter-pyflakes**

* 参考URL: https://github.com/SublimeLinter/SublimeLinter-pyflakes

* 他にインストールするもの
   * pyflakesのインストール

```
# For python 2.x
[sudo] pip-2.x install pyflakes

# For python 3.x
[sudo] pip-3.x install pyflakes
```

**SublimeLinter-shellcheck**

* 参考URL: https://github.com/SublimeLinter/SublimeLinter-shellcheck

* 他にインストールするもの