# 2021 and Beyond: Weekly Update #56

https://www.geoweb.network/post/weekly-update-56

Looking back at the year that was and kicking off a new one on the Geo Web project.

## 2021 and Beyond

Before we move forward with what is sure to be an exciting year on the Geo Web (mainnet launch anyone?), let&#39;s do a quick recap of some of the highlights for our little project in 2021.

We started the year with a prototype Cadastre and smart contracts that &quot;worked,&quot; but no real publishing tools or content layer. Let&#39;s call it hack-a-thon++ readiness.

ETH mainnet fees weren&#39;t yet a total showstopper, but we were exploring and considering deployment on xDAI. We (naively) assumed that we&#39;d be launching our beta mainnet imminently. Move fast and break things to find product market fit, right?

The hype of L2 Summer (and our own growing understanding of rollup technology) convinced us that waiting to launch on an ETH L2 rollup was the way to go from a network scalability, composability, decentralization, and community perspective.

L2 Summer © 2021 has turned into #L222, so that gave us time to re-architect our core smart contracts… several times. Our contracts today are much more modular and try to account for the fact that [all the design decisions that we make today will be &quot;wrong&quot; someday](https://github.com/Geo-Web-Project/garden/blob/main/content/notes/Extending%20the%20Geo%20Web.md). The Geo Web&#39;s core architecture is night and day better prepared for a successful launch with a sound path to upgradability.

