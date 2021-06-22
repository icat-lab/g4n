# Markdown 形式で、引用・Link を使う

## 引用

Markdown 形式で、他の文章からテキストを引用を用いる場合、`>` で引用できます。例えば、以下のように入力します。

```
ユルゲン・ハーマスは『公共性の構造転換』で以下のように指摘している。
> 自己疎外の根源的生起は、文明の進歩の責任に帰せられる。「社会契約論」の天才的手法は、この裂け目をいやそうとするものである。各人は人心と財産を一切の権利もろとも共同体に委ね、それ以後は一般意思の媒介によって万人の権利と義務に参与するのである。
```
すると、表示は以下のようになります。

- - -
ユルゲン・ハーマスは『公共性の構造転換』で以下のように指摘している。
> 自己疎外の根源的生起は、文明の進歩の責任に帰せられる。「社会契約論」の天才的手法は、この裂け目をいやそうとするものである。各人は人心と財産を一切の権利もろとも共同体に委ね、それ以後は一般意思の媒介によって万人の権利と義務に参与するのである。
- - -  
引用に関する詳細は[こちら](https://docs.github.com/ja/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text)を参照ください。

## ソースコードなどの引用

利用する機会は少ないかと思いますが、Markdown 形式の文書や HTML の文書のソースコードを示したい場合、バッククオート ` を利用します。

```
文章をコミットする場合、 `git commit` を使います。 
```
上記は、以下のように表示されます。 

- - -
文章をコミットする場合、 `git commit` を使います。   
- - -


文章全体を引用する場合、バッククォートと3つ書いて、始まりと終わりを表現します。このような範囲をコードブロックと言います。

````
```
ファイルを追加し、コミットする手順：
git add
git commit
```
````
すると、表示は以下のようになります。
```
ファイルを追加し、コミットする手順：
git add
git commit
```
改行などもそのまま表示されることが分かります。  
なお、通常の Markdown 形式の文書で、改行するためには、行の最後に半角スペースを二つ入れてから改行します。

コードブロックに関する詳細は、[こちら](https://docs.github.com/ja/github/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)を参照ください。

## LINK を使う

リンクは、ウェブページ上で、ある特定の URL へ移動する文字列を指定できます。書き方は以下のように行います。

```
[リンクする文字列](リンク先 URL)
```


URL はあるサイトのページを示すこともできますし、あるページ内のあるアンカーへジャンプすることもできます。GitHub 上の Markdown 文書の場合、各タイトル（`# で指定されたタイトル`) にマウスを乗せると、リンク先が表示されます。

<a href="https://user-images.githubusercontent.com/2966953/122950734-a83d5600-d3b7-11eb-980e-9f47de5c8178.png"><img src="https://user-images.githubusercontent.com/2966953/122950734-a83d5600-d3b7-11eb-980e-9f47de5c8178.png" width="500" alt="Issues"></a>

インターネットの世界では、参照可能とされるものには全てに URL が付与されます。例えば、Slack 上特定の会話も、以下の「Copy Link」を用いることで、その会話への URL を取得することが可能です。

<a href="https://user-images.githubusercontent.com/2966953/122951486-47624d80-d3b8-11eb-9369-344cb70d8c26.png"><img src="https://user-images.githubusercontent.com/2966953/122951486-47624d80-d3b8-11eb-9369-344cb70d8c26.png" width="500" alt="Issues"></a>

例として、この会話へリンクする場合、Markdown 形式の文書では次のように書きます。

```
深見先生のコメントは[こちら](https://icatlab.slack.com/archives/C01RT07SE4S/p1619665540006300)。
```

表示は以下のようになります。

- - -
深見先生のコメントは[こちら](https://icatlab.slack.com/archives/C01RT07SE4S/p1619665540006300)。
- - -

なお、HTML 文書が分かる人向けとなりますが、リンクに HTML タグを使うことも可能です。以下のように書いてもリンクの表示は同じになります。必ずしもこの記法が理解できる必要はありません。

```
深見先生のコメントは<a href="https://icatlab.slack.com/archives/C01RT07SE4S/p1619665540006300">こちら</a>。
```

