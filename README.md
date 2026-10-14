# MEMORY STONE

石ころと旅の思い出を結び付ける、ブラウザ向け試作品です。

## ローカルで起動

Python 3 がある環境で、プロジェクトルートから次を実行します。

```sh
python3 -m http.server 4173 --directory outputs
```

`http://localhost:4173` を開きます。

## GitHub Pages

`main` ブランチへの push で GitHub Actions が `outputs/` を Pages に公開します。GitHub リポジトリの Settings → Pages で、Build and deployment の Source を GitHub Actions に設定してください。

写真と記録はブラウザ内の IndexedDB に保存されます。サンプル旅行写真の表示にはインターネット接続が必要です。
