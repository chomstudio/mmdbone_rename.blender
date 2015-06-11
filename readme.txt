# mmdbone_rename ver.1.0

Blenderでmmd_toolsを使用しpmx/pmdを読み込んだのち、
fbxで出力しUnreal Engine 4 (以下UE4)等で使用したいとします。
この時日本語のボーン名が文字化けをおこし正常に動かないケースがあります。
それを回避するためにはボーン名を適当にASCIIキャラクターへ
変更すれば良いのですが、
まずひとつひとつ入力するのが非常に面倒なのである程度自動化したい、
そしてせっかくなのでUE4内でボーンリターゲットして再利用しやすいように
汎用的なボーン名に変更しようという目的で書かれたのが本スクリプトです。


# 使用方法

Blenderのメニューからテキストエディター(Text Editor)を開き、
このスクリプトをコピーアンドペーストで貼付け、
モデルのアーマチャ―が選択されている状態で「スクリプト実行」してください。
準標準ボーンに対応していますが、必要に応じて適当に変更してください。


# お断り

このスクリプトを使用した結果生じたいかなる不利益に対しても
作者は一切の責任を負いません。


# 作者について

ちょむP (TakeponG)
http://chomstudio.com
https://twitter.com/chom


# License

The MIT License (MIT)

Copyright (c) 2015 Chom.P

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.