"# spring" 

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
web.xmlがDTDベースからXMLSchemaベースに変更になった。

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

# Java API
- Java SE
標準的な機能向け

- Java ME
情報家電や携帯端末組み込み機器向け
現在は、SEに統合されているらしい？？

- Java EE
サーバ・大規模システム向け

- J2SE J2ME J2EE
J2～はSE ME EEの旧称を指す

# Javaの開発
エンタープライズ向けのJava開発における主流のフレームワークは以下
- Java EE
- Spring Framework
- Play Framework