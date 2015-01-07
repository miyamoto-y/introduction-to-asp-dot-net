# introduction-to-asp-dot-net

## Get Started with ASP.NET

> ASP.NET is a free web framework for building great Web sites and Web applications using HTML, CSS and JavaScript. You can also create Web APIs, mobile sites, use real-time technologies like Web Sockets and more!

[ASP.NET-Get Started with ASP.NET](http://www.asp.net/get-started)

### ASP.NETとは？

[ASP.NET 入門 - ASP.NET とは？](http://aspnet.keicode.com/aspnet/what.php)

ASP.NETは、Microsoftが開発・提供しているWebアプリケーションフレームワークです。

Microsoftが提供している Visual Web Developer や Visual Studio などの
統合開発環境 (`IDE`) を用いると、 HTML や HTTP などの基本的な Webテクノロジーに
精通していなくても Webアプリケーションを開発できるのが特徴です。

---

以下、個人的な考えですが
ASP.NET (と Visual Studio) のメリットは、開発者がコードを書く量が
少なくて済むということだと思います。

多くの場合、ASP.NETの開発にはVisual Studioを使用すると思いますが
さすがに長い歴史を持つIDEなだけあって、基本的なコードを予め生成してくれたり
優秀なコード補完やリファクタリング機能が備わっています。

コード量が少なければ それだけ早く開発できますし、不具合が混入する割合も少なくなります。

一昔前はマシンパワーの問題でストレスもあったのですが、
最近のPCであればデバッグしつつの開発であってもVisual Studioのエディタが固まってコーディングできない、
なんて現象はほとんど発生しなくなりました。

---

### ASP.NET概要

![ASP.NET Architecture image](../images/asp-net-architecture.png)

* Sites

サーバーからHTMLなどを返すアプリケーションを作成する技術です。

クライアントはWebブラウザを想定しています。
一般的なWebアプリケーションだと思っていただいて問題ありません。


* Services

サーバーからXMLやJSONなどを返すアプリケーションを作成する技術です。

多くの場合はエンドユーザーから直接呼び出されることはなく、
クライアントとなるプログラムから呼び出されます。

クライアント側は受け取ったデータを処理した上で画面に表示します。

---

#### 今後取り上げる内容について

以下の様な内容を解説していきます。

1. `ASP.NET Web Forms`を使用した簡単なWebアプリケーションの開発手順について
2. `ASP.NET MVC`によるWebアプリケーション開発
3. `ASP.NET Web API`によるREST API開発
4. `ASP.NET`と`knockout.js`によるSingle Page Application開発

