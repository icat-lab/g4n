# Issues を使う

## Issues とは
Issues についての公式なドキュメントは <a href="https://docs.github.com/ja/github/managing-your-work-on-github/about-issues">こちら</a> にあります。ソフトウェア開発における、ユーザーフィードバックやソフトウェアのバグ報告などを書き留めておくためのツールですが、To Do アイテムの管理ツールとご理解頂いて差し支えありません。To Do としてやるべき事を Issue として登録し、そこに進捗状況を書き込んでいけるのです。そのようにすることで、行うべき事 Issue がどのくらいあり、現在どのくらい進捗しているかを管理します。

<a href="https://user-images.githubusercontent.com/2966953/111875875-5d3e2c00-89df-11eb-9028-d0a2f8f17d1e.png"><img src="https://user-images.githubusercontent.com/2966953/111875875-5d3e2c00-89df-11eb-9028-d0a2f8f17d1e.png" width="500" alt="Issues"></a>


## Issue の登録

先生から指定される GitHub リポジトリのページから、①[Issues] をクリックし、Issues ページを開きます。その後、②[New Issue] をクリックします。

<a href="https://user-images.githubusercontent.com/2966953/111877315-228bc200-89e6-11eb-869c-03400b26178c.png"><img src="https://user-images.githubusercontent.com/2966953/111877315-228bc200-89e6-11eb-869c-03400b26178c.png" width="500" alt="Issues"></a>

新しい Issue の入力画面となりますので、Title と Comment を入力、[Submit new issue] をクリックすれば、Issue の登録は完了です。必要に応じて、右のペインにある Assignee（Issue の担当者）、Labels、Projects（後述）、Milestone などを記入します。Comment は <a href="https://docs.github.com/ja/github/writing-on-github/basic-writing-and-formatting-syntax" target="_blank">Markdown</a>で記入します。Preview タブで Markdown でかかれたテキストをプレビューできます。

<a href="https://user-images.githubusercontent.com/2966953/111879958-130f7780-89ec-11eb-9311-ba28fdb99433.png"><img src="https://user-images.githubusercontent.com/2966953/111879958-130f7780-89ec-11eb-9311-ba28fdb99433.png" width="500" alt="Issues"></a>

### Markdown 形式について

GitHub では、多くの場面で Markdown 形式の記入が可能です。Markdown を用いることで、文書のタイトルや段落の表示体裁を自動的に整えることが可能です。この文書自体も Markdown で書かれています。例として、以下のような表示を考えてみましょう。

#### Markdown のサンプル
**サンプル** の *文章* はこんな感じ
- リストのサンプル
- リストのサンプル
> 引用のサンプル

上記のような表示を行いたい場合は、コメントに以下のように記述します。
```
#### Markdown のサンプル
**サンプル** の *文章* はこんな感じ
- リストのサンプル
- リストのサンプル
> 引用のサンプル
```

詳細については、 <a href="https://docs.github.com/ja/github/writing-on-github/basic-writing-and-formatting-syntax" target="_blank">こちら</a> の公式文書をご参照ください。

## Issue にコメントを追加する

Issue に進捗があった場合など、コメントを追記することができます。該当 Issue ページの一番下にあるボックスに、コメントを Markdown で記入し、[Comment] ボタンをクリックすることで、コメントを追記できます。Markdown のコメントを [Preview] タブでプレビューすることが可能です。また、コメント記入後 [Close with comment] をクリックすることで、Issue をクローズすることができます。これは Issue が終了した際に行います。

<a href="https://user-images.githubusercontent.com/2966953/111880328-35a29000-89ee-11eb-857d-91908f050d71.png"><img src="https://user-images.githubusercontent.com/2966953/111880328-35a29000-89ee-11eb-857d-91908f050d71.png" width="500" alt="Issues"></a>

