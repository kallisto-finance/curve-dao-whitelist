# A Revised Proposal to Whitelist Kallisto’s Automated Vault Contract


# Summary
This proposal is a revision of our initial introduction proposal to Cuve DAO [here](https://gov.curve.fi/t/proposal-to-whitelist-kallistos-automated-vault-contract/4110) based on public and private comments. This Version2 proposal aims to address some of the questions and feedback from the Curve community regarding that initial proposal. Special thanks to the Curve folks who shared their perspectives. 

This proposal also aims to secure community support for the vote to whitelist the Kallisto Curve-APY Chaser Vault contract, enabling it to earn and to lock CRV rewards from LP staking. It will also enable Kallisto vaults to participate in Curve governance, Curve gauges, and to participate in LP boosting for Kallisto vault Liquidity Providers.

1. Whitelist Kallisto Finance Curve-APY Chaser vault contract in Curve’s SmartWalletList
2. Automatically lock CRV for extended durations for veCRV
3. Acquire veCRV to participate in Curve governance as well as to boost its Kallisto Liquidity Provider holdings.

# Abstract:
An introduction to Volume. Volume Finance is a launchpad team founded to explore new and decentralized ways to increase volume to AMMs. We have spent the last year working in the Cosmos ecosystem to support automated liquidity management projects such as Sommelier and Terra's Anchor Protocol.

Volume's current focus is on its blockchain https://palomachain.com and Dapp Kallisto, https://kallisto.finance. Paloma is a Cosmos-SDK chain whose validators execute transactions on smart contracts deployed on the EVM. Paloma's goal is to manage liquidity contracts such as those of Kallisto Finance that bring liquidity to Curve's AMM.

An introduction to Kallisto, the Bear. Kallisto v0 was previously built on Terra's Anchor Liquidition Queue to automate liquidation queue bids. As Terra's original chain and ecosystem is no longer, Kallisto moves to Ethereum to support the largest AMMs. Kallisto’s currently offers certain liquidity providers an automated Curve Finance APY chaser vault to move liquidity to the highest APY yields. This new vault provides a low-cost, continuously updating, data science-based strategy for liquidity providers to participate in the most profitable Curve pools even longer. 

By aggregating users’ deposits, monitor, and then respond to price dynamics, the vault intends to significantly reduce the cost to stay in the highest APY pools on Curve.

* Home Page & App: https://kallisto.finance
* Twitter: https://twitter.com/kallistofinance
* Documentation: https://kallisto-finance.github.io/kallisto-docs/
* Telegram: https://t.me/kallistofinance

# Motivation:
At a time when AMM liquidity supply (The LPs) must decide between the crypto-ecosystem risk premium and simply investing in US treasuries, due rising US interest rates, and a stronger US dollar, We at Volume think the status quo is no longer a valid strategy. We see both trading volumes and TVL continue to withdraw from all AMMs, including Curve. We continue to see less leverage and increasing risk-off profiles from crypto traders. Volume believes that Kallisto’s Curve Finance APY chaser vault can bring significant value to the Curve ecosystem. Kallisto intends to support Curve liquidity supply by giving another reason for LPs to stay in the Curve liquidity pools. We believe that whitelisting this vault’s contract will be a win for the Curve community and the protocol's survival.

By systematically scanning the most popular and liquid pools on Curve and dynamically moving the liquidity to the pool with the highest yield, the vault’s users enjoy the best LP opportunities. The vault’s automated LP managing service also improves the Curve user experience as select Liquidity Providers will not need to figure out which pool to join, nor will they need to constantly monitor their positions. Moreover, as users’ liquidity is aggregated and moved together, the transaction cost of switching pools is shared and therefore significantly reduced. As a result, we envision that the vault has the potential to strongly increase Curve’s TVL and enhance the user experience for Liquidity Providers who prefer to stay in Curve with low maintenance requirements.

If Kallisto’s Curve Finance APY chaser vault is whitelisted for CRV locking, the vault’s APY will receive a substantial boost of the supply of liquidity. We expect this should lead to more user deposits or at least to help maintain Curve's TVL against the further possibility of decreased liquidity due to rising interest rates and competition from other AMMs. 

# Proposal
This proposal is intended to whitelist the Kallisto’s Curve Finance APY chaser vault smart contracts and allow Kallisto to take part in the gauge voting. We propose the following:

  1. An immutable contract whitelist for Kallisto.finance automated LP position management contract. The contract will automatically convert CRV rewards to veCRV in order to secure additinal boost. While base APYs continue to drop, relative to alternative demand for capital, we propose that Kallisto access boosted CRV to continue to attract liquidity supply.

# Specification:
Curve DAO whitelisting the following Kallisto smart contract to allow locking of CRV, gauge voting, governance voting, as well as boosted LP rewards:
Kallisto Curve-Chaser Vault Contract deployed to Ethereum and viewed on Etherscan here:
https://etherscan.io/address/0x7620527fd09af964cdef936286091c636fc3b242
Keeping with Curve's best practice for immutable contracts, this contract will be replaced with a new one as we upgrade features for Paloma's blockchain control.

  

For:
A vote For signals community approval for Kallisto’s Curve Chaser Vault to be whitelisted for veCRV rewards to attract more Liquidity Providers to the Curve AMM. A vote will also be a signal to encourage Kallisto to continue to build new automated liquidity features valuable to Curve that will focus on both liquidity supply and demand.

Against:
A vote against signals community disapproval for Kallisto’s Curve Chaser Vault to be whitelisted for veCRV rewards.

Poll:
The poll will be submitted to the DAO, 24-hours after this post, and after comments and review from the community.

Again, special thanks to the thoughtful comments on our first proposal. We hope this updated proposal clarifies the Kallisto opportunity and value to the community.