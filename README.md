##
arbitrage bots running across different blockchains <br>
looking for: <br>
	1. arbitrages via atomic swaps (selling and buying a token in the same tx on the same chain) <br>
	2. cross-chain arbitrages (selling on one chain and buying on another, the swap is not atomic) <br>
and maybe:
	- arbitrages with one leg off-chain and another on-chain (e.g buying on coinbase and selling on uniswap) <br>
	- liquidations <br>

evm = ethereum virtual machine <br>
Exclusively on evm-chains at first because it's easier. <br>

### week 1-3
- learn more about MEV (https://docs.flashbots.net/new-to-mev) and solidity (the evm programming lang)
- set up real-time price feeds from a chosen set of chains
- write testbots in JS and solidity and monitor for opportunities

### week 3+
- run the bots on testnets and see if they work
- test the bots on mainnet
- will probably get outcompeted -> rewrite the JS part in go or rust


why JS from the start? the easiest language to prototype with because of the libraries hardhat and ethers-js
