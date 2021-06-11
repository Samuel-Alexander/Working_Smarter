# Working Smarter
Using Smart Contracts to make paying employees easier 

![contract](Images/smart-contract.png)

## Dependencies
* [Remix IDE](https://remix.ethereum.org)
* [Ganache](https://www.trufflesuite.com/ganache)
* [MetaMask](https://metamask.io/)

## Summary
This Repo contains Solidity smart contracts that satisfy the following payment conditions:

* Even distribution: `AssociateProfitSplitter.sol` accepts Ether into the contract and divides it evenly among Associate Level employees. This allows a Human Resources department to pay employees with equal rank and salary quickly and efficiently.

* Tiered distribution: `TieredProfitSplitter.sol` distributes different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

* Deferred Equity: `DeferredEquityPlan.sol` distributes company shares for employees in a "deferred equity incentive plan" automatically based upon traditional company stock plans. This contract automatically manages 1000 shares with an annual distribution of 250 over 4 years for a single employee.
