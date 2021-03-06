# 2020年度 統計学 中間レポート(Markdown版)

<div style="text-align:right">
担当: 社会情報科学部 山本 岳洋 <br>
t.yamamoto@sis-u-hyogo.ac.jp <br>
講義ページ: <a href="https://tyamamot.github.io/statistics-2020/">https://tyamamot.github.io/statistics-2020/</a>
</div>


---

中間レポートのMarkdown用ファイルです．ヒント等は省いていますので，必ず[講義ページ](https://tyamamot.github.io/statistics-2020/)よりWord版かPDF版のレポート課題を確認してください．

**提出は .md ファイルではなく PDF を提出すること**

---



## 問1.（1変数データの記述と要約）
標準化されたデータ $z_1, z_2, \cdots, z_n$ の個々のデータ $z_i$ ($1 \leq i \leq n$) に対して，以下の変換を行う．

$t_i = 4z_i + 50$

このとき，変換後のデータ$t_1, t_2, \cdots, t_n$ の平均 $\bar{t}$ と標準偏差 $S_t$ を求めよ．なお，結果だけでなく途中の式も示すこと．標準化されたデータ  $z_1, z_2, \cdots, z_n$  の平均 $\bar{z}=0$, 標準偏差 $S_z=1$ は既知としてよい．
$$
\bar{t} = \frac{1}{n}\sum_{i=1}^{n}t_i
$$









## 問2. （ベイズの定理）
モンティ・ホール問題について考える．いま，回答者が扉aを選んだ．講義資料「確率の基礎」に記載したように事象を定義する．すなわち，

- 事象 $A_1$ : 扉aが正解である
- 事象 $A_2$ : 扉bが正解である
- 事象 $B$ : 司会者が 扉cを開ける

とするとき，ベイズの定理を用いて $P(A_1│B)$ と $P(A_2│B)$ をそれぞれ求めよ．そして，その結果に基づき，司会者が扉cを開けたとき，回答者は初めに選んだ扉aから扉ｂに選択を変えた方が良いかどうか解答せよ．


## 問3. （二項分布）
国民の10%がかかっていることが分かっている病気がある．以下の確率a)-c)を計算せよ．どの問題も感染者の数は二項分布に従うと仮定してよい．この問題はExcel（かGoogleスプレッドシート）を用いて二項分布の確率を計算し解答すること．

- a) 国民20人を調べたときに感染者が4人である確率はいくらか．解答はパーセントで解答し，小数点第2位まで求めればよい．
- b) 国民200人を調べたときに感染者が40人である確率はいくらか．解答はパーセントで解答し，小数点第5位まで求めればよい．
- c) 国民200人を調べたときに感染者が40人以上である確率はいくらか．解答はパーセントで解答し，小数点第5位まで求めればよい．


## 問4. （離散型の確率変数）
離散型の確率変数 $X$ の取りうる値が $x_1, \cdots, x_n$，その確率が $p_1, \cdots, p_n$，離散型の確率変数 $Y$ の取りうる値が $y_1, \cdots, y_m$，その確率が $q_1, \cdots, q_m$ として与えられている．いま，$X$ と $Y$ が互いに独立であるとき，$E(XY)=E(X)E(Y)$ が成り立つことを示せ．


## 問5. （正規分布その1）
政府の平成28年「国民健康・栄養調査」によると日本人の12歳男性の身長は平均150.8 cm，標準偏差8.6 cm であることが知られている．いま，12歳男性の身長が正規分布 $N(150.8,8.6^2)$  に従うと仮定し以下の問いa), b)に答えよ．なお，この問題は教科書もしくは参考書の標準正規分布表を用いて解答すること．

- 身長が133.6 cm 以上 168.0 cm 以下の日本人12歳男性の割合を求めよ．解答はパーセントで解答し，小数点第1位まで求めればよい．なお，答えだけでなく途中の考え方についても示すこと．
- 12歳男性を身長が高い順に並べたとき，上位10%以内に入るにために必要な身長はいくらか求めよ． 解答は小数点第1位まで求めればよい．なお，答えだけでなく途中の考え方についても示すこと．


## 問6. （正規分布その2）
問5と同じ問題設定において，以下の問いa), b)に答えよ．この問題はExcel（もしくは Googleスプレッドシートを使って回答すること）

