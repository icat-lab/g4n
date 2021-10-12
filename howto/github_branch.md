# Branch を使う

## Branch とは

Branch とは、履歴を分岐して記録するためのものです。[サル先生のGit入門の「ブランチとは」の章](https://backlog.com/ja/git-tutorial/stepup/01/)が非常に丁寧に解説していますので、ご一読いただければと思います。以下、該当の章より転載となります。

<img src="https://backlog.com/ja/git-tutorial/assets/img/stepup/stepup1_1.png" width="500" alt="branch">

## Repsitory に Branch を追加する

先生から指定される GitHub リポジトリのページ左上 ① を押下し、② に新しい branch 名を入力後、③ [Create branch] をクリックします。

<a href="https://user-images.githubusercontent.com/2966953/136992162-03d01b11-08be-4797-9a62-7324f2f5c203.png"><img src="https://user-images.githubusercontent.com/2966953/136992162-03d01b11-08be-4797-9a62-7324f2f5c203.png" width="500" alt="Create new branch"></a>

以上で、新しい Branch が作成されます。[Repository を使う](github_repository.md)でご紹介したようにファイルを編集後、左上① の Branch を変更すると、編集されたファイルが元に戻っています。Branch ごとに履歴が管理されていることが分かります。

## Pull Request を使う

別 Branch での変更内容を、他の Branch（例えば main Branch）に反映させたい場合、Pull Request を行います。Pull request を選択します。

<a href="https://user-images.githubusercontent.com/2966953/136993868-d74ea9f8-22b8-4f98-af87-1c2e1b0dc21c.png"><img src="https://user-images.githubusercontent.com/2966953/136993868-d74ea9f8-22b8-4f98-af87-1c2e1b0dc21c.png" width="500" alt="input"></a>

[Compare & pull request] または、[New pull request] を選択します。[Compare & pull request] は差分が自動で検出された場合にのみ表示されます。

<a href="https://user-images.githubusercontent.com/2966953/136994372-e414e80e-8456-4397-914e-10d034b6211b.png"><img src="https://user-images.githubusercontent.com/2966953/136994372-e414e80e-8456-4397-914e-10d034b6211b.png" width="500" alt="commiot"></a>

[Compare & pull request] を選択した場合は、Pull Request を確認してほしい人を ① Assignees に選択し、② に Pull Request のタイトルと詳細を記入、③ [Create pull request] をクリックすることで、Pull Request が完了します。

<a href="https://user-images.githubusercontent.com/2966953/136995126-eb14c252-3ac7-4caf-bdcf-a9a2068ac340.png"><img src="https://user-images.githubusercontent.com/2966953/136995126-eb14c252-3ac7-4caf-bdcf-a9a2068ac340.png" width="500" alt="Success"></a>

[New pull request] を選択した場合は、compare: に Pull Request の元となる Branch を選択すれば、[Compare & pull request] の時と同様に Pull Reqeuest を行えるようになります。

<a href="https://user-images.githubusercontent.com/2966953/136995736-2028cb59-99ab-46a0-a462-b2b31fb4a06b.png"><img src="https://user-images.githubusercontent.com/2966953/136995736-2028cb59-99ab-46a0-a462-b2b31fb4a06b.png" width="500" alt="view"></a>


## Pull Request を受ける

Pull Request の Assignees として受けた場合、Pull requests にリクエストが表示されています。該当のリクエストをクリックします。

<a href="https://user-images.githubusercontent.com/2966953/136996508-4f8c0c1a-37eb-4e1e-acc6-fb385248db5a.png"><img src="https://user-images.githubusercontent.com/2966953/136996508-4f8c0c1a-37eb-4e1e-acc6-fb385248db5a.png" width="500" alt="edit"></a>

Pull Request の内容に問題がなければ、[Marge pull request] をクリックして、Main Branch に反映します。問題があれば、事由を記入の上、[Close pull request] でリジェクトすることもできます。

<a href="https://user-images.githubusercontent.com/2966953/136996910-3ab22857-1dda-468d-8785-3efe6bb7ba48.png"><img src="https://user-images.githubusercontent.com/2966953/136996910-3ab22857-1dda-468d-8785-3efe6bb7ba48.png" width="500" alt="edit"></a>

[Git Hub の使い方ページに戻る](github.md)




