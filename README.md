# Haskell Playground

Haskell を試すための Docker 環境

## 使い方

```sh
(local) docker compose up -d
(local) docker compose exec app bash
(container) cd hello-world/

# コンパイルする場合
(container) make # コンパイル
(container) ./build/hello-world # 実行

# コンパイルせず実行する場合
(container) make run
```
