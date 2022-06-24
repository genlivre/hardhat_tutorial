# hardhat Tutorial
[https://hardhat.org/tutorial](https://hardhat.org/tutorial)

## テストの実行
```npx hardhat test```

## コントラクトのデプロイ
### localへのデプロイ
```npx hardhat run scripts/deploy.js```

### Rinkebyへデプロイ
```npx hardhat run scripts/deploy.js --network rinkeby```

### etherscan(Rinkeby)へverify
```npx hardhat verify --network rinkeby デプロイしたコントラクトAddress```

### 再度verify
```npx hardhat clean```
