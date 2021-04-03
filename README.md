# azure-functions-local-sample
azure functions をローカル開発環境で動かしてみるサンプル

## install
```
yarn
```

## storageの起動
```
docker run -p 10000:10000 -p 10001:10001 mcr.microsoft.com/azure-storage/azurite
```

## ローカル実行
```
yarn start
```