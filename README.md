# 修士課程中間諮問 スタイルファイル（非公式）

京都大学大学院情報学研究科社会情報学専攻の修士課程の中間諮問で使えるスタイルです。**公式で配布されているしている Word ファイルをもとに作られています**。

30 分クオリティなので，至らない点が多いです。プルリクを投げていただければ反映させていただきます。

## 動作環境

Lualatex, jlreq クラスで動作確認しています。

## 注意

フォントは公式に合わせて，MS Mincho を使っています。Mac の方は，

- /Applications/Microsoft Word.app/Contents/Resources/DFonts/msgothic.ttc
- /Applications/Microsoft Word.app/Contents/Resources/DFonts/msmincho.ttc

を開いて本体にインストールしてあげるなどの方法で，これらのフォントが使えるようにする必要があります。自己責任でお願いします。他のフォントを使っても OK です。Windows は動作環境がなく確かめていませんが，lualatex-fontspec パッケージに上記フォントの定義があるので，苦労しないはずです。

Overleaf では MS フォントありませんので，違うフォントに切り替えてください。ローカルでやる場合は，

```bash
brew install mactex-no-gui
```

で GUI なしの TeX をインストールして，

https://texwiki.texjp.org/?Visual%20Studio%20Code%2FLaTeX

にある設定を導入するだけで動きます。環境構築これだけですし，ローカルの方がビルドが早いです。

## 要望

色々無理やり感がありますが，所属と指導教員が特に無理矢理です。改善してくれる方大歓迎です。

こんなのでよければどうぞお使いくださいませ 🙏