- a) 12歳男性を身長が高い順に並べたとき，中間の95%（上位2.5%から上位97.5%）の男性の身長は $a$ cm以上 $b$ cm以下の区間にはいる．この $a$ と  $b$ を求めよ．小数点第1位まで求めればよく，また，答えだけ記述すればよい．
- いま，ある12歳男性の身長を調べたところ 175.0 cm であった．このとき，この男性は身長の高い方から数えて上位0.5%以内に入っていると言えるかどうか調べよ．答えだけでなく途中の考え方についても示すこと．


## 問7. （正規分布その3）
問6のa)とb)と同様のことを， Excelや標準正規分布表を用いず，必要があれば以下を使って求めよ．また，答えだけでなく途中の考え方についても示せ．

> 確率変数 $Z$ が標準正規分布 $N(0,1)$ に従うとき，以下が知られている
> $P(-1.96 \leq Z \leq 1.96)=0.95$  
> $P(-2.58 \leq Z \leq 2.58)=0.99$


- a) 12歳男性を身長が高い順に並べたとき，中間の95%（上位2.5%から上位97.5%）の男性の身長は $a$ cm以上 $b$ cm以下の区間にはいる．この $a$ と $b$ を求めよ．小数点第1位まで求めればよい．答えだけでなく途中の考え方についても示すこと．
- b) いま，ある12歳男性の身長を調べたところ 175.0 cm であった．このとき，この男性は身長の高い方から数えて上位0.5%以内に入っていると言えるかどうか調べよ．答えだけでなく途中の考えかたについても示すこと．



### 参考文献:
（レポートを書くにあたり，参考にした書籍やウェブページがあれば，最後に記載すること）

---
以降は発展課題です．余裕がある人だけ，取り組めるだけ取り組んでください．


## 発展課題その1.（順位相関係数）
以下は，ある食堂の8つのメニューについて，２名の教員に順位付けしてもらった結果である．

教員E:  1位. チキン香草焼き，2位. 塩だれカツ丼，3位. 鯖生姜煮，4位. 麻婆豆腐，5位. 県大唐揚げ，6位.カレーライス，7位. ダッカルビ風野菜炒め，8位. ロースカツカレー

教員O:  1位. 県大唐揚げ ，2位. チキン香草焼き，3位. ダッカルビ風野菜炒め，4位. 麻婆豆腐，5位. 塩だれカツ丼，6位. ロースカツカレー，7位. 鯖生姜煮，8位. カレーライス

さて，２つの順序の相関関係を測る尺度として，スピアマンの順位相関係数やケンドールの順位相関係数と呼ばれる尺度が知られている．各自どちらか一方の順位相関係数について調べよ．そして，上記の8つのメニューを自分の好みでランキングし，自分の好みが教員Eと教員Oの好みとどちらか近いか順位相関係数を実際に計算して確認してみよ．


## 発展課題その2.（回帰直線の導出）
最小二乗法による回帰直線の $a$ および $b$ を導出せよ．具体的には，誤差関数 $L$ を $a$ の二次関数 $L(a)$，$b$ の二次関数 $L(b)$ とみなし，$\frac{\mathrm{d}L(a)}{\mathrm{d}a}=0$, $\frac{\mathrm{d}L(b)}{\mathrm{d}b}=0$ という2つの方程式から得られる連立方程式を解くことで，$a$ および $b$ が講義資料の結果と一致することを確かめよ．




## 発展課題その3. （離散型の確率変数）
離散型の確率変数 $X$ と $Y$ が互いに独立であるとき， $V(X-Y)=V(X)+V(Y)$ が成り立つことを示せ．なお，期待値の線形性や加法性，$X$ と $Y$ が互いに独立であるとき $E(XY)=E(X)E(Y)$ が成り立つことなどは既知としてよい．



## 発展課題その4.（正規分布の確率，期待値，分散の確認）
ガウス積分と呼ばれる以下の公式が知られている：


$$
\int_{-\infty}^{+\infty}e^{-ax^2}dx = \sqrt{\frac{\pi}{a}}
$$

この公式を用いて，確率変数 $X$ が正規分布 $N(\mu, \sigma^2)$ に従うとき，
$\int_{-\infty}^{+\infty}f(x)dx = 1$ となっていること，また，期待値，分散がそれぞれ $\mu, \sigma^2$ となっていることを示せ．