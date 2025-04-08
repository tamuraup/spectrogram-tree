# spectrogram-tree

これは以下のリポジトリをコピーし、改変したものです。

[spectrogram-tree (original)](https://github.com/fkubota/spectrogram-tree)

clone していない理由は、オリジナルのリポジトリが重く、そのまま継承したくなかったからです。

## lisence

オリジナルのライセンスは以下

https://github.com/fkubota/spectrogram-tree/blob/master/LICENSE

本リポジトリでの改変内容は、コミットログを参照してください。


## インストール

Python 3.12.9 で動作確認済み。

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
