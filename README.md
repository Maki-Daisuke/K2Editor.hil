# K2Editor Highlight Files

## What's this?

その昔愛用していた K2(KOYABU kazuya)氏作による [K2Editor](http://k2top.jpn.org/index.php?K2Editor) の強調表示用の設定ファイルです。

メンテされなくなって久しいので、もはや需要があるとは思いませんが、個人的なアーカイブとして残しておきます。

だいたい、2003年〜2005年ごろに自分で使いやすいようにちょこちょこと拡張していったものです。


## How to Use

K2Editorのウィンドウメニューの「その他(O)」→「ファイルタイプ別の設定(F)」から設定ダイアログを開いて、「強調表示」タブの「読込(Y)」から読み込んでください。


## File list

### C.hil

ファイル名はCとなっているが、実質的にC++用。
クラスメソッドになるべく正確にマッチさせるために、実に3キロバイトを越える正規表現が３つも使われている。
なお、この正規表現を生成するPerlは失われてしまったため、もはやロストテクノロジー状態である。

### Haskell.hil

Haskell の予約語が登録してあるだけ。

### JustString.hil

その名の通り、ダブルクォート(")またはシングルクォート(')に挟まれた文字列とおぼしきものを強調表示するだけ。
iniファイルなどのちょっとした設定ファイルを開くのにどうぞ。

### Perl.hil

Perl用。サブルーチンの強調表示が、`sub foo{...` のみならず `my $foo= sub{...` という形式にも対応しているのが特徴といえば特徴。あと、ヒアドキュメントもちゃんと認識するようになっている。

### While-Language.hil

卒論製作的なもので作ったWhile言語用の強調表示。「While言語ってなんだよ？」という人は、[高橋正子先生の『計算論』](https://www.amazon.co.jp/dp/4764901846/)を読もう！


## Copyright

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Daisuke -yanother- Maki](https://github.com/Maki-Daisuke) has waived all copyright and related or neighboring rights to K2Editor.hil. This work is published from: Japan.
