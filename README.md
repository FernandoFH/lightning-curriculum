# Lightning Curriculum

| Subjects                        | Topics  | Sub-topics    | Sources |
|---------------------------------|---------|---------------|---------|
What is Lightning?|Introduction||[The Bitcoin Lightning Network: Scalable Off-Chain Instant Payments](http://lightning.network/lightning-network-paper.pdf), [What is the Lightning Network and how can it help Bitcoin scale?](https://coincenter.org/entry/what-is-the-lightning-network), [The Lightning Network Evolving Bitcoin into a layered system](https://medium.com/scalar-capital/the-lightning-network-cf836329626b), [Understanding the Lightning Network, Part 1: Building a Bidirectional Bitcoin Payment Channel](https://bitcoinmagazine.com/articles/understanding-the-lightning-network-part-building-a-bidirectional-payment-channel-1464710791/), [Understanding the Lightning Network, Part 2: Creating the Network](https://bitcoinmagazine.com/articles/understanding-the-lightning-network-part-creating-the-network-1465326903/), [Understanding the Lightning Network, Part 3: Completing the Puzzle and Closing the Channel](https://bitcoinmagazine.com/articles/understanding-the-lightning-network-part-completing-the-puzzle-and-closing-the-channel-1466178980/), [Reaching The Ground With Lightning](https://github.com/ElementsProject/lightning/blob/master/doc/deployable-lightning.pdf), [Scaling Bitcoin to Billions of Transactions Per Day, 2015](https://www.youtube.com/watch?v=8zVzw912wPo), [Lightning Network Deep Dive with Laolu "Roasbeef" Osuntokun](https://www.youtube.com/watch?v=b_szGaaPPFk), [The #Bitcoin #Lightning Spec](https://medium.com/@rusty_lightning/the-bitcoin-lightning-spec-part-1-8-a7720fb1b4da), [Lightning Network Glossary](https://en.bitcoin.it/wiki/Lightning_Network) |
| |Lightning Layers - an overview||[Alex Bosworth - The Lightning Protocol, an Application Design Perspective](https://www.youtube.com/watch?v=1R5DNUcCYRg) |
| |History of LN|| [Christian Decker - History of the Lightning Network](https://www.youtube.com/watch?v=HauP9F16mUM), [The Future of Bitcoin: What Lightning Could Look Like](https://bitcoinmagazine.com/articles/future-bitcoin-what-lightning-could-look/), [The History of Lightning: From Brainstorm to Beta](https://bitcoinmagazine.com/articles/history-lightning-brainstorm-beta/) |
Lightning ≈ Bitcoin|||[Christian Decker - Lightning ≈ Bitcoin](https://www.youtube.com/watch?v=8lMLo-7yF5k) |
||Revisting tx malleability||[SF Bitcoin Devs Seminar: Transaction Malleability: Threats and Solutions](https://www.youtube.com/watch?v=jyDE-aFqJTs) |
|Transfer|Payment channel (general concept)||[Payment Channel](https://wiki.ion.radar.tech/tech/lightning/payment-channel) |
|||Public channel| |[Do the channel balances get publicly announced in real-time on Lightning Network?](https://bitcoin.stackexchange.com/questions/80130/in-lightning-network-is-the-balance-publicly-anounced-in-realtime), [The open_channel Message](https://github.com/lightningnetwork/lightning-rfc/blob/master/02-peer-protocol.md#the-open_channel-message)|
|||Private channel|[Exploring Lightning Network Routing](https://blog.lightning.engineering/posts/2018/05/30/routing.html) |
|||Channel balance (local/remote)|||
|||Exhausted channels||
|||Channel reserve|[Rationale](https://github.com/lightningnetwork/lightning-rfc/blob/master/02-peer-protocol.md#rationale) |
||Transactions||[BOLT #3: Bitcoin Transaction and Script Formats](https://github.com/lightningnetwork/lightning-rfc/blob/master/03-transactions.md) |
|||Funding Transaction| [Funding Transactions as a Generalized Design Pattern for Offchain Protocols](https://zmnscpxj.github.io/offchain/generalized.html), [Funding Transaction Output](https://github.com/lightningnetwork/lightning-rfc/blob/master/03-transactions.md#funding-transaction-output), [The funding_created Message (https://github.com/lightningnetwork/lightning-rfc/blob/master/02-peer-protocol.md#the-funding_created-message)|
|||Commitment Transaction| [Commitment transactions](https://en.wikipedia.org/wiki/Lightning_Network#Commitment_transactions), [Commitment Transaction](https://github.com/lightningnetwork/lightning-rfc/blob/master/03-transactions.md#commitment-transaction)  |
|||Closing Transaction| [Closing a Channel in Lighting Network](https://bitcoin.stackexchange.com/questions/80394/closing-a-channel-in-lightning-network), [Closing Transaction](https://github.com/lightningnetwork/lightning-rfc/blob/master/03-transactions.md#closing-transaction) |
|||Penalty Transaction| [Lightning Network ‘Penalty Scenario’ Works in Old State Channel Incident](https://bitsonline.com/lightning-network-hackers-busted/), [Revoked Transaction Close Handling](https://github.com/lightningnetwork/lightning-rfc/blob/master/05-onchain.md#revoked-transaction-close-handling)  |
|||Mutual Close| [Distinguishing mutual and unilateral channel closing in the Bitcoin blockchain](https://medium.com/coinmonks/distinguishing-mutual-and-unilateral-channel-closing-in-the-bitcoin-blockchain-ec2e0e7d71f4), [Mutual Close Handling](https://github.com/lightningnetwork/lightning-rfc/blob/master/05-onchain.md#mutual-close-handling)  |
|||Unilateral Close|[Unilateral Close Handling: Local Commitment Transaction](https://github.com/lightningnetwork/lightning-rfc/blob/master/05-onchain.md#unilateral-close-handling-local)|||commitment-transaction |
|||Fee negotiation|[BOLT #2: Peer Protocol for Channel Management](https://github.com/lightningnetwork/lightning-rfc/blob/master/02-peer-protocol.md#closing-negotiation)||closing_signed |
||HTLC|| [What Are Hashed Timelock Contracts (HTLCs)? Application In Lightning Network & Payment Channels](https://hackernoon.com/what-are-hashed-timelock-contracts-htlcs-application-in-lightning-network-payment-channels-14437eeb9345),[Lightning Networks Part II: Hashed Timelock Contracts (HTLCs)](https://rusty.ozlabs.org/?p=462) |
|||Hashlock|[[WIP] HTLC implementation in the wallet #7601](https://github.com/bitcoin/bitcoin/pull/7601) |
|||Timelocks| [Bitcoin’s Time Locks](https://medium.com/summa-technology/bitcoins-time-locks-27e0c362d7a1), [Timelock](https://en.bitcoin.it/wiki/Timelock),[Bitcoin Timelocks in a nutshell](https://medium.com/@RobinHung/bitcoin-timelocks-in-a-nutshell-4c95aafc7a59)  |
|||Revocation Key|[Lightning Networks Part I: Revocable Transactions](https://rusty.ozlabs.org/?p=450) |
|||Relative Locktime/CLTV|[bips/bip-0065.mediawiki](https://github.com/bitcoin/bips/blob/master/bip-0065.mediawiki) |
|||Hash Pre-image| [What is a hash pre-image as it is used for the breach remedy?](https://bitcoin.stackexchange.com/questions/48053/what-is-a-hash-pre-image-as-it-is-used-for-the-breach-remedy),[Offered HTLC Outputs](https://github.com/lightningnetwork/lightning-rfc/blob/master/03-transactions.md#offered-htlc-outputs)  |
|||payment basepoint/revocation basepoint|[Key Derivation](https://github.com/lightningnetwork/lightning-rfc/blob/master/03-transactions.md#key-derivation) |
|||Per-commit secret/Commitment number|[Key Derivation](https://github.com/lightningnetwork/lightning-rfc/blob/master/03-transactions.md#key-derivation) |
|||HTLC fulfillment/failure|[Removing an HTLC: update_fulfill_htlc, update_fail_htlc, and update_fail_malformed_htlc](https://github.com/lightningnetwork/lightning-rfc/blob/master/02-peer-protocol.md#removing-an-htlc-update_fulfill_htlc-update_fail_htlc-and-update_fail_malformed_htlc) |
||Payment|| |
|||Invoice| |
|||Payment Request| |
|Update||Bolt11 encoding|[BOLT #11: Invoice Protocol for Lightning Payments](https://github.com/lightningnetwork/lightning-rfc/blob/master/11-payment-encoding.md) |
|||Gossip Protocol||[BOLT #7: P2P Node and Channel Discovery](https://github.com/lightningnetwork/lightning-rfc/blob/master/07-routing-gossip.md) |
|||LN-Penalty|| |
|||Eltoo payment channels||[eltoo: A Simple Layer2 Protocol for Bitcoin](https://blockstream.com/eltoo.pdf) |
|||querying for information| |
|Multihop||| |
Sphinx||| [Sphinx Packet](https://wiki.ion.radar.tech/tech/lightning/sphinx-packet), [Using Sphinx to Improve Onion Routing Circuit Construction (short paper)⋆](https://www.cypherpunks.ca/~iang/pubs/SphinxOR.pdf), [Sphinx: A Compact and Provably Secure Mix Format](http://diyhpl.us/~bryan/papers2/bitcoin/Sphinx:%20A%20compact%20and%20provably%20secure%20mix%20format.pdf), [Security Analysis of the Lightning Network](https://cyber.stanford.edu/sites/g/files/sbiybj9936/f/olaoluwaosuntokun.pdf)  |
|Onion Routing|||[Onion Routing with HTLCs on the Lightning Network explained! - Beginner / Experts](https://www.youtube.com/watch?v=toarjBSPFqI) |
||Public vs. Private channel|| [Do the channel balances get publicly announced in real-time on Lightning Network?](https://bitcoin.stackexchange.com/questions/80130/in-lightning-network-is-the-balance-publicly-anounced-in-realtime),[Exploring Lightning Network Routing](https://blog.lightning.engineering/posts/2018/05/30/routing.html) |
||Channel announcements||[BOLT #2: Peer Protocol for Channel Management](https://github.com/lightningnetwork/lightning-rfc/blob/master/02-peer-protocol.md#the-open_channel_message) |
||Routing fees||[The Lightning Network (Part 2) – Routing Fee Economics](https://blog.bitmex.com/the-lightning-network-part-2-routing-fee-economics/) |
|||Expiry delta||[cltv_expiry_delta Selection](https://github.com/lightningnetwork/lightning-rfc/blob/master/02-peer-protocol.md#cltv_expiry_delta-selection) |
||Route hints||[Exploring Lightning Network Routing](https://blog.lightning.engineering/posts/2018/05/30/routing.html) |
|Base|Framing and feature negotiation|| |
|Transport ||| |
||Noise Protocol Framework|| [The Noise Protocol Framework](http://www.noiseprotocol.org/noise.html#introduction) [The Noise Protocol Framework](https://www.youtube.com/watch?v=ceGTgqypwnQ)  |
||Noise XK|| [Handshake patterns](http://noiseprotocol.org/noise.html#handshake-patterns) [Noise Explorer](https://noiseexplorer.com/patterns/XK/)  |
Atomic Swaps||| [What are Atomic Swaps? A Beginner’s Guide](https://coincentral.com/what-are-atomic-swaps-a-beginners-guide/),[Atomic Swaps: How the Lightning Network Extends to Altcoins](https://bitcoinmagazine.com/articles/atomic-swaps-how-the-lightning-network-extends-to-altcoins-1484157052/), [Atomic Swaps](https://bitcointechtalk.com/atomic-swaps-d6ca26b680fe) [Trey Griffith - Atomic Swaps on the Lightning Network](https://www.youtube.com/watch?v=iuNopQm1Adk) |
||Submarine swaps vs. reverse swaps|| [Onboarding the Masses: Submarine Swaps](https://medium.com/chainrift-research/onboarding-the-masses-submarine-swaps-b615b6d80093),[Alex Bosworth: Submarine Swaps on the Lightning Network](https://www.youtube.com/watch?time_continue=1&v=ASkyu0w_8Q8)  |
||Loops||[Announcing Lightning Loop Alpha: An Easier Way to Receive on Lightning](https://blog.lightning.engineering/posts/2019/03/20/loop.html),[Loop Out In-depth](https://blog.lightning.engineering/technical/posts/2019/04/15/loop-out-in-depth.html) |
Current Limitations||| [Lightning Network 2.0](https://blog.theabacus.io/lightning-network-2-0-b878b9bb356e), [Major Limitations of the Lightning Network](http://diyhpl.us/wiki/transcripts/boltathon/2019-04-06-alex-bosworth-major-limitations/)  |
BOLTs 1.1 and the future||| [Lightning Specification 1.1 Proposal States](https://github.com/lightningnetwork/lightning-rfc/wiki/Lightning-Specification-1.1-Proposal-States) ||[Lightning User Experience: A Day in the Life of Carol](https://blog.lightning.engineering/posts/2018/05/02/lightning-ux.html)  |
||Splicing|| [[Lightning-dev] Channel top-up](https://lists.linuxfoundation.org/pipermail/lightning-dev/2017-May/000692.html), [[Lightning-dev] Splicing Proposal: Feedback please!](https://lists.linuxfoundation.org/pipermail/lightning-dev/2018-October/001434.html)  |
||Dual Funded channels||[[Lightning-dev] Proposal for Advertising Channel Liquidity](https://lists.linuxfoundation.org/pipermail/lightning-dev/2018-November/001532.html)|
||AMP|| [AMP: Atomic Multi-Path Payments over Lightning](https://lists.linuxfoundation.org/pipermail/lightning-dev/2018-February/000993.html),[Base AMP](https://lists.linuxfoundation.org/pipermail/lightning-dev/2018-November/001577.html)  |
||Rendezvous routing||[Rendez vous mechanism on top of Sphinx](https://github.com/lightningnetwork/lightning-rfc/wiki/Rendez-vous-mechanism-on-top-of-Sphinx) |
|The Future||| |
||Multiparty channels / channel factories||[What are Channel Factories and how do they work?](https://bitcoin.stackexchange.com/questions/67158/what-are-channel-factories-and-how-do-they-work), [Onboarding the Masses: Channel Factories](https://medium.com/chainrift-research/onboarding-the-masses-||channel-factories-6e5c26b07cf1)  |
||Decorelation||[Payment Decorrelation](https://github.com/lightningnetwork/lightning-rfc/wiki/Brainstorming#payment-decorrelation) |
||Streaming Payments||[BOLT 11, real time micro payments, and route redundancy](https://lists.linuxfoundation.org/pipermail/lightning-dev/2017-September/000757.html) |
||Refunds|| |
||Fast Failure|| |
||Scriptless Scripts with ECDSA||[Scriptless Scripts with ECDSA](https://lists.linuxfoundation.org/pipermail/lightning-dev/2018-May/001244.html) |
||Just in time routing||[Just in Time Routing (JIT-Routing) and a channel rebalancing heuristic as an add on for improved routing success in BOLT 1.0](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-March/001891.html) |
| Privacy considerations|||[How the Lightning Network Layers Privacy on Top of Bitcoin](https://bitcoinmagazine.com/articles/how-the-lightning-network-layers-privacy-on-top-of-bitcoin-1482183775/) |
||Gossip protocol and privacy|| |
||watchtowers|| [Incentivizing payment channel watchtower](https://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/incentivizing-payment-channel-watchtowers/),[Trustless Watchtowers](https://lists.linuxfoundation.org/pipermail/lightning-dev/2018-November/001562.html), [Architecture of LND Watchtowers](http://diyhpl.us/wiki/transcripts/boltathon/2019-04-06-conner-fromknecht-watchtowers/) [Scaling Bitcoin 2018 "Kaizen" Day 2 Part 2](https://www.youtube.com/watch?time_continue=3880&v=nwSuctrzV7Y)  |
||Channel probing attack for channel balance|| |
||decorrelation of lightning payments||[Decorrelation of Lightning Payments](https://medium.com/@rusty_lightning/decorrelation-of-lightning-payments-7b6579db96b0) |
||SNARKs||[Better privacy with SNARKs](https://lists.linuxfoundation.org/pipermail/lightning-dev/2015-November/000309.html) |
||Security/Attack Vectors||| |
||Denial of Service attacks|| [State of the Crypto: Lightning Network DDoS’d, Ethereum Inflation Talk](https://bitsonline.com/state-of-crypto/), [Payment channel congestion via spam-attack #182](https://github.com/lightningnetwork/lightning-rfc/issues/182)  |
||Desired topology of a high functional network ||| |
|||Autopilot|| [Improve the autopilot of bitcoin’s lightning network (Summary of the bar camp Session at the 2nd lightninghackday in Berlin)](https://www.rene-pickhardt.de/index.html%3Fp=2085.html), [first version of lib-autopilot.py #1888](https://github.com/ElementsProject/lightning/pull/1888)  |
|||Channel management||[Rebalancing in the lightning network: Analysis and implications](https://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/rebalancing-lightning/) |
|||Cyclic Superhubs||[Cyclic Superhubs as Solution Towards Reasonable Lightning Network Topology](https://zmnscpxj.github.io/offchain/cyclicsuperhubs.html) |
|Considerations||| |
||Neutrino|| [Exploring Neutrino](https://vimeo.com/316626387), [Neutrino: The Lighter Side of Lightning](https://blog.lightning.engineering/posts/2018/10/17/neutrino.html )|
||Pitfalls of concurrent requests|| |
||RGB protocol|| |
||broadcasting channel updates||[What is the status of the Lightning Network?](https://www.reddit.com/r/Bitcoin/comments/714x2k/what_is_the_status_of_the_lightning_network/dn8v3dg/) |
|Implementations||| |
||LND||[Lightning Network Daemon](https://github.com/lightningnetwork/lnd) |
||ptarmigan||[Lightning Network (BOLT)](https://github.com/nayutaco/ptarmigan) |
||electrum||[Comparing changes](https://github.com/spesmilo/electrum/compare/lightning) |
||rust||[Rust-Lightning, not Rusty's Lightning](https://github.com/rust-bitcoin/rust-lightning) |
||c-lightning||[c-lightning — a Lightning Network implementation in C](https://github.com/ElementsProject/lightning) |
||Eclair||[A scala implementation of the Lightning Network.](https://github.com/ACINQ/eclair) |
Setting up a node||| [Bitcoin Lightning Network #1: Can I compile and run a node?](https://medium.com/andreas-tries-blockchain/bitcoin-lightning-network-1-can-i-compile-and-run-a-node-cd3138c68c15), [Beginner’s Guide to ️Lightning️ on a Raspberry Pi](https://github.com/Stadicus/guides/blob/master/raspibolt/README.md), [My Lightning Node setup with c-lightning](https://medium.com/coinmonks/my-lightning-node-setup-with-c-lightning-45bbb9993c0), [Fastest and cheapest way to get your own Lightning Node running - on a RaspberryPi with a nice LCD](https://github.com/rootzoll/raspiblitz) |
