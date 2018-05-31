# Ruby kaigi 2018 Exploring internal Ruby Through C Extention
@yuryu
Chromium contributor

C拡張

Cの拡張とは
CのインターフェースをRubyで使う
OSにアクセスできる
Init関数 requireしてloadされたときに一回実行される

RubyのHashをC++で再実装
HashはCSのよい例題

mark and sweap

TypedDate_Get_Struct

ベンチマーク

Ruby独自のhashは結構早い
C++のラップは若干遅い
GC周りで差が出た可能性がある

C拡張をパフォーマンスが欲しいから書くというのは待ったほうがいい
C言語で書いたコードはRubyの進化に追随しない

Cのライブラリを使いたいからそのインターフェースを書くというのが正解

Ruby Under a Microscope
Rubyソースコード完全解説
Incremental GC for Ruby interpreter
Ruby Hack Challenge
