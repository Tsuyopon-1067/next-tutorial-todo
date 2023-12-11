### run
```npm run dev```

```npm run json-server```


### docker
```docker compose run --rm app sh -c 'npx create-next-app@latest . --typescript'```
- --rm: コンテナ終了後に自動的に削除
- app: 実行するサービス名
- sh: シェル
- -c: あとに続く文字列がコマンド

```docker compose up```

```docker compose run --rm app sh -c 'npm i json-server'```

```docker compose run --rm test-server sh -c 'npm i json-server'```

```docker compose run --rm app sh -c 'npm run json-server'```

設定を再読み込みし変更を適用

```docker compose up -d```