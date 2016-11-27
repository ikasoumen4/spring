# XML(Extensible Markup Language)
文書やデータの意味や構造を記述するためのマークアップ言語の一つ。

# マークアップ言語
マークアップ言語とは、「タグ」と呼ばれる特定の文字列で地の文に情報の意味や構造、装飾などを埋め込んでいく言語のことである。

# スキーマ言語
SGMLやXMLで文書を作成する際に、その構造を定義する言語。

# SGML
XMLより難しいらしい。

# html
W3Cが定めたhyper text markup languageの略称。


# DTD
XMLが誕生した時から存在するシンプルなスキーマ言語である。

# XML Schema
DTDに代わるスキーマ言語である。
DTDに比べ細かく構造を指定できる反面、仕様が膨大である。

[参考](http://www.atmarkit.co.jp/ait/articles/0312/02/news002.html)

スキーマの定義例
```
//greetingをルート要素とし、内容は文字列で属性と子要素は持たない
<?xml version="1.0"?>
<xsd:schema xmlns:xsd="http://www.w3.org/2001/XMLSchema">	//スキーマの名前空間の指定　xsd（XML Schema Definition)
	<xsd:element name="greeting" type="xsd:string"/>
</xsd:schema>
```

命令一覧
- ComplexType
要素の型定義を行う。
- sequence
指定した順に要素が出現する。
- choice
指定した要素のうち、いずれか一つが出現する。
- all
指定した要素が必ず１回出現する。

# キーワード
- xmlns
XML Name Space
