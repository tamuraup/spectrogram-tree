# spectrogram-tree

これは以下のリポジトリをコピーし、改変したものです。

[spectrogram-tree (original)](https://github.com/fkubota/spectrogram-tree)

clone していない理由は、オリジナルのリポジトリが重く、そのまま継承したくなかったからです。

## lisence

オリジナルのライセンスは以下

https://github.com/fkubota/spectrogram-tree/blob/master/LICENSE

本リポジトリでの改変内容は [PR](https://github.com/tamuraup/spectrogram-tree/pulls?q=is%3Aclosed+is%3Amerged+) またはコミットログを参照してください。

## インストール

以下環境で動作確認済みです。

- ~~Ubuntu 24.04~~ 
- Python 3.12.9

### ビルド

```bash
# パッケージのインストール
pip install -r requirements.txt

# アプリケーションのビルド
make build  # または `make -B build` を使用
```

ビルドに成功すると、`dist/spectrogram_tree/spectrogram_tree` が作成されます。

### アプリケーションの実行

`./dist/spectrogram_tree/spectrogram_tree` を実行してアプリケーションを起動します。

+ **私の ubuntu 24.04 だとビルドしたアプリでは音声が再生されませんでした…。**   
  `python src/spectrogram_tree.py` で実行すれば音声は再生されます。よくわかりません、助けてください。

+ macOS ではビルドしたアプリでも音声が再生されるようです。

## 使い方

```bash
spectrogram_tree [--root_dir=<ツリー表示するルートディレクトリ>]
```

`--root_dir` オプションで、ツリー表示するルートディレクトリを指定できます。
