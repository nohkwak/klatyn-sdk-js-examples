# Ethers.js by Example
To test Klaytn with ethers.js

## Technology Stack & Tools

- Javascript (Writing scripts)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [Node.js](https://nodejs.org/en/) (To run our scripts and install ethers.js)
- [Baobob](https://api.baobab.klaytn.net:8651) (Klaytn Test Net)

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
```
$ npm install
```

## Ethers.js scripts

### 1_accounts.js - Reads balance of KLAY of wallet address
- Input your wallet address
```
$ node examples/1_accounts.js
```

### 2_read_smart_contract.js - Reads the balance of wallet address from the contract
- Input your wallet and contract addresses
```
$ node examples/2_read_smart_contract.js
```

### 3_send_signed_transaction.js - Transfers 0.025 KLAY from account1 to account2 
- Input your account1 public key
- Input your account2 public key
- Input your account1 private key
```
$ node examples/3_send_signed_transaction.js
```

### 4_deploy_contract.js - Deploys contract on Baobob testnet by using Factory contract
- Input your account private key
```
$ node examples/4_deploy_contract.js
```

### 5_write_contract.js - Transfers entire balance of token of your choosing from account1 to account2 (on Baobob testnet)
- Input your account1 public key
- Input your account2 public key
- Input your account1 private key
- Input contract address of the token you want to transfer (You can use the deployed contract address from the previous script)
```
$ node examples/5_write_contract.js
```

### 6_contract_event_stream.js - Queries a block for transfer events
```
$ node examples/6_contract_event_stream.js
```

### 7_inspecting_blocks.js - Get transactions from block
```
$ node examples/7_inspecting_blocks.js
```