# walletconnect-chain-registry

Standarized multi-blockchain registry

## Examples

```js
// cosmos-hub2.json
{
  "name": "Cosmos Hub",
  "network": "cosmos-hub2",
  "interface": "cosmos",
  "coins": [
    {
      "name": "Atom",
      "symbol": "ATM",
      "denom": "uatom",
      "granularity": 9
    }
  ],
  "rpc": [
    "http://178.128.246.154:26657"
  ],
  "custom": {
    "lcd": "http://178.128.246.154:1317",
    "moniker": "cosmos-do-sentryz1"
  }
}

// eip155-1.json
{
  "name": "Ethereum Mainnet",
  "network": "eip155-1",
  "interface": "evm",
  "coins": [
    {
      "name": "Ether",
      "symbol": "ETH",
      "denom": "wei",
      "granularity": 18
    }
  ],
  "rpc": [
    "https://mainnet.infura.io/v3/${INFURA_API_KEY}",
    "https://api.mycryptoapi.com/eth"
  ],
  "custom": {
    "chainId": 1,
    "networkId": 1
  }
}
```
