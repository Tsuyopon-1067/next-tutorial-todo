```docker compose run --rm app sh -c 'npx create-next-app@latest . --typescript'```
- --rm: コンテナ終了後に自動的に削除
- app: 実行するサービス名
- sh: シェル
- -c: あとに続く文字列がコマンド

docker compose up