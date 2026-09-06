文法



動詞  

全ての動詞は基本形だと自動詞で、末尾の子音を変化させることで他動詞になる。
自動詞のとき V S,
他動詞のとき V S O

動詞は連結させることができる。
その際、連結している動詞の目的語や補語は全て共通する。
連結している動詞がすべて自動詞のとき V ... V S,
少なくとも1つが他動詞のとき V ... V S O


形容詞

形容詞は1つのみである。
tos Sentence ok で 文章を形容詞にする。
形容詞は修飾する名詞のすぐ後につく。

V ... V S Adj ... Adj  
V ... V S Adj ... Adj O Adj ... Adj



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

Par N で副詞句を作る。
その N は連結している動詞の間で共通。
副詞は文章の主語と目的語の後ろにつく。

V ... V S Adj ... Adj Adv ... Adv  
V ... V S Adj ... Adj O Adj ... Adj Adv ... Adv



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

V((ε|ma)((pa|patu|padu|tu|du)ma)\*(ε|pa|patu|padu|tu|du)|pu|u)(ε|ka)(ε|fa)(ε|sa)(ε|ra|ja)(nra|nja)\*(ε|s|n|ns|xa|xas|xan)(ε|p|t|l)

助動詞と終助詞が末尾についたことを分かりやすくするため、
動詞の末尾の子音を変化させてスペース無しで助詞を引っ付ける。
動詞が連結しているなら一番最後の動詞につける。

tu か du が存在しないとき、元の動詞が他動詞なら助動詞と終助詞を付けた後の動詞句の一番最後の子音を変化させる。
tu は他動詞にのみつけられ、最後の子音は変化しない。
du は自動詞にも他動詞にもつけられる。自動詞なら最後の子音は変化せず、他動詞なら変化する。
受け身のとき、 vis は（en N が省略されていても）動作の主の方にかかり、主語にはかからない。

pa が複数あり de が複数ある場合は de を省略しない。内側の de から順番にに内側の pa に対応させる
tu, du に対する en も同様

V ... VAux...AuxPar S Adj ... Adj Adv ... Adv  
V ... VAux...AuxPar S Adj ... Adj O Adj ... Adj Adv ... Adv



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
それに加えて、内部の文章 Sentence において、動詞が連結しておらず、自動詞で、かつ主語が省略されて、副詞が無い場合、
つまり Sentence が(助動詞と終助詞のついた)動詞ただ1つで構成される場合、
N tos VAux...AuxPar ok を N VAux...AuxPar と省略して良い。

fos Sentence os で文章を副詞にする。



命令系

文章の始めに I をつけて命令系にする。

I V ... VAux...AuxPar S Adj ... Adj Adv ... Adv  
I V ... VAux...AuxPar S Adj ... Adj O Adj ... Adj Adv ... Adv






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
