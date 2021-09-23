---
layout: content
---

# Bitcoin Privacy

### Issues

Bitcoin Core:

- [ ] Improve change amount privacy [#6569](https://github.com/bitcoin/bitcoin/issues/6569)
- [ ] Implement PayJoin / Pay-to-EndPoint [#19148](https://github.com/bitcoin/bitcoin/issues/19148)
- [ ] RBF with custom change address [#20795](https://github.com/bitcoin/bitcoin/issues/20795)
- [ ] Broadcast a transaction to specific nodes [#21876](https://github.com/bitcoin/bitcoin/issues/21876)
- [ ] Wallet fingerprinting [#22018](https://github.com/bitcoin/bitcoin/issues/22018)
- [ ] wallet: use database for locked coins [#22368](https://github.com/bitcoin/bitcoin/issues/22368)
- [ ] Sub wallet for dirty coins [#22424](https://github.com/bitcoin/bitcoin/issues/22424)

Bisq:

- [ ] Feature for renewing the onion address [#1056](https://github.com/bisq-network/bisq/issues/1056)
- [ ] bisq mobile notifications should NOT rely on "google play services" [#2441](https://github.com/bisq-network/bisq/issues/2441)

LND:

- [ ] Better privacy for sender when making LN payments [#2530](https://github.com/lightningnetwork/lnd/issues/2530)
- [ ] routing: add shadow route randomization, payment path randomization, and fee randomization [#1222](https://github.com/lightningnetwork/lnd/issues/1222)




### Pull Requests

Bitcoin Core:

- [ ] p2p: Introduce node rebroadcast module [#21061](https://github.com/bitcoin/bitcoin/pull/21061)
- [x] wallet: Decide which coin selection solution to use based on waste metric [#22009](https://github.com/bitcoin/bitcoin/pull/22009)
- [ ] net: respect -onlynet= when making outbound connections [#22834](https://github.com/bitcoin/bitcoin/pull/22834)
- [ ] Allow UTXO locks to be written to wallet DB [#23065](https://github.com/bitcoin/bitcoin/pull/23065/)

Bisq:

- [x] Privacy improvements for manual payout [#4899](https://github.com/bisq-network/bisq/pull/4899)
- [x] Do not use tx broadcast to mempool nodes if a local btc nodes is used [#4958](https://github.com/bisq-network/bisq/pull/4958)

LND:

- [x] multi: add onion services support [#1159](https://github.com/lightningnetwork/lnd/pull/1159)
