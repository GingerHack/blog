# blog

Ginger Ale Hackathonのブログです。

## 使い方

手元で動かす方法を説明します。その他、記事の書き方などについては[Wiki](https://github.com/GingerHack/blog/wiki)を参照してください。

まずは依存関係をインストールするために次のコマンドを実行してください。

```console
$ bundle install --path=vendor/bundle --jobs=4
```

記事のビルドは次のコマンドを実行します。このコマンドで、`_site`以下にHTMLなどが生成されます。

```console
$ bundle exec jekyll build
```

記事のプレビューは次のコマンドを実行します。出力されたURLをブラウザで開いてください (この場合は<http://127.0.0.1:4000/blog/>)

```console
$ bundle exec jekyll serve
```
