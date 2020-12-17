# GitHub CLI test


## repo - リポジトリの操作


リポジトリの作成、クローン、表示などが行えます。

```
# リポジトリの作成
$ gh repo create [<name>] [flags]

# リポジトリのクローン
$ gh repo clone <repository> [<directory>] [flags]

# リポジトリのフォーク
$ gh repo fork [<repository>] [flags]

# リポジトリ内容の閲覧
$ gh repo view [<repository>] [flags]
```

## pr - プルリクエストの操作

プルリエクストの作成、マージ、レビューなどが行えます。たぶん一番使うコマンドですね。

```
# プルリクエストのブランチへのチェックアウト
$ gh pr checkout {<number> | <url> | <branch>} [flags]

# 現在のブランチからのプルリクエストの作成
$ gh pr create [flags]

# プルリクエストのクローズ
$ gh pr close {<number> | <url> | <branch>} [flags]

# プルリクエストの差分を確認
$ gh pr diff {<number> | <url>} [flags]

# プルリクエストの一覧を取得
$ gh pr list [flags]

# プルリクエストをマージ
$ gh pr merge [<number> | <url> | <branch>] [flags]

# プルリクエストにレビューを追加
$ gh pr review [<number> | <url> | <branch>] [flags]

# プルリクエストの内容を閲覧
$ gh pr view [<number> | <url> | <branch>] [flags]

# 自分に関係のあるプルリクエストのステータスを閲覧
$ gh pr status [flags]

# ドラフトのプルリクエストをレビューに変更する
$ gh pr ready [<number> | <url> | <branch>] [flags]

# クローズしたプルリクエストを再度オープンにする
$ gh pr reopen {<number> | <url> | <branch>} [flags]
```

## issue - イシューの操作

イシューの作成や、ステータスの確認などが行えます。

```
# イシューの作成
$ gh issue create [flags]

# イシューのクローズ
$ gh issue close {<number> | <url> | <branch>} [flags]

# イシューの一覧表示
$ gh issue list [flags]

# イシューの再オープン
$ gh issue list [flags]

# 自分の関連するイシューのステータス確認
$ gh issue status [flags]

# 指定のイシューの閲覧
$ gh issue view {<number> | <url>} [flags]
```
