# Vertial File System in pdfmake

> このプログラムはttfフォントデータを、PDFMakeで扱えるようにjs化したものです。

ファイルサイズを小さく抑えたフォントサブセットです。フルサイズのものは jpfontjsを使ってください。

このフォントデータはIPAフォントを利用しています
https://ipafont.ipa.go.jp/old/ipafont/download.html

IPAフォントをPDFMakeによってコンバートし、膨大な文字コードから、サブセットデータだけ抜き出しています。
サブセットに含まれる文字はsubset.txtを参照してください

> 使い方
yarn add ueda19850603/jpfontjs_xs



