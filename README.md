# NA Projekt

## Arbitrage bots
Arbitrage bots will be running across different blockchains with 2 (4) objectives:

1. Arbitrages via atomic swaps. [ *Selling and buying a token in the same TX on the same chain* ]
2. Cross-chain arbitrages. [ *Selling on one chain and buying on another chain* ]
3. (?) Arbitrages with one leg off-chain and another on-chain.
4. (?) Liquidations.

## TODO
**EVM** = Ethereum Virutal machine
**Solidity** = **EVM** programming language

***Note***: Targeted exclusively on EVM-chains to recude complexity.

**JavaScript** will be used as a prototyping language due to its suitable libraries (***Hardhat*** and ***Ethers-js***).

### Preperation (Week 1-3)
- [ ] Learn more about **MEV** (https://docs.flashbots.net/new-to-mev) and **Solidity**.
- [ ] Set up real-time price feeds from a chosen set of chains.
- [ ] Develop testbots using **JS** and **solidity**.

### Future (Week 3+)
- Run and test the bots on testnets. 
- Test the bots on mainnet.
- Rewrite in faster language if necessary.


why JS from the start? the easiest language to prototype with because of the libraries hardhat and ethers-js
