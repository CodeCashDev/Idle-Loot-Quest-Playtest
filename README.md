# Idle Loot Quest プレイテスト

ブラウザで遊べます。初回はゲームデータの読み込みに時間がかかることがあります。

[ゲームを開く](https://codecashdev.github.io/Idle-Loot-Quest-Playtest/)

## 配布版の更新

1. Godot の Web プリセットで、新しい空のフォルダに `index.html` としてリリースを書き出します。
2. 書き出されたファイル一式を `idle-loot-quest-web.zip` にまとめます。ZIP を展開した直下に `index.html` が来るようにします。
3. このリポジトリの Releases で新しいタグを作り、ZIP を添付してリリースを公開します。

リリースを公開すると、GitHub Actions が ZIP を展開して同じ URL にデプロイします。既存のリリースを配布し直す場合は、Actions の **Publish web playtest** を開き、タグを指定して実行します。
