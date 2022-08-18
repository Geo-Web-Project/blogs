# Public Goods are Good: Weekly Update #84

https://www.geoweb.network/post/weekly-update-84

Crypto is the most powerful and energized space for creating and funding public goods. Therefore crypto is a good thing. Plus updates from the Geo Web project (8/11/22 - 8/17/22).

## Public Goods are Good

_This is the essay form of a talk that I gave yesterday at a local educational event for crypto/web3 under the theme "Why Crypto?". H/T to_ [_Gitcoin_](https://gitcoin.co/) _for memeing the title of this talk into existence. They may not have technically come up with the phrase, but they're the ones that brainwormed it for me._

For a growing group of people, including me, crypto represents one of the most powerful tools humanity has ever had to create abundance.

In _abundance_, I mean creating enough economic value for everyone to have the opportunity to thrive. (Life isn't all about things that can be counted in GDP, but crypto also has applications within community, art, and the "softer" things that shouldn't be discounted.)

A pairing of crypto and abundance might come as a surprise to some. Isn't crypto all about creating artificial scarcity?

What this common criticism misses is that some things are inherently scarce (human attention will be finite until "we" are no longer human) and some things derive meaning from their relative scarcity (adding a 0 to every dollar denomination overnight doesn't create x10 wealth).

To me, crypto is about creating fair, credible systems that leverage strategic scarcity to create more value and spread it widely. The most potent place this can be directed is toward creating and funding public goods.

[Public goods](https://en.wikipedia.org/wiki/Public_good_(economics)), for those that haven't been brushed up on your Econ 101 in a while, are a categorization of commodity/service/information that are non-excludable (someone can't be prevented from using it) and non-rivalrous (one person's use of the good doesn't impact the ability of another to enjoy it as well). Knowledge is the ultimate example.

Most goods exist on the spectrums of excludability and rivalry, but the closer something is to a public good, the more it is an economic miracle. Public goods are never-ending wells of positive value that anyone can tap. They just don't have a business model to reward those that create them.

This is why governments are traditionally funders, creators, and administrators of this type of good. Governments are supposed to represent the collective interest of their citizens and overcome [this market failure](https://en.wikipedia.org/wiki/Free-rider_problem). In theory, we want this because public goods are good! In practice, there's much left to be desired. Regardless, we should always be pushing for progress.

I'm not saying that our existing governments are going to disappear overnight because crypto makes them irrelevant (someday…?). But, there are four attributes of crypto that make it the most promising space that we have for creating and funding more public goods right now:

1. Permissionlessness
2. Transparency
3. Scalability
4. Culture

### Permissionlessness

At a high level, progress is the intersection of a person or group's aptitude, effort, and opportunity coming together to make an impact. If people are more educated/skilled, have the right incentives, and are given more freedom to pursue their ideas, we can expect better results.

Not rocket science, right? That's why society pursues improvements across all three areas.

But, the internet has shown that the opportunity lever is the "easiest" one to pull. Allowing the world to freely access information and interact on a permissionless network has obviously had a massive impact on the world.

Crypto amplifies the impact of that permissionlessness by allowing permissionless interactions to have credibility. Especially in the context of creating public goods, this is the game changer.

Instead of just governments, there are now almost 8 billion people worldwide that can credibly manifest sustainable public goods just by launching some smart contracts or a blockchain.

### Transparency

Disillusionment with governments can at least partly be attributed to how opaque the system is to the average citizen. We all like nice roads, education, and clean water, but how do our taxes actually flow to maintaining them? The lack of clear cause-and-effect between taxes (i.e investment) and return leads to underappreciation and underinvestment.

Public goods transparently administered on the blockchain can inspire more confidence from citizens. People are more likely to support investment in public goods, even voluntarily, if they can clearly see the impact of doing so.

### Scalability

The launch of Amazon Web Services S3 (cloud storage) and EC2 (cloud compute) in 2006 marked a new era of software company scalability.

AWS and the public cloud allowed startups to eliminate early capital expenditures and distractions (buying and running their own servers) to focus on their core idea/value prop. Operating costs scale with usage (i.e. success).

This new paradigm help fuel a golden age of venture capital investing for the last 16 years.

Smart contracts will spur a golden age of public goods entrepreneurship. An idea for a public good can be deployed as an autonomous smart contract for a one-time cost. Users pay transaction fees to interact with the smart contract, but each transaction is a positive economic trade (or presumably the user wouldn't do the transaction).

"Big ideas" deployed to blockchains don't need a war chest of VC money to scale to millions and eventually billions of users.

### Culture

Too often we forget that people are behind all technology. We can bend the arc of the future to what we want it to be.

The future isn't strictly formed through conscious decisions and perfectly laid plans, but it will largely reflect the dominant culture(s).

Crypto is the digital frontier. Those that have chosen to be here are the modern-day equivalent of the explorers that led humans to settle in every part of the globe. Explorers can have some rougher edges (they _might need_ them to survive), but they also understand the value of community and cooperation to overcome the challenges of the wild.

You can find that mindset in spades in crypto. It's why Gitcoin has been able to provide nearly [$65 million and counting to open-source developers](https://gitcoin.co/results). It's why we see experiments like [Retroactive Public Goods Funding](https://medium.com/ethereum-optimism/retroactive-public-goods-funding-33c9b7d00f0c). It's why we're attempting to build the Geo Web.

The culture is ultimately the number one reason that I know that crypto will create more abundance for the world through public goods.

## Technical

- Cody released [our new v3 Diamonds + ACL core contract architecture on Goerli](https://louper.dev/diamond/0x6CC6d2ba9668d5F8F5D08A45520E935cD6CDfc6f?network=goerli) over the weekend. It's missing a few functions/facets, but the bulk of it is there to start exploring (without a connected UI). We have to make a testnet migration regardless because our current home [Optimistic Kovan is being phased out](https://twitter.com/optimismFND/status/1542589602329919490?s=20&t=oN7lSS9sipW8_4QbnYb4ug). Optimistic Goerli doesn't have all of our dependencies yet, so we'll see how that develops before making an official move to a new testnet home ([https://github.com/Geo-Web-Project/core-contracts/pull/75](https://github.com/Geo-Web-Project/core-contracts/pull/75)).
- Corresponding changes to the Geo Web Subgraph and SDK are in the works as well ([https://github.com/Geo-Web-Project/geo-web-subgraph/pull/18](https://github.com/Geo-Web-Project/geo-web-subgraph/pull/18), [https://github.com/Geo-Web-Project/sdk/pull/2](https://github.com/Geo-Web-Project/sdk/pull/2))
- [Lolboysg](https://github.com/lolboysg) & [tnrdd](https://github.com/tnrdd) released on a beast of a PR to upgrade the Cadastre to Bootstrap v5 from v4. It was awesome seeing them collab on the changes and crank it out ([https://github.com/Geo-Web-Project/cadastre/pull/224](https://github.com/Geo-Web-Project/cadastre/pull/224)).
- We released a fix to address an issue finding pinsets if local browser storage was cleared on the Cadastre ([https://github.com/Geo-Web-Project/cadastre/pull/191](https://github.com/Geo-Web-Project/cadastre/pull/191)).

## Community

- [Loved this video](https://twitter.com/gitcoin/status/1557074721723891713?s=20&t=0CV-h_TkCaHBSpQzlc4A1Q) from [@Gitcoin](https://twitter.com/gitcoin) about [@austingriffith](https://twitter.com/austingriffith)'s personal journey to become the superstar public-goods/open-source developer that he is. Keep BUIDLing.
- [Tornado Cash was placed on the US Treasury's OFAC list](https://home.treasury.gov/policy-issues/financial-sanctions/recent-actions/20220808) over a week ago, and it's the talk of Crypto Twitter. Rekt News has a [good overview of the implications of the move](https://rekt.news/eye-of-the-storm/), which to say the least are far-reaching. Legal challenges [are likely on the way](https://twitter.com/coincenter/status/1559173293860585472?s=20&t=gryDfG3dVV02bzVOPqkOOg).

## On Deck

- Release v3 of the core contracts
- Release a new spatial browser
- More Cadastre tinkering
