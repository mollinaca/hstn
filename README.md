# hstn

https://hstn.mollinaca.dev 用の静的サイトです。

## 公開設定

- GitHub Pages: Deploy from a branch / `main` / `/ (root)`
- Custom domain: `hstn.mollinaca.dev`
- DNS: `hstn` の CNAME レコードを `mollinaca.github.io` に設定
- 証明書の発行後、Enforce HTTPS を有効化

`index.html` や静的ファイルを編集し、`main` に push して更新します。
`CNAME` は独自ドメインの指定、`.nojekyll` は Jekyll 処理を無効にするためのファイルです。
