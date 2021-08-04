# Template for environment setting
VSCodeに特化したリモート開発環境（GPU無しver）

## Prerequisite
- `~/.ssh/config`にて設定
  - `template.code-workspace`内の`"docker.host": "ssh://ubuntu@XXXXX"`部分に関係

## How to use?
1. template.code-workspaceを開く
2. VSCode左下部分のボタンを押し、`Reopen in Container`を押下することでリモートコンテナに入る
3. コンテナに入ったのち、`conda create -f environment.yml`を実行することで仮想環境が完成する
