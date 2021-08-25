# Possession is nine-tenths of NFT display: Weekly Update #42

https://www.geoweb.network/post/weekly-update-42

Displaying someone else&#39;s NFT is a hollow act. Being the owner (even if one of many) is what creates the impact. As the Geo Web evolves, we&#39;ll explore this interplay between digital display and ownership. Plus updates from last week on the Geo Web project (8/19/21 - 8/25/21).

## Possession is nine-tenths of NFT display

Back in February and March, we wrote about the [Top Shot craze](https://www.cnbc.com/2021/02/28/230-million-dollars-spent-on-nba-top-shot.html) and the Beeple&#39;s $69M [&quot;The First 5000 Days&quot; auction](https://onlineonly.christies.com/s/beeple-first-5000-days/beeple-b-1981-1/112924?ldp_breadcrumb=back) as the harbingers of mainstream adoption for NFTs.

For the last couple weeks, (digital art) NFTs have been on their latest massive bull run. [CryptoPunks](https://usa.visa.com/visa-everywhere/blog/bdp/2021/08/18/nfts-mark-a-1629328216374.html) and [other &quot;bluechip&quot; NFT projects](https://artblocks.io/) are reaching new levels of popularity, and the pace of new projects successfully launched is relentless.

A lot of the excitement is clearly based in speculation and financialization. The fractionalized [Feisty Doge NFT](https://fractional.art/vaults/0xDFDb7f72c1F195C5951a234e8DB9806EB0635346) briefly held an [implied market valuation of over $100M](https://www.forbes.com/sites/alpha-alarm/2021/08/23/this-dog-picture-briefly-became-the-worlds-most-valuable-nft-at-110m/).That... seems excessive.

If you simply dismiss this all out of hand, you&#39;ll miss the seeds of interesting developments. As [Fred Wilson of Union Square Ventures recently pointed out](https://avc.com/2021/08/splitting-ownership-and-display-consumption/), communal ownership and verifiable digital assets combine to create genuinely new cultural opportunities that we&#39;re just starting to explore.

The fact that digital objects can be perfectly, infinitely replicated is a double-edged sword. It&#39;s why most still &quot;don&#39;t get&quot; NFTs. But those that have internalized the distinct, but socially linked concepts of ownership of an NFT and display of an NFT can come together to bid millions on a _JPEG_ and derive potentially more utility from it than solo ownership.

Digital ownership and display will evolve and intertwine on the Geo Web too.

On the Geo Web, content linking (i.e. display) is managed with Ceramic Streams. During the initial claim of a parcel, a root Stream ID is associated to the parcel. Currently, the licensor is the owner of that Stream. Each time a parcel is transferred, a new Stream (owned by the new licensor) is created and associated.

That can change after we integrate Ceramic&#39;s [recently released NFT:DID](https://twitter.com/ceramicnetwork/status/1428371493407371265). With NFT:DID, the land parcel itself (an NFT) can own the linking document. The current parcel licensor always controls content liking via proxy. Instead of starting a new history with each transfer, a parcel&#39;s history is preserved.

But in either setup linking != ownership. It is tautological that ownership of an NFT is determined via its smart contract on its respective blockchain. Linking an NFT on the Geo Web doesn&#39;t change that.

We can however emphasize the importance of NFT ownership in Geo Web spatial browsers. If the licensor of a land parcel is also the owner of a linked NFT (as we would hope is the case), the browser could display it with a &quot;stamp of authenticity.&quot;

It would be considered garish and readily apparent if someone is passing off someone else&#39;s NFT as their own. Users could even decide to block display of inauthentic NFTs.

NFT owners could anchor their digital property to any number of parcels or even grant temporary authorization for 3rd party use.

As the use cases of NFTs expand from visual to functional (&quot;apps&quot; become NFTs) this setup could start to create a licensed vs pirated software sort of delineation.

Ownership and consumption (a broader definition of display) are foundational concepts for our culture and commerce. Even if these ideas seem basic at first glance, creating new primitives and drawing new lines between them will have a transformational impact. We haven&#39;t even explored the idea of NFTs (like digital land parcels) owning NFTs (like digital art) yet...

## Technical

- We have a couple known issues on the Cadastre: land transactions failing and automated pinning for some DIDs not initiating, so bear with us. Fixes are coming soon.
- Released new wallet connection options and a new map skin (improved performance) on the Cadastre last week.
- Migrated our [contracts to Hardhat](https://github.com/Geo-Web-Project/core-contracts/tree/hardhat) and are deploying contracts to the optimistic rollup L2 testents—Arbitrum Rinkeby &amp; Optimism Kovan.

## Community

- Check out Ceramic&#39;s [blog post about the different use cases for NFT:DID](https://blog.ceramic.network/ceramic-chainlink-vrf-the-toolset-for-building-more-dynamic-nfts/). Geo Web gets a shout out along with some other cool concepts around evolving NFTs.
- It looks like the [Gitcoin DAO](https://gitcoin.co/quadraticlands/mission) is going to [vote on an allocation](https://gov.gitcoin.co/t/proposal-issue-clr-fund-a-40k-gtc-grant/8240) of GTC to [clr.fund](https://clr.fund/). We&#39;ve been huge fans of both projects for a while, but the idea that Gitcoin would even consider funding a &quot;competitor&quot; shows what they&#39;re all about. They practice what they preach with public goods, and we&#39;re all beneficiaries.

## On Deck

- Adding a profile modal and transfer proceeds claim function to the Cadastre
- Experimenting with different map projections and multiselect land claims UX
- Integrating NFT:DID!
