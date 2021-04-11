# DevContainer for CSharp

DevContainerではじめるC#開発のためのお手軽キット

## 揃う環境

- .NET 5.0
- Node.js
- Azure Cli
- Visual Studio Codeの拡張機能いろいろ

## 必要なもの

### ローカルのDockerを使う場合

1. [Visual Studio Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
2. [Visual Studio Code Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
3. [Docker Desktop](https://www.docker.com/products/docker-desktop)
4. [GitHub](https://github.com/)のアカウント

### GitHub Codespacesを使う場合

……まだ確かめられないので誰か検証お願いします。

## 開発の始め方

### ローカルのDocker Desktopではじめる場合

1. このリポジトリから新しいリポジトリを作る
2. ローカルにクローン
3. Visual Studio Codeを開く
4. 左下のリモート接続メニューを呼ぶ
5. `Remote-Containers: Reopen in Container`を選ぶ
6. 少々待つと、Bashが立ち上がる
7. あとはお好きに開発を！
