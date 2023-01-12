# ShinPooh.com

## GitHub Pages を使って（なるべく無料の）ウェブサイト開発

### (1) GitHub Pages でウェブページを作成

- マークダウンファイルでウェブページを作成する

  - `README.md` を index.html 代わりに使う

  - サイト内リンクはなるべく相対パスで記述

- **https://(GitHub アカウント名).github.io/(リポジトリ名)** で公開する


この時点で `https://dotnsf.github.io/shinpooh-web` で公開される


### (2) 独自ドメインに更新

- [GoDaddy.com](https://godaddy.com/) で取得した **shinpooh.com** を使う

  - `CNAME www dotnsf.github.io` のレコードを作成する

  - リポジトリ内に以下の内容の `CNAME` ファイルを追加する

```
www.shinpooh.com
```

この時点で `http://www.shinpooh.com/` で公開される


### (3) 独自ドメインで SSL 有効化

- GitHub リポジトリの GitHub Pages 設定で **Custom domain** の `TLS certificate is being provisioned` が有効になるのを待つ（１５分程度）

- 有効になった後で `Enforce HTTPS` にチェック


この時点で `https://www.shinpooh.com/` で公開される


## Copyright

2023 K.Kimura @ ShinPooh.com all rights reserved.