We were the first project to [officially launch on Ceramic Mainnet](https://blog.ceramic.network/geo-web-is-connecting-digital-content-to-the-physical-world-with-nfts-and-ceramic/) in June. We integrated native, free IPFS pinning and Filecoin archive of content from the Cadastre with the help of the [Filecoin Foundation](https://filecoinfoundation.medium.com/dev-grant-spotlight-geo-web-bdcb6ffd3d5d) and [Estuary](https://estuary.tech/). We built out our media gallery publishing tools and our first [spatial browser](https://geoweb.app/).

We accomplished a lot (more than what&#39;s listed here of course), but I&#39;d be lying if I didn&#39;t admit that I&#39;m a bit antsy that we have yet to launch our mainnet and go deep honing our product market fit.

Our community has grown by leaps and bounds. At the start of the year, the only people who knew the word metaverse were Neal Stephenson fans more or less. Zuck changed that. We raised ~$600 directly and $4,100 in matching funds during Gitcoin GR8 based with a ton of hustle and individually onboarding people to Gitcoin. That became $32,000 and $17,000 in GR12 from thousands of contributors all over the world. We&#39;ve used those funds to further our public goods mission transparently and, I hope, in a way that builds legitimacy ([my favorite post of the year](https://vitalik.ca/general/2021/03/23/legitimacy.html)). Here&#39;s an (unaudited) overview of the project financials:

![Geo Web Incoming Funds 2021](https://user-images.githubusercontent.com/15019279/149394103-3112bde5-a951-4f3a-bc0c-83fa17185245.png)

--People were very generous to us.

![Geo Web Use of Funds 2021](https://user-images.githubusercontent.com/15019279/149394121-0e099a29-553a-452f-b0dc-ae4b3b539b5e.png)

--Filecoin Grant payouts were made for work specified and assigned in the proposal. All other payouts were made through mechanisms open for community participation.

We&#39;ve attempted to embrace openness at every turn with our [code](https://github.com/Geo-Web-Project), [finances](https://geo-web-project.github.io/sourcecred-instance/#/accounts), [operations](https://forum.geoweb.network/) ([+](https://github.com/Geo-Web-Project/garden)), and [decision making](https://aragon.1hive.org/#/geoweb/). We still have a long way to go in making all that open information more discoverable, digestible, and actionable.

I&#39;m more excited about the Geo Web today than I ever have been, but the rubber needs to meet the road this year. There are ETH L2 roll-ups available today and more are on the way. We&#39;ll commit to one as our long-term, scalable home and get this grand experiment in partial common ownership property rights and augmented, shared reality started.

While launching our mainnet is clearly the tentpole of our 2022, I&#39;m looking forward to maturing our governance structures and ecosystem of contributors almost as much.

The project is admittedly pretty centralized right now with trust put into the founding team. The Geo Web only reaches its potential if it evolves into a democratically governed public good. That doesn&#39;t necessarily mean all on-chain governance and just 1 person or token = 1 vote. We want to innovate here just as much as in the tech stack. Luckily there are a lot of smart, principled people proposing and experimenting with novel structures.

Almost all of the work being done on the project is being done by a few people. Naturally the distribution of SourceCred (our main payout mechanism) has largely gone to those people. Power law distributions aren&#39;t that unusual especially at this stage of a project, but we do want to grow the number of people building (on) the Geo Web and create more permissionless opportunities for builders, creators, and community champions. We&#39;ll continue to build new, better, and more diverse on-ramps for contributors to be fairly compensated for their skills and effort. We&#39;re banking on our network fees being reinvested into our public goods ecosystem as a big reason the Geo Web can outcompete traditional private property rights systems. Time to start making that a reality.

To wrap things up, thank you to all that have supported us from the beginning or joined us more recently. 2021 was a great year, but the next one is going to be even better—not because it&#39;s destined to be, but because we&#39;re going to make it that way. Two of the most powerful forces in the universe are [optimism](https://www.warpnews.org/premium-content/kevin-kelly-the-case-for-optimism/) and [social coordination](https://www.youtube.com/watch?v=KpXPym_m_wA). Both start with mindsets controlled by each of us as individuals. We hope you&#39;ll join us in choosing to opt-in for a better future.

## Technical

- Cody finished up new specs that would combine both streaming network fee payments and an &quot;owner forgiving auction&quot; format (tldr: a current licensor could match bids with a penalty): [CollectorSuperApp](https://github.com/Geo-Web-Project/garden/blob/main/content/notes/Draft%20Proposal%20-%20CollectorSuperApp.md),[ETHxPurchaser](https://github.com/Geo-Web-Project/garden/blob/main/content/notes/Draft%20Proposal%20-%20ETHxPurchaser.md), &amp;[SimpleETHxClaimer](https://github.com/Geo-Web-Project/garden/blob/main/content/notes/Draft%20Proposal%20-%20SimpleETHxClaimer.md). This is a pretty big step for usability only practical on L2s. It also addresses one of the longer-term challenges to adoption for partial common ownership (uncertainty).

## Community

- The Geo Web joined the[Panvala League](https://panvala.com/) at the end of last year. It&#39;s an awesome community that brings together regen communities to create power/support in numbers. One of the ways they do that is by rewarding &quot;Proof of Community&quot; with payouts of their native token PAN. In practice that means the Geo Web can earn even more matching funds based on our[Gitcoin GR12 grant](https://gitcoin.co/grants/1403/geo-web). To maximize our match, we need our[community to stake PAN](https://panvala.com/staking/) (it&#39;s a gasless, lossless transaction on ETH mainnet). The first snapshot for Q1 2022 will be January 14th, so if you want to find another way to support our work, get some[PAN on Uniswap](https://app.uniswap.org/#/swap?outputCurrency=0xd56dac73a4d6766464b38ec6d91eb45ce7457c44&amp;use=V2) and stake it to the Geo Web!
- As a part of an effort with[RadicalXChange](https://www.radicalxchange.org/#), the Geo Web and several other builders interested in partial common ownership NFTs have come together to form an open working group. We&#39;re going to be meeting regularly in 2022 to support adoption, create educational material, and eventually a NFT standard for partial common ownershsip. Join us in the[RxC Discord #SALSA](https://discord.com/invite/qqrTPKVVse) channel and check out[our meeting notes](https://github.com/RadicalxChange/salsa-nft/wiki/Working-Group-Call-Notes) for more info.

## On Deck

- #L222… we&#39;re testing!
- Continue exploration of point-anchored AR content
- Unfortunately lots of admin, tax, and legal work
