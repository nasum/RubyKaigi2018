# Ruby kaigi 2018

## Hijacking Ruby Syntax in Ruby
@joker1007
@tagomoris

jokerさん
tagomorisさん

Asakusa.rb

binding
コンテキストを保存する
変数のセット
bindingを実行するとその時点で参照できるローカル変数がとれる
テンプレートエンジンとかで使えそう
local_variable_set
おんなじブロックでも生成するオブジェクトIDが違う
local_variable_setをブロック内で実行してもブロックを出ると存在しない
ただ既存の変数の上が胃には使える
既存の変数を上書きするためにあるもの

TracePoint
例外を集めるためのものとドキュメントにあるが嘘
いろいろ集められる
bindingがとれる
任意の行のbindingを取ってこれる。
任意の変数を上書きできる

Refinements
局所的にクラスをパッチできる
その場所でしか使えない安全なprivateメソッドを定義出来る
作ったgem
final
override
abstract

hookしたときに実行するメソッドがRubyには抱負
MethodHook
finalを実現するには結構ハードルがある
includeはメソッドを追加しているのではなくメソッドを探索するチェーンを追加するだけ。
method_addedのフックが使えない

TracePoint
なんで使わないといけないのか
Rubyは上から順にクラス定義を巡に読んでいって終わるまでどんなクラスがあるか分からない。なのでTracePointを使う。

Ripper
S式

binding_ninja
呼び出し元のbindingを突っ込める
scalaのimplicit paramaterをRubyで実現してみる

productionモードがあるからdevelopmentのみ実行とかが出来る

undef_methodとremove_methodの違い
undef メソどっがないとマークされる
remove_methodは消す。superクラスにあればそれが使えるようになる

with statement
java python C#にはある機能

こういう機能を作るとRubyを隅から隅まで使ってる感じがしてとてもよい。
だがデバッグが難しい。
覚悟をもってやるように

覚悟は出来ているか。俺は出来ている。
















