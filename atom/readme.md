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

```
$ apm install language-groovy
```
(参照)[language-groovy](https://atom.io/packages/language-groovy)

### 基本設定
Package > Settings View > Open > [Editor]
- インデントガイドを表示：チェック
- 不可視文字を表示：チェック

### JavaScriptsコードの整形
```
$ apm install atom-beautify
```

* 「Ctrl + Alt + B」の自動フォーマットのショートカット

Ubuntuでは、テキスト編集時に変なバインドが掛かってしまう。  
そのため、以下のコマンドを実行してログアウトを行うことで、解消可能。

```
$ sudo vim /usr/share/fcitx/addon/fcitx-vk.conf 
```

開いたファイルに
```
Enable=false 
```

ログアウトし、再ログイン。

### HTMLタグを自動で閉じる
```
$ apm install autoclose-html
```

### JSDoc補完
```
$ apm install docblockr
```

### Dockerfile Syntax Highlighting
```
$ apm install language-docker
```

### Markdownのテーブルを成形
```
$ apm install tidy-markdown
```
