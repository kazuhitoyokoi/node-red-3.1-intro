---
marp: true
paginate: true
---
# Node-RED v3.1新機能紹介
2023年5月26日 横井一仁

https://kazuhitoyokoi.github.io/node-red-3.1-intro

---
## 横井 一仁 (よこい かずひと)
- Node-RED開発メンバ
  - GitHubコミット数 世界3位
  - 和訳や不具合修正で貢献
- Node-RED User Group運営メンバ
  - Node-RED Con運営
  - UG Enterprise運営
- 日立製作所
  - ソリューションアーキテクト
  - DX、Industry 4.0研修講師
![w:400 bg right](https://nodered.jp/images/yokoi.jpg)

---
# Open Source Summit North Americaで<br>登壇してきました🇨🇦
 - ノードをつくるハンズオンの<br>内容を発表
 - OpenJS Foundationトップの<br>Robin様にも挨拶できました
![w:640 bg right vertical](https://pbs.twimg.com/media/Fv4TUloWAAIEmuw?format=jpg)
![bg right vertical](https://github.com/kazuhitoyokoi/node-red-3.1-intro/blob/main/robin.jpg?raw=true)

   セッションページ: https://sched.co/1K5CB

---
# 月刊I/Oにプロジェクト機能の記事を連載中📚
 - 3月号: プロジェクト機能の概要
 - 4月号: プロジェクトの切り替え
 - 5月号: フローのバージョン管理
 - 6月号: GitHubへフローを共有
 - 7月号: GitHubからフローを取得
 - 8月号: フローをクラウド環境へ<br>　　　デプロイ(予定)
![bg right](https://pbs.twimg.com/media/FplCZZnaUAcopKn?format=jpg&name=large)

---
# 私からご紹介するNode-RED v3.1の新機能
 - ノードの説明タブにMermaid図を表示
 - ノードの説明タブにインライン画像を追加
 - グローバル環境変数
 - プロジェクト関連の修正
 - 日本語訳

---
# Mermaidとは
- Mermaidとは、Markdown上でテキストで図を書く記法
- 2022年2月からGitHub、<br>2022年4月からQiitaでも利用可能<br><br>

  Mermaidのサイト: https://github.com/mermaid-js/mermaid

![bg right](https://raw.githubusercontent.com/mermaid-js/mermaid/develop/img/header.png)

---
# ノードの説明タブにMermaid図を表示
MarkdownエディタでMermaid記法を用いて、左側の説明タブに図を表示できる
- ノードの説明以外でも利用可能
  - フローの説明書き
  - グループの説明書き
  - プロジェクト機能のREADME.mdファイル
- プレビュー機能でリアルタイムに生成される図を確認しながら記述

![w:600 bg right](https://user-images.githubusercontent.com/30289092/210740564-5c0df1e8-5a3b-46bb-b2a2-5b36bdbbcf18.png)

---
# Mermaidのデモ
 - フローの説明書き
 - ChatGPTで生成したフローの説明書き
 - プロジェクト機能で作成した図をGitHubで表示

---
## ノードの説明タブに<br>インライン画像を追加
- Markdown中に画像のバイナリデータを挿入できる機能
- フローと同一JSON内にフローと画像が格納される

![w:600 bg right](https://user-images.githubusercontent.com/30289092/210725017-0f55c9f3-1bef-438c-be53-ce0a3b158be6.gif)

---
## グローバル環境変数
hoge
![w:600 bg right](https://user-images.githubusercontent.com/30289092/210725017-0f55c9f3-1bef-438c-be53-ce0a3b158be6.gif)

![w:600 bg right](https://camo.qiitausercontent.com/1da920248905bd1814f2ef607d715d2f7898968d/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e61702d6e6f727468656173742d312e616d617a6f6e6177732e636f6d2f302f3534363231372f36333735643039392d616230312d366537392d633931642d3761656132646331646264612e706e67)

---
## プロジェクト機能の修正
 - デフォルトのフローファイル名がflow.jsonからflows.jsonに変更
 - node-redコマンドでフローを指定しなくても起動できるようになった。

---
## 日本語訳
 - プロジェクト
![w:600 bg right](https://user-images.githubusercontent.com/30289092/210725017-0f55c9f3-1bef-438c-be53-ce0a3b158be6.gif)

---
## 最後に
 - Node-RED v3.1
