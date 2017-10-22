### 日本語化
Package > Settings View > Install Packages  
検索バーに「japanese-menu」でインストール。

### Path

* Windows
```
C:\Users\ユーザ\.atom\styles.less
```
### Groovy syntax highlighting and snippets
ターミナルで以下を実行する。

```shell
apm install language-groovy
```
(参照)[language-groovy](https://atom.io/packages/language-groovy)

### 基本設定
Package > Settings View > Open > [Editor]
- インデントガイドを表示：チェック
- 不可視文字を表示：チェック

### JavaScriptsコードの整形
Package > Settings View > Install Packages
検索バーに「atom-beautify」でインストール。

* 「Ctrl + Alt + B」の自動フォーマットのショートカット

Ubuntuでは、テキスト編集時に変なバインドが掛かってしまう。  
そのため、以下のコマンドを実行してログアウトを行うことで、解消可能。

```
sudo vim /usr/share/fcitx/addon/fcitx-vk.conf 
```

開いたファイルに
```
Enable=false 
```

ログアウトし、再ログイン。

### HTMLタグを自動で閉じる
Package > Settings View > Install Packages
検索バーに「autoclose-html」でインストール。
