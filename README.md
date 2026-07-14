# Zenn Articles

Zennで公開する記事を管理するリポジトリ。

## 構成

- `articles/`: 記事
- `images/`: 記事で使用する画像

## 操作

### 記事の作成

```sh
npx zenn new:article
```

### 記事の一覧

```sh
npx zenn list:articles
```

### プレビュー

```sh
npx zenn preview
```

## 公開

branch を publish に切り替えて Push

```sh
git checkout publish
git push
```
