# arm64-vscode-deep-learning-project-template
A Deep Learning VSCode Remote-Container project template with PyTorch and Tensorflow for arm64 architecture, especially Applie Silicon (M1) Macs.


## 使い方

### 1. ARM Mac用Dockerをインストールする。

- ARM Mac用Docker: https://docs.docker.com/docker-for-mac/apple-m1/

### 2. Visual Studio Code Remote-Containers機能拡張をインストールする。

- VSCode Remote-Containers: https://docs.microsoft.com/ja-jp/learn/modules/use-docker-container-dev-env-vs-code/1-introduction
- [Remote-Containers機能拡張のインストール方法](https://qiita.com/sabure500/items/a117b8a1733193be455f)

### 3. プロジェクトテンプレートをダウンロードして解凍する。

- ダウンロード: https://github.com/sonoisa/arm64-vscode-deep-learning-project-template/archive/refs/heads/main.zip

### 4. Visual Studio Code Remote-Containersでプロジェクトテンプレートを開く

1. Visual Studio Codeの左下にある"><"のようなアイコンをクリックする。
2. Remote-Containers: Open Folder in Container...をクリックする。
3. 3で解凍したフォルダを選択する。dockerイメージのビルドの完了を待つ。
4. dockerコンテナの起動後に、利用するpythonを選択せよという警告が表示されたら"~/python3-venv/bin/python"を選択する。
