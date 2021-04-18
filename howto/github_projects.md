# Projects を使う

## Projects とは
Projects についての公式なドキュメントは <a href="https://docs.github.com/ja/github/managing-your-work-on-github/managing-project-boards">こちら</a> にあります。溜まった Issue の進捗状況を示すためのツールとなります。アジャイルと呼ばれるソフトウェア開発手法では、スプリントまたはイテレーションと呼ばれる、1週間～1カ月程度の小さな単位でスケジュールを区切り、その中で対応可能な Issue をこの Project 上に載せて管理します。以下の例では、To do / In progress / Done のカラムが用意され、スプリントで対応する Issue を To Do に配置します。Issue の担当者は、その Issue が進捗中であれば、In Progress に移動させ、完了すれば Done に移動させます。このステータスの移動は（残念ながら）自動化はされませんので、各担当者が行う手作業で必要があります。

<a href="https://user-images.githubusercontent.com/2966953/111907865-71932f00-8a9a-11eb-8e59-d6aeb30332c3.png"><img src="https://user-images.githubusercontent.com/2966953/111907865-71932f00-8a9a-11eb-8e59-d6aeb30332c3.png" width="500" alt="Projects"></a>

余談になりますが、トヨタ自動車のカンバン方式からヒントを得たとされたツールです。トヨタ自動車の工場では、誰もが見る場所にホワイトボードが設置され、この Projects と同様にステータスを示すカラムを用意し、その上に各社員の持っているアイテムをマグネットや付箋などでカラム上に張り付けて、ステータスを報告していたことに由来します。

## Project を作る・参照する

Project は短い期間である一つのスプリントを表現しているため、全体の完成までにはかなりの数の Project を作ることになります。先生から指定される GitHub リポジトリのページから、①[Projects] をクリックすると、現在クローズされていない Project 一覧が表示されます。各 Project を参照する場合は、該当の Project をクリックすることで、Project のページに進みます。新たに Project を作る場合は ②[New project] をクリックします。

<a href="https://user-images.githubusercontent.com/2966953/111909234-d735ea00-8a9f-11eb-9e64-b3ae75696f52.png"><img src="https://user-images.githubusercontent.com/2966953/111909234-d735ea00-8a9f-11eb-9e64-b3ae75696f52.png" width="500" alt="Project list"></a>

Create a new project のページが表示されたら、Project board name にプロジェクト名、Description にその概要（オプション）を記入し、Template を 最もシンプルな、"Basic kanban" にします。Template については、リポジトリの状態から自動で issue の状態を同期させるようなものもあります。最後に [Create project] をクリックすれば、新しい Project が作成されます。

<a href="https://user-images.githubusercontent.com/2966953/111909480-d3569780-8aa0-11eb-9d35-fcc50aeaa319.png"><img src="https://user-images.githubusercontent.com/2966953/111909480-d3569780-8aa0-11eb-9d35-fcc50aeaa319.png" width="500" alt="Create a new project"></a>

## Project に Issue を載せる

Project を参照した状態から、右上の [Add cards] をクリックします。

<a href="https://user-images.githubusercontent.com/2966953/115148447-94fdc980-a09a-11eb-9c58-87a81e92c8c0.png"><img src="https://user-images.githubusercontent.com/2966953/115148447-94fdc980-a09a-11eb-9c58-87a81e92c8c0.png" width="500" alt="Add card"></a>

すると、選択可能な Issue が表示されますので、Project に載せたい Issue を To do にドラッグ&amp;ドロップします。

<a href="https://user-images.githubusercontent.com/2966953/115148660-95e32b00-a09b-11eb-9873-a0b476028110.png"><img src="https://user-images.githubusercontent.com/2966953/115148660-95e32b00-a09b-11eb-9873-a0b476028110.png" width="500" alt="Drag &amp; Drop Issue"></a>

## Issue の状態を変える

Issue を To do 状態から In progress 状態に変更する場合、Issue を該当カラムにドラッグ&amp;ドロップしてください。なお、Issue 側をクローズしても、Project 側の状態は変わりません。ご注意ください。

<a href="https://user-images.githubusercontent.com/2966953/115148977-de4f1880-a09c-11eb-8c1e-8d4ce2bf474f.png"><img src="https://user-images.githubusercontent.com/2966953/115148977-de4f1880-a09c-11eb-8c1e-8d4ce2bf474f.png" width="500" alt="Change Issue status"></a>

## Project を Close する

[Projects] をクリックして、Project 一覧表示の状態から、クローズしたい Project の右隅にある [・・・] をクリックし、[Close] を選択します。

<a href="https://user-images.githubusercontent.com/2966953/115149213-0a1ece00-a09e-11eb-816d-744ad0f8789e.png"><img src="https://user-images.githubusercontent.com/2966953/115149213-0a1ece00-a09e-11eb-816d-744ad0f8789e.png" width="500" alt="Close Project"></a>

[Git Hub の使い方ページに戻る](github.md)