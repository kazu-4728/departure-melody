# INSTRUCTION.md

このプロジェクトでは、JR東日本の駅発車メロディを再生できるWebアプリをGitHub Pages上に構築します。

## 要求仕様
- 子供でも使いやすいUI（駅名検索、路線選択、再生・停止ボタン、電車画像）
- HTML + JS + JSON構成
- 音源は `audio/` フォルダから読み込み
- JSONは `station_index.json` と `lines/*.json` に分割
- GitHub Actions（deploy.yml）を用いて `gh-pages` に自動デプロイ

## Codexへの指示
このINSTRUCTION.mdに基づき、GitHub Pagesで動作する発車メロディ再生アプリを生成・構築してください。
