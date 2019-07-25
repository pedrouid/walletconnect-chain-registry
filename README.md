# walletconnect-chain-registry

Standarized multi-blockchain registry

## Examples

```js
// cosmos-hub2.json
{
  "name": "Cosmos Hub",
  "rpc": [
    "tcp://0.0.0.0:26657"
  ],
  "network": "cosmos-hub2",
  "coins": [
    {
      "name": "Atom",
      "symbol": "ATM",
      "denom": "uatom",
      "granularity": 9
    }
  ],
  "interface": "cosmos",
  "custom": {
    "node_info": "http://178.128.246.154:1317/node_info",
    "moniker": "cosmos-do-sentryz1"
  }
}

// eip155-1.json
{
  "name": "Ethereum Mainnet",
  "rpc": [
    "https://mainnet.infura.io/v3/${INFURA_API_KEY}",
    "https://api.mycryptoapi.com/eth"
  ],
  "network": "eip155-1",
  "coins": [
    {
      "name": "Ether",
      "symbol": "ETH",
      "denom": "wei",
      "granularity": 18
    }
  ],
  "interface": "evm",
  "custom": {
    "chainId": 1,
    "networkId": 1
  }
}
```
