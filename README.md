# Kojocho-Resource-Pack

Minecraft Bedrock Edition 用のリソースパックです。

<!-- ここに紹介文を追記予定 -->

## インストール

1. [Releases](https://github.com/MomokaSada/Kojocho-Resource-Pack/releases) から `Kojocho-Resource-Pack.mcpack` をダウンロード
2. ダブルクリックで Minecraft にインポート

## 使い方

### 対応バージョン

- Minecraft Bedrock Edition 1.17.30 以上（manifest の min_engine_version に準拠）

### 有効化

1. `Kojocho-Resource-Pack.mcpack` をダウンロードする
2. ファイルをダブルクリックし、Minecraft にインポートする
3. Minecraft を起動し、設定 → グローバルリソース またはワールド設定 → リソースパック から「Kojocho-Resource-Pack」を有効化する

### 効果

- （パックの効果を記載）

### 注意事項

- リソースパックのため、サーバー側の設定や他のパックとの競合で表示が変わる場合があります
- 見た目のみの変更で、挙動は変更されません

## リリースの作り方

`v1.0.0` のようなタグを push すると、GitHub Actions が `resource_pack/` を zip して `.mcpack` を生成し、Release に添付します。

```bash
git tag v1.0.0
git push origin v1.0.0
```