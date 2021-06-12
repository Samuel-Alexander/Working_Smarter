# Working Smarter
Using Smart Contracts to make paying employees easier 

![contract](Images/smart-contract.jpg)

## Dependencies
* [Remix IDE](https://remix.ethereum.org)
* [Ganache](https://www.trufflesuite.com/ganache)
* [MetaMask](https://metamask.io/)

## Summary
This Repo contains Solidity smart contracts that satisfy the following payment conditions:

* Even distribution: `AssociateProfitSplitter.sol` accepts Ether into the contract and divides it evenly among Associate Level employees. This allows a Human Resources department to pay employees with equal rank and salary quickly and efficiently.

* Tiered distribution: `TieredProfitSplitter.sol` distributes different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

* Deferred Equity: `DeferredEquityPlan.sol` distributes company shares for employees in a "deferred equity incentive plan" automatically based upon traditional company stock plans. This contract automatically manages 1000 shares with an annual distribution of 250 over 4 years for a single employee.

## AssociateProfitSplitter

![Screen Shot 2021-06-11 at 4 39 12 PM](https://user-images.githubusercontent.com/75221323/121759755-fb2c2900-caec-11eb-98c0-54d181a8928d.png)

![Screen Shot 2021-06-11 at 4 40 04 PM](https://user-images.githubusercontent.com/75221323/121759768-054e2780-caed-11eb-9060-fb5e1edc4c90.png)

![Screen Shot 2021-06-11 at 4 40 21 PM](https://user-images.githubusercontent.com/75221323/121759777-0c753580-caed-11eb-96d7-1a77d3d6226d.png)

![Screen Shot 2021-06-11 at 4 53 43 PM](https://user-images.githubusercontent.com/75221323/121759783-1434da00-caed-11eb-88d1-0da546882390.png)



## Tiered
<img width="243" alt="Screen Shot 2021-06-11 at 6 22 51 PM" src="https://user-images.githubusercontent.com/75221323/121759789-1ac35180-caed-11eb-9b3b-0273c7712e7e.png">


<img width="200" alt="Screen Shot 2021-06-11 at 6 23 35 PM" src="https://user-images.githubusercontent.com/75221323/121759798-257de680-caed-11eb-891a-b16270a5d08a.png">

<img width="194" alt="Screen Shot 2021-06-11 at 6 23 59 PM" src="https://user-images.githubusercontent.com/75221323/121759806-2b73c780-caed-11eb-9541-1b361f47d06c.png">



## Deferred

<img width="242" alt="Screen Shot 2021-06-11 at 6 29 57 PM" src="https://user-images.githubusercontent.com/75221323/121759813-33cc0280-caed-11eb-8f7a-ca004773d4f2.png">


<img width="202" alt="Screen Shot 2021-06-11 at 6 30 01 PM" src="https://user-images.githubusercontent.com/75221323/121759825-3cbcd400-caed-11eb-8e57-2158f264c090.png">

<img width="198" alt="Screen Shot 2021-06-11 at 6 30 17 PM" src="https://user-images.githubusercontent.com/75221323/121759828-40e8f180-caed-11eb-9cae-562372cff545.png">

<img width="204" alt="Screen Shot 2021-06-11 at 6 46 53 PM" src="https://user-images.githubusercontent.com/75221323/121759835-49412c80-caed-11eb-8a5f-41103709ef38.png">

<img width="353" alt="Screen Shot 2021-06-11 at 7 31 45 PM" src="https://user-images.githubusercontent.com/75221323/121759859-65dd6480-caed-11eb-91f9-b5db6cefc71d.png">

## Deployment to the Kovan testnet
<img width="356" alt="Screen Shot 2021-06-11 at 7 28 27 PM" src="https://user-images.githubusercontent.com/75221323/121759857-6544ce00-caed-11eb-8f7f-8456d324c3e9.png">

<img width="353" alt="Screen Shot 2021-06-11 at 7 31 45 PM" src="https://user-images.githubusercontent.com/75221323/121759869-72fa5380-caed-11eb-83e5-879775ac0f7d.png">

<img width="351" alt="Screen Shot 2021-06-11 at 7 32 42 PM" src="https://user-images.githubusercontent.com/75221323/121759873-768dda80-caed-11eb-9bd3-bbbb5c9353cd.png">




