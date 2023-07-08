# CosVM Interface

An open source interface for CosVM -- a community-driven decentralized exchange for Cosmos and Ethereum assets with fast settlement, low transaction fees, and a democratic distribution -- powered by Cosvm Network.

- Website: [CosVM DEX](https://dexholder.com/)
- Interface: [CosVM App](https://cosvm.app)
- Telegram: [CosVM](https://t.me/cosvm)
- Discord: [CosVM](https://discord.com/invite/cosvm)
- Twitter: [@CosVMdex](https://twitter.com/cosvm)



## Accessing the CosVM Interface

Visit [cosvm.app](https://cosvm.app).

## Development

### Install Dependencies

```bash
yarn
```


### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env.sample` named `.env`

Note that the interface only works on testnets where both 
[CosVM](https://github.com/CosVMdex/exchange-contracts) and 
[multicall](https://github.com/makerdao/multicall) are deployed.
The interface will not work on other networks.

## Attribution
This code was adapted from this Uniswap repo: [uniswap-interface](https://github.com/Uniswap/uniswap-interface)
