# OpuCoin
Smart-contracts for the token distribution of Opu Labs ICO.

* Vesting.sol
A vesting contract to store tokens for a year period and then release it in full or in 12 batches of 1/12th total assigned tokens.

* ColdStorage.sol
A holding contract that keeps the tokens for two full years, then releases them altogether to a pre-defined address.

* OPUCoin.sol
An ERC223 token contract with backwards compatibility to ERC20. Mints 12 billion tokens exactly once, to a specified address.

* Allocation.sol
A contract to be used by the backend to perform the initial token distribution after the crowdsale.
