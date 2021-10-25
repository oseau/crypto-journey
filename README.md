# crypto-journey

Crypto world from a full-stack developer's prospective

## [Octopus Network](https://oct.network/)

The Octopus Network is designed to serve appchains by providing flexible and affordable leased security, powerful out-of-box interoperability, and many useful infrastructures.

To put it simply, Octopus appchains pay rent in their native tokens to lease security from Octopus token holders.

Octopus Relay 是一组运行在 Near 上的智能合约。 项目方通过提供自己的代币，向 Octopus Relay 租用安全性。

PoS 安全性来源于质押，跨链的质押无法保证安全性。例如 A 链的质押总额为 1，导入的 B 链资产总额>1，那么 A 链的 validator 存在作恶的可能。Octopus 选择[Leased Proof-of-Stake](https://docs.oct.network/general/octopus-staking.html)方案，统一质押 OCT 使得作恶无利可图。项目方可以选择提供多少自己的 token 奖励给 validator，以达到满意的安全性。validator 自行选择为这个项目质押多少 OCT。在这种模型下，validator 的角色更像是项目投资者，而非简单的 IT 承包商。

- [discord](https://discord.gg/6GTJBkZA9Q) 不活跃，提问 3 天没有人回应。[link](https://discord.com/channels/820671513594167336/820671513594167339/901079934741663744)
- [Test Net](https://github.com/octopus-network/octopus-pallets/tree/main/appchain) 官网的地址指向的原 repo 已经 archived
- [Substrate](https://www.parity.io/technologies/substrate/)
  - [tutorial](https://docs.substrate.io/tutorials/v3/create-your-first-substrate-chain/)
- [INTER‑BLOCKCHAIN COMMUNICATION PROTOCOL](https://ibcprotocol.org/)
- [Near](https://near.org/)
- [Rainbow Bridge](https://near.org/blog/the-rainbow-bridge-is-live/)
- [Polkadot](https://polkadot.network/)
- [Kusama](https://kusama.network/)
- [Cosmos](https://cosmos.network/)
- [Starport](https://github.com/tendermint/starport)
- [Polygon](https://polygon.technology/)
- [Skale](https://skale.network/)
- [arweave](https://www.arweave.org/) forkable by archiving the appchain block history to Arweave
- [governance token valuation](https://github.com/coinfund/governance-model)

## github stats

```bash
curl -H "Accept: application/vnd.github.v3+json" "https://api.github.com/orgs/octopus-network/repos?type=sources&sort=updated" | jq --compact-output '.[] | {name: .name, updated_at: .updated_at}'
```

```json
{"name":"wrapped-appchain-token","updated_at":"2021-10-25T17:11:12Z"}
{"name":"octopus-webapp","updated_at":"2021-10-25T16:36:51Z"}
{"name":"octopus-appchain-anchor","updated_at":"2021-10-25T16:13:31Z"}
{"name":"appchain-native-token","updated_at":"2021-10-25T06:41:07Z"}
{"name":"octopus-bridge","updated_at":"2021-10-25T04:09:37Z"}
{"name":"octopus-relay-contract","updated_at":"2021-10-24T15:36:58Z"}
{"name":"octopus-relay-webapp","updated_at":"2021-10-24T15:32:29Z"}
{"name":"barnacle","updated_at":"2021-10-24T15:29:22Z"}
{"name":"octopus-pallets","updated_at":"2021-10-24T14:52:51Z"}
{"name":"octopus-relayer","updated_at":"2021-10-23T17:36:50Z"}
{"name":"mock-grandpa","updated_at":"2021-10-23T11:55:46Z"}
{"name":"planets","updated_at":"2021-10-23T09:23:43Z"}
{"name":"octopus-appchain-registry","updated_at":"2021-10-23T08:42:48Z"}
{"name":"substrate-ibc","updated_at":"2021-10-21T07:53:50Z"}
{"name":"papers","updated_at":"2021-10-21T04:02:53Z"}
{"name":"octopus-docs","updated_at":"2021-10-20T04:11:23Z"}
{"name":"octopus-gateway","updated_at":"2021-10-19T08:36:24Z"}
{"name":"issues","updated_at":"2021-10-14T08:38:45Z"}
{"name":"oct-token-eth","updated_at":"2021-10-14T01:48:02Z"}
{"name":"hermes-test","updated_at":"2021-10-12T06:48:21Z"}
{"name":"oct-faucet","updated_at":"2021-10-11T15:45:34Z"}
{"name":"appchain-launch","updated_at":"2021-10-10T08:45:33Z"}
{"name":"pallet-octopus-appchain","updated_at":"2021-10-09T08:30:51Z"}
{"name":"pallet-octopus-lpos","updated_at":"2021-09-29T17:06:20Z"}
{"name":"octoup","updated_at":"2021-09-28T09:35:46Z"}
{"name":"oct-token-vesting-app","updated_at":"2021-09-21T01:51:50Z"}
{"name":"ibc-demo","updated_at":"2021-09-20T02:00:44Z"}
{"name":"solana-flux-aggregator","updated_at":"2021-09-18T12:37:11Z"}
{"name":"octopus-explorer","updated_at":"2021-09-03T21:35:14Z"}
{"name":"relay-rpc","updated_at":"2021-09-03T06:35:19Z"}
```
