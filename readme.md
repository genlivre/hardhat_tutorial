# hardhat Tutorial
[https://hardhat.org/tutorial](https://hardhat.org/tutorial)

# npmのインストール
```npm install```

# hardhatプロジェクトの作成(既にhardhatプロジェクトを作成済みの場合は不要)
```npx hardhat```

# hardhat compile
```npx hardhat compile```

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
