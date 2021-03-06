# Git rebase Example for beginner

Git の branch をマージする時に rebase を利用してマージするための練習用のレポジトリです。

このリポジトリの branch の全体像は以下のようになっています。

![git-rebase-example-origin drawio](https://user-images.githubusercontent.com/5770480/139302539-fa5c6d09-8219-4c46-938e-e4c73896a906.png)

rebase を利用してマージし、以下のようなコミットログを作りましょう。
[Issues](../../issues) の番号順に対応します。

![git-rebase-example-expect drawio](https://user-images.githubusercontent.com/5770480/139302667-dfcf491f-b86a-41ca-a5dc-1805b54b8f6e.png)

**なぜ rebase を利用するのかというと、ログが直列になり読みやすくなります。**
rebase を利用しないでマージすると、以下のようなコミットログになります。

![git-rebase-example-without-rebase drawio](https://user-images.githubusercontent.com/5770480/139302706-c5b999d8-a17d-4a5a-848d-c60b670f126c.png)
