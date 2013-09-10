JsonpWeb
========

javascript,Servlet,JavaEE5

satoA 20130909

HTML(Jquery)から、Servlet間をJsonpで通信させるサンプル。
サーバ側は、Glassfish（JavaEE5/JDK6）で作成。

イメージとしては、昔からあるGlassfishの業務サーバに、新しく
HTMLで通信させる用件を想定した。
※サーブレットまで行けば後は、EJBなり何なりでどうにでもなる。

JavaEE6でもよかったが、たいした違いはないのでEJBと連携する
サンプルでもそのうち。

JavaEE7になると、Jsonともっと親和するのでますますがんばって欲しい。
こちらもそのうちサンプル作りたいですね。

また、HTML側のJsonpは、Jsonpらしく、クロスドメインで動作している。
これは、ApacheCordovaで、Androidアプリ化することも想定している。
※実記確認済み。HTC EVO 3D。そろそろ新しいおもちゃが欲しいですね。


以下適当な英訳

this program is between HTML as Servlet on Jsonp communication.

HTML(JavaScript/Jquery) <-----(Jsonp taransfer)------>Servlet


Server is Glassfish3 (JavaEE5)

on NetBeans7.3
