文法

使う記号、子音の変化

| | C | C' | V |
| ---- | ---- | ---- | ---- |
| 0 | ε | h | ε/u |
| 1 | p | b | a |
| 2 | t | d | e |
| 3 | k | g | i |
| 4 | f | v | o |
| 5 | s | z | 'u |
| 6 | m | x | 'a |
| 7 | n | c | 'e |
| 8 | r | q | 'i |
| 9 | l | j | 'o |

以下の規則によって自然数と単語を対応させる。

15340

1. 与えられた自然数の十進表記を逆にする

04351

2. 左から順にC列、V列に交互に対応させる

εok'up

3. 母音の前に ' が付いている場合、1個前の子音をC'列のものに変化させる。εは消去する。

ogup

この対応によって得られる単語において、末尾にC'列の子音が現れることはないが、後の文法における子音の変化によって末尾の子音がC'列のものになる場合がある。



動詞  

そのままの形で動詞になる単語は無い。
名詞の末尾に n(n を付けた結果末尾に子音が2つ連続し、それが final consonant clusters に含まれないなら更に末尾に u を付ける)を付けると動詞になる。
子音を変化させないと自動詞になり、変化させると他動詞になる。

ex.
rokevot 発展  
rokevod 開発  
rokevodn 発展する  
rokevodca 開発する

文型は自動詞のとき V S、 他動詞のとき V S O。

動詞は連結させることができる。
その際、子音を変化させてスペース無しで連結し、連結している動詞の目的語や補語は全て共通する。

ex.
zos 作成  
zozca 作る  
tarit 終了  
taridn 終わる  
zoztaridca 作り終わる (全体で他動詞となる)



形容詞

形容詞は1つのみである。
tos Sentence ok で 文章を形容詞にする。
形容詞は修飾する名詞のすぐ後につく。

V...V S Adj ... Adj  
V...V S Adj ... Adj O Adj ... Adj



助詞

ze      A(u) uは自動詞のとき主語の、他動詞のとき目的語の補語 uと uに
ko      A(u) 動作の始点 uから uより
cus     A(u) 動作の途中 uを (トンネルを通る)
ak      A(u) 動作の方向 対象 uへ uに
anap    A(u) 動作の終点 uまで
tiet    A(u) 限定 uばかり uだけ uのみ
vun     A(u) 程度 分量 uほど uくらい
fil     A(u) 比較 uより
zil     A(u) 比較 uと同じかuより u以上に
he      A(u) 時間 uに
ma      A(u) 場所 uで
de      A(u) 動詞が使役のとき、使役されるほう uにVさせる
en      A(u) 動詞が受け身のとき、その動作の主 uに
du      A(u) 手段 uで
cel     A(u) 理由 uなので uゆえ
bivul   A(u) uがてら
vis     A(u) 共同の相手 uと
fos Sentence os で文章を副詞にする。
などなど

Par N で副詞句を作る。
その N は連結している動詞の間で共通。
副詞は文章の主語と目的語の後ろにつく。

V...V S Adj ... Adj Adv ... Adv  
V...V S Adj ... Adj O Adj ... Adj Adv ... Adv



助動詞と終助詞

助動詞

pa 使役 Vさせる
tu 直接受け身 Vられる
du 関節、被害の受け身 Vられる
mu 可能 Vられる
ma 希望 Vたがる
ka した方が良い して当然 Vるべき
fa 否定 Vない
sa 様態 Vそうだ
ra 推定 Vらしい
ja 比喩 Vみたい
xa 伝聞 Vそうだ
n 過去 Vた
s 推量 Vよう

終助詞

p 質問
t 確認
l 独り言つ

助動詞と終助詞は以下の正規表現で表される組み合わせが可能である

((ε|ma)((pa|patu|padu|tu|du)ma)\*(ε|pa|patu|padu|tu|du)|pu|u)(ε|ka)(ε|fa)(ε|sa)(ε|ra|ja)(nra|nja)\*(ε|s|n|ns|xa|xas|xan)(ε|p|t|l)

これを A とおく。
A != ε のとき、 (連結している)動詞が n、c で終わるなら na、ca に、もともと a が付いているならそのまま A を動詞の後ろにスペース無しでくっつける。

tu は他動詞にのみつけられ、tuのついた後の動詞は自動詞扱いとなる。
du は自動詞にも他動詞にもつけられる。duのついた後の動詞が自動詞か他動詞かは元の動詞が自動詞か他動詞かと同じ。
受け身のとき、 vis は（en N が省略されていても）動作の主の方にかかり、主語にはかからない。

pa が複数あり de が複数ある場合は de を省略しない。内側の de から順番にに内側の pa に対応させる
tu, du に対する en も同様

V...VAux...AuxPar S Adj ... Adj Adv ... Adv  
V...VAux...AuxPar S Adj ... Adj O Adj ... Adj Adv ... Adv

ex.

Diloznapadumafanxat no. 彼は変わらせられたがらなかったそうだね。



文章の中の文章

これまでの紹介した文法において、名詞句、名詞節は省略できる。
その際助動詞は単独で残る。

mos Sentence on で文章を名詞にする。

los Sentence os で文章を動詞にする。

内部の文章で主語や目的語や補語を省略した際、
Los Sentence os S
という文章は、「Sは内部の文章で省略された名詞句、名詞節(のリスト)である」という意味になる。
内部の文章で複数が省略されている場合、上の文章でSは省略された名詞句、名詞節の左から右の順のリストである。

tos Sentence ok で文章を形容詞にする。
内部の文章で名詞句、名詞節を省略した際の挙動は los on と同様。
それに加えて、内部の文章 Sentence において、(連結している)動詞が自動詞で、かつ主語が省略されて、副詞が無い場合、
つまり Sentence が(助動詞と終助詞のついた、連結している)動詞ただ1つで構成される場合、
N tos V...VAux...AuxPar ok を N V...VAux...AuxPar と省略して良い。

fos Sentence os で文章を副詞にする。



命令系

文章の始めに I をつけて命令系にする。

I V...VAux...AuxPar S Adj ... Adj Adv ... Adv  
I V...VAux...AuxPar S Adj ... Adj O Adj ... Adj Adv ... Adv






日本語の補助動詞

為る
tat Vしている Vしてる
hon Vしてある
成る
rop Vしてくる
taz Vしてみる
jol Vしていく
できる
rov Vしてしまう
遣る
居る
下さる
呉れる
tib Vしてあげる してくれる してやる
zez Vしておく
御座る
sec Vしだす
tiz Vしつける 押し付ける
rag Vしてもらう していただく
qas Vしかける
qaz Vしかかる
vufab Vし始める
borit Vしすぎる
