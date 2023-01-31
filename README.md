## これは何？

Markdownからドキュメントを生成する[mdBook](https://github.com/rust-lang/mdBook)というRustでできたツールを利用した
Perlの日本語ドキュメントのためのテンプレートです。

このテンプレートを利用すれば、次のようなPerlのコードの実行結果を確かめながら読めるドキュメントが作れます。
```perl
print "HELLO WORLD";
```

このテンプレートの利用方法は、このテンプレートをforkし、forkしたテンプレートからリポジトリを作成するのが良いと思います。
mdBookの利用方法は、mdBookのドキュメントを参照してください。

perlの実行には、現在、[wandbox](https://github.com/melpon/wandbox)を利用しています。
perlのバージョンは、5.34.0です。
