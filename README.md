# Java
[引用](https://ja.wikipedia.org/wiki/Java)

特徴
- オブジェクト指向
- クロスプラットフォーム
- ポインタは利用不可
- 中間言語(Javaバイトコード）にコンパイルされ仮想マシン上で実行

# Java 開発環境
- Java SE
標準的な機能向け

- Java ME
情報家電や携帯端末組み込み機器向け
現在は、SEに統合されているらしい？？

- Java EE
サーバ・大規模システム向けの機能を提供する。
servletやjspはJava EEの技術である。

- J2SE J2ME J2EE
J2～はJava SE ME EEの旧称（5.0以前)を指す


# Java フレームワーク
エンタープライズ向けのJava開発における主流のフレームワークは以下
- Java EE
- Spring Framework
- Play Framework



# Java8
- ラムダ式の導入
- 型アノテーション
- Date and Time API 
- 高速JavaScriptエンジン Nashorn
- JavaFX 8
- マルチタッチデバイス対応
- HotspotとJRockitの統合

# JavaFx
Java仮想マシン上で動作するリッチインターネットアプリケーション (RIA) のGUIライブラリである。

# サーブレットの仕組み
サーブレットコンテナはウェブサーバマシン上に常駐する。
ウェブサーバはリクエストを受け取ると、サーブレットコンテナにリクエストを渡す。
サーブレットコンテナはサーブレットにリクエストを渡し、サーブレットの処理結果をウェブサーバへ返す。

# spring" 

動的プロジェクトを作成
HelloServletを作成

サーバ構成を追加

検証中
構成-Gradleネーチャーの追加
もしくはgradleプロジェクト作成



#STS起動まで
jdkをインストール
pathを通す

#spring mvc プロジェクト作成方法（spring boot 以前）
新規プロジェクト
spring regacy 

maven-update project
run as maven install


# web.xml
動作を規定する配備記述子を指定する必要があり、配備記述子はweb.xmlに記載する必要がある。
J2EE2.4にバージョンアップした際に、
web.xmlがDTD(Document Type Definition)ベースからXMLSchemaベースに変更になった。

サーブレット定義
サーブレットクラスを呼び出すためのURL定義
セッション定義
認証設定
ウェルカム・エラーページ

``` XML
<servlet-name>ロサンゼルス（あだ名）</servlet-name>
<servlet-class>ロサンゼルス１－３－３（本名）</servlet-class>

<servlet-mapping>
	<servlet-name>ロサンゼルス</servlet-name>
	<url-pattern>ロス</url-pattern>
</servlet-mapping>
```


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