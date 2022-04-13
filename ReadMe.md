# Vite-ts-vue-example
# VSCodeのRemote Developmentをインストール
コマンドパレット -> show recommended extensions にあるので選択。
エクステンションId: `ms-vscode-remote.vscode-remote-extensionpack`

コマンドパレット-> Reopen in Container -> コンテナをvscodeからホストのように触れる

イメージをビルドし直すときは Rebuild and Reopen in Container

# コンテナ内から
```sh
npm create vite@latest vite-example -- --template vue-ts
cd vite-example
npm i
npm run dev
```
