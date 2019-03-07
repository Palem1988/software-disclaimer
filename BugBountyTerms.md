# MELON PROTOCOL BUG BOUNTY PROGRAM 2019

## **DESCRIPTION**

Welcome to the Melon Protocol Bug Bounty Program 2019. The purpose of this program is for developers around the world to test the security of both the smart contracts for the Melon Protocol v1.0 release as well as the front-end. In exchange, you can earn rewards in the form of DAI. Please have a look at the content below before starting your hunt. By submitting a bounty, you agree to the terms and conditions set forth herein.

The complete Bounty Reward Pool is equivalent to 247,989 DAI. The individual Bounty Reward will depend on the amount and quality of bounties submitted and accepted into the Bounty Program (more details below). If the total amount of DAI rewards in the Bounty Reward Pool have been distributed, this will signal the end of the current Bug Bounty Program unless another one is announced.

**Scope: Melon Protocol**

This Bug Bounty Program is intended to incentivise the testing of the security of the Melon protocol exclusively, ie. all the smart contracts part of the Melon system.

The smart contracts included in the scope of this Bug Bounty Program are as follows, in the src folder of the smart contracts repository [https://github.com/melonproject/protocol](https://github.com/melonproject/protocol).

Below are the smart contracts in scope of the bug bounty. Any valid and previously unknown security vulnerability found and disclosed to the Melon Council will be rewarded.

**Melon Engine** 

- [AmguConsumer.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/engine/AmguConsumer.sol)
- [Engine.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/engine/Engine.sol)

**Prices**

- [PriceSource.i.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/prices/PriceSource.i.sol)
- [KyberPricefeed.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/prices/KyberPriceFeed.sol)

**Version**

- [Version.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/version/Version.sol)
- [Registry.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/version/Registry.sol)

**Fund**

- [Factory.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/factory/Factory.sol)
- [FundFactory.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/factory/FundFactory.sol)

**Fund components**

- [Hub.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/hub/Hub.sol)
- [Spoke.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/hub/Spoke.sol)
- [Accounting.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/accounting/Accounting.sol)
- [FeeManager.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/fees/FeeManager.sol)
- [ManagementFee.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/fees/ManagementFee.sol)
- [PerformanceFee.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/fees/PerformanceFee.sol)
- [Participation.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/participation/Participation.sol)
- [Shares.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/shares/Shares.sol)
- [Trading.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/trading/Trading.sol)
- [Vault.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/vault/Vault.sol)
- [PolicyManager.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/policies/PolicyManager.sol)
- [Policy.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/policies/Policy.sol)
- **Compliance (participation policy)**
    - [UserWhitelist.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/policies/compliance/UserWhitelist.sol)

- **Risk management policies**
    - [AssetBlacklist.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/policies/risk-management/AssetBlacklist.sol)
    - [AssetWhitelist.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/policies/risk-management/AssetWhitelist.sol)
    - [MaxConcentration.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/policies/risk-management/MaxConcentration.sol)
    - [MaxPositions.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/policies/risk-management/MaxPositions.sol)
    - [PriceTolerance.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/fund/policies/risk-management/PriceTolerance.sol)

**Exchange adapters**

- [ExchangeAdapter.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/exchanges/ExchangeAdapter.sol)
- [EngineAdapter.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/exchanges/EngineAdapter.sol)
- [EthfinexAdapter.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/exchanges/EthfinexAdapter.sol)
- [KyberAdapter.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/exchanges/KyberAdapter.sol)
- [MatchingMarketAdapter.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/exchanges/MatchingMarketAdapter.sol)
- [ZeroExV2Adapter.sol](https://github.com/melonproject/protocol/blob/develop/src/contracts/exchanges/ZeroExV2Adapter.sol)

## **Important principles of the Melon Bug Bounty Program 2019**

- Issues reported are only valid if they relate to code that is used (or is intended to be used) in production, ie code deployed on the Ethereum main network or deployed on the test net with the intent to be deployed on the main network in the near future.
- Issues that have already been submitted by another user or are already known to the Melon Council are not eligible for bounty rewards.
- Public disclosure of a vulnerability makes it ineligible for a bounty. Instead they should be reported via encrypted email to [security@melonport.com](mailto:security@melonport.com) (PGP key fingerprint: 55DE CA3F D841 E26B 9230 18B8 9477 CD0F 85C7 9DD6) with the subject “PROTOCOL BUG BOUNTY REPORT”.  This email address will be updated during the course of the bug bounty program to a Melon Council address.
- The Melon Council, employees, contractors and all other people paid by Melon Council, directly or indirectly, are not eligible for rewards.
- The Melon Protocol Bug Bounty Program considers a number of variables in determining rewards, and is based on the exceptionally successful Ethereum bug bounty program. Determinations of eligibility, score and all terms related to an award are at the sole and final discretion of the Melon Council bug bounty team.
- The Melon Council holds no liability towards any user funds, tokens, virtual currencies, assets,time or other value lost which results in a loss with respect to this challenge.

## **Qualification for Rewards**

The value of rewards paid out will vary depending on severity and other factors. The severity is calculated according to the OWASP ([https://www.owasp.org/index.php/OWASP_Risk_Rating_Methodology](https://www.owasp.org/index.php/OWASP_Risk_Rating_Methodology)) risk rating model based on Impact and Likelihood:

![](https://d33wubrfki0l68.cloudfront.net/6b30b8f18010c7e4accd1a5a583ae2f0aa3f6e70/fa4bd/assets/images/rating.png)

Reward sizes are guided by the rules above, but are, in the end, determined at the sole discretion of the Melon Council bug bounty team.

- **Critical**: up to 10,000 DAI
- **High**: up to 5,000 DAI
- Low: up to 500 DAI

In addition to **Severity**, other variables are also considered when the Melon Council team decides the score, including (but not limited to):

- **Quality of description**: Higher rewards are paid for clear, well-written submissions. This makes it easier for us to quickly understand the scope and severity of the submitted issue.
- **Quality of reproducibility**: Please include test code, scripts and detailed instructions. The easier it is for us to reproduce and verify the vulnerability, the higher the reward. Please see the wiki and repos to learn more about our test suite:[https://github.com/melonproject/protocol](https://github.com/melonproject/protocol)
- **Quality of fix**: (if included): Higher rewards are paid for submissions with clear descriptions of how to fix the issue.

Vague, unclear or incomplete reports will be deemed invalid and will not result in a payout of any bug bounty amounts. In case the report is deemed valid by Melon Council and the vulnerability has not been executed, then Melon Council may decide to reward the first person reporting this vulnerability with an amount of up to 10,000 DAI, subject to providing a valid invoice.

## **Important Legal Information**

The bug bounty program is an experimental and discretionary rewards program for the active Melon community to encourage and reward those who are helping to improve the protocol. It is not a competition. You should be aware that we can cancel the program at any time, and awards are at the sole discretion of the Melon Council team. In addition, the Melon Council is not able to issue bounty payments to individuals who are on the US, Swiss, European (or other) sanctions lists or who are citizens of sanctioned/embargoed countries (eg. North Korea, Iran, etc). All recipients of any bounty tokens are responsible for all taxes under their respective jurisdictions and situations. All rewards are subject to applicable law. Your testing must not violate any law or compromise any data that is not yours. 

The Melon Council holds no liability towards any User funds, tokens, virtual currencies, assets or User time lost which results in a User loss with respect to this program. 

Any disputes arising out of or in connection with the Bounty Program shall be exclusively decided by the ordinary courts of the city of Zug, Switzerland and in accordance to Swiss law.

## **References**

- [Melon protocol documentation](http://www.docs.melonport.com/)
- [Protocol](https://github.com/melonproject/protocol)
