# Metaverse Land &amp; Radical Property Rights: Weekly Update #63

https://www.geoweb.network/post/weekly-update-63

Our belief in the power of partial common ownership property rights isn&#39;t widely shared yet, but it will be. Plus updates from the Geo Web project in the last week (3/10/22 - 3/16/22).

## Metaverse Land &amp; Radical Property Rights

&quot;Still think the metaverse land model at play is probably wrong (but nobody knows yet, we are still experimenting)&quot; - [@punk6529](https://twitter.com/punk6529/status/1503985205157273602?s=20&amp;t=HmprNJq3ZFDD1b2HACThjA)

Punk6529 is a big proponent of [building the open metaverse](https://twitter.com/punk6529/status/1448399827054833668?s=20&amp;t=HmprNJq3ZFDD1b2HACThjA) and has amassed a significant following on Twitter by sharing his insight (and hopes) for this future.

We don&#39;t have everything figured out on the Geo Web. We&#39;re definitely still experimenting (only in our testnet!), but seeing this tweet and the replies makes me feel like I&#39;m in on the biggest secret in the world:

[Partial common ownership](https://docs.geoweb.network/concepts/partial-common-ownership) is a key to an open metaverse (and much more).

In a perfect world, metaverse land could be free and infinite. Technically, it is. But practically speaking, humans have finite time, brain power, and resources. If the metaverse is built for people and not machines, then choke points/scarcity will emerge somewhere in the stack regardless of if we want them to (e.g. Google amassed its power by inserting itself between the user and infinite web pages that needed contextualization and a better discovery mechanism).

Rather than having a choke point surreptitiously imposed upon us under someone else&#39;s agenda (like a for-profit, centralized company), the open metaverse should be designed to acknowledge inherent limits and make more mindful tradeoffs up front.

Partial common ownership [isn&#39;t the only answer](https://matthewscottjones.com/virtual-lands-in-the-metaverse/), but I do believe it&#39;s the best one.

PCO may be a radical economic concept currently, but it fits better with our ingrained understanding of how space works than other physics-bending solutions that are technically possible in digital worlds. I think that matters.

Beyond that, partial common ownership is a transparent, market-based solution to the inevitable scarcity and necessary human coordination. It is economically efficient and morally fair. It doesn&#39;t bestow permanent monopoly power to early adopters nor leave a massive vacuum for someone to step in later.

If governed by a non-profit-seeking, decentralized and open collective, the tradeoffs imposed can end up generating more value for all through public goods funding than infinite land could.

It can be the seed of a global Schelling point for human coordination and cooperation.

We still have a lot to learn and experience with partial common ownership systems, but I believe sooner rather than later many more people are going to agree with our partial common ownership hypothesis.

## Technical

- Our fair launch (Dutch auction) contract is complete ([https://github.com/Geo-Web-Project/core-contracts/pull/42](https://github.com/Geo-Web-Project/core-contracts/pull/42))1 We don&#39;t know what demand for Geo Web land at launch will be, but we have to come prepared. If we&#39;ve created something of value, then land in high trafficked areas might turn into a priority gas auction (PGA) that causes negative externalities and selects &quot;winners&quot; based on misaligned incentives. [Check out the specs](https://github.com/Geo-Web-Project/garden/blob/main/content/notes/Fair%20Launch%20Auction%20Requirements.md) for more details and our rationale.
- At the Partial Common Working Group&#39;s meetup at ETHDenver, we had a [debate about the ERC-721 transfer functionality and PCO](https://timdaub.github.io/2022/02/19/non-skeuomorphic-harberger-properties-erc721-nfts/). Under a deposit based system, I advocated for maintaining the functionality (I didn&#39;t see how &quot;free&quot; transfers between wallets could undermine the market). With streaming payments things are a bit different: streams are indefinite and can&#39;t be started without permission (duh). Transferring a NFT from one address to another would leave a mismatch between the license and stream owner without additional actions taken by the receiver. It&#39;s messy, so we decided to [turn off ERC721 transfers in our new streaming architecture](https://github.com/Geo-Web-Project/core-contracts/pull/50) (our &quot;admin&quot; contract handles transfers according to PCO rules). &quot;Layer 2&quot; solutions like flash loans would still allow individuals to move assets between their addresses without needing to have capital to pay the full For Sale Price.
- We&#39;re experimenting with more AR/VR use cases ([https://github.com/Geo-Web-Project/geoweb-experiments/pull/9](https://github.com/Geo-Web-Project/geoweb-experiments/pull/9)). This latest one is a [web browser seen in VR](https://bafybeiel7yk7oohdkh57qlfywbhja4sj4dmr4242llxjiyvqxldylks534.on.fleek.co/05-3d-webview/).

## Community

- [The Geo Web Gitcoin GR13 grant is going strong](https://gitcoin.co/grants/1403/geo-web)! We still have a week to try to match last quarter&#39;s success ($50k+... we can dream, right?). Thank you for all of your support! If you&#39;re feeling extra committed to funding public goods, you can also support the [PCO Working Group grant](https://gitcoin.co/grants/4976/pcot-working-group) that&#39;s still searching for traction (which also means more matching upside).
- [FOAM](https://foam.space/) is an awesome project that has been innovating in web3 for several years. We had a chance to chat with some of the team at ETHDenver and are super excited about what they&#39;re doing with verifiable location claims. Check out [their latest announcement](https://mirror.xyz/foamspace.eth/Awq0ItP4fxvg7_HAZA3gNQnNgoE_7Ogj_4n2EkDed-I): bye, bye GPS (soon-ish?).

## On Deck

- Raid Guild Cohort Season IV is restarting next week, and we&#39;re sponsoring several [Geo Web bounties](https://docs.google.com/document/d/1L_5-kAAjZN3b-hatcycgcjqRPUtuyMF8vzi5DkQ9jTw/edit). Join the [RG Discord](https://discord.com/invite/rGFpfQf) and dig around if you&#39;re interested.
- Complete wireframes and move to final design of our streaming payments &amp; new auction UX for the Cadastre
- Beginning work on the [Reclaimer](https://github.com/Geo-Web-Project/core-contracts/issues/51) to round out all of the land market functions in our streaming payments architecture
