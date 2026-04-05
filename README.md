# pyconjp-2025-chair

PyCon JP 2025 座長 [@nishimotz](https://github.com/nishimotz) の日報ブログです。

サイト: https://pyconjp-2025-chair.nishimotz.com/

## 開発環境のセットアップ

```shell
bundle install
npm install
```

### 開発サーバーの起動

```shell
bundle exec jekyll serve --host 0.0.0.0 --incremental
```

### Linux 環境での追加セットアップ

```shell
sudo apt install -y ruby-full build-essential ruby-dev
sudo gem install bundler
bundle install --path vendor/bundle
npm install
```

