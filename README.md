---
marp: true
paginate: true
---
# Node-RED v3.1新機能紹介
2023年5月26日 横井一仁
https://kazuhitoyokoi.github.io/node-red-3.1-intro

---
## 自己紹介
- 横井 一仁 (よこい かずひと)
- Node-RED開発メンバ
  - GitHubコミット数 3位
  - 和訳や不具合修正で貢献
- Node-RED User Group運営メンバ
  - Node-RED Con
  - Node-RED UG Enterprise
- 日立製作所
  - ソリューションアーキテクト
  - DX、Industry 4.0研修講師
![w:400 bg right](https://nodered.jp/images/yokoi.jpg)
---
# Open Source Summit North Americaで<br>登壇してきました
 - ノードをつくるハンズオンの<br>内容で登壇
 - OpenJS Foundationの<br>Robin様にも挨拶できました
![w:600 bg right vertical](https://pbs.twimg.com/media/Fv4TUloWAAIEmuw?format=jpg)
---

# 本日紹介するNode-REDの新機能
 - Mermaid
 - インライン画像
 - グローバル環境変数
 - プロジェクト機能の修正
 - 日本語訳
---
# Mermaidとは
- Mermaidとは、Markdown上でテキストで図を書く記法
- 2022年2月からGitHub、<br>2022年4月からQiitaでも利用可能<br><br>

  公式サイト: https://github.com/mermaid-js/mermaid

![bg right](https://raw.githubusercontent.com/mermaid-js/mermaid/develop/img/header.png)

---
# Node-REDのMermaidサポート
- Markdownエディタ内でMermaid記法が可能
  - フローの説明書き
  - ノードの説明書き
  - グループの説明書き
  - プロジェクト機能のREADME.mdファイル
- プレビューも可能

![w:600 bg right](https://user-images.githubusercontent.com/30289092/210740564-5c0df1e8-5a3b-46bb-b2a2-5b36bdbbcf18.png)

---
# Mermaidのデモ
 - フローの説明書き
 - ChatGPTで生成したフローの説明書き
 - プロジェクト機能で作成した図をGitHubで表示

---
## インライン画像
- Markdown中に画像のバイナリデータを挿入できる機能
- フローと同一JSON内にフローと画像が格納される

![w:600 bg right](https://user-images.githubusercontent.com/30289092/210725017-0f55c9f3-1bef-438c-be53-ce0a3b158be6.gif)
---
## グローバル環境変数
---
## プロジェクト機能の修正
 - デフォルトのフローファイル名がflow.jsonからflows.jsonに変更
   - node-redコマンドでフローを指定しなくても起動できるようになった。
---
## 日本語訳
