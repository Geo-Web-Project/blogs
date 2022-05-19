# DeSoc &amp; Geo Web: Weekly Update #71

https://www.geoweb.network/post/weekly-update-71

A vision for building a better pluralist future. Plus updates from the Geo Web project (5/11/22 - 5/18/22).

## DeSoc &amp; Geo Web

Glen Weyl, Puja Ohlhaver, and Vitalik Buterin [released a paper](https://twitter.com/pujaohlhaver/status/1524392972044972033) last week called [_Decentralized Society: Finding Web3&#39;s Soul_](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4105763)_._

It received a lot of attention and excitement which isn&#39;t all that surprising given the reach of the authors. It wasn&#39;t really a _groundbreaking_ paper if you&#39;ve been paying attention though.

There&#39;s no disrespect intended because I think the authors would agree. And [there&#39;s nothing new under the sun after all](https://www.geoweb.network/post/weekly-update-59).

Vitalik [wrote about soulbinding NFTs (dubbed SBTs in the paper)](https://vitalik.ca/general/2022/01/26/soulbound.html) earlier this year. [POAP](https://poap.xyz/) has been seeding &quot;identities&quot; with context-rich tokens for several years. And many others have been hard at work on alternative approaches to SBTs with similar ends in the form of verifiable credentials or _VCs_ (shout out to our friends at [Ceramic](https://ceramic.network/), especially [Danny](https://twitter.com/dazuck)).

The point of the paper isn&#39;t that non-transferrable NFTs are the silver bullet that leads to utopia. The authors acknowledge the limitations, potential risks, challenges, and alternatives of the headline-grabbing technology of the paper (this is where it&#39;s helpful to get off Twitter to dig deeper!).

My main takeaway from the paper was an elucidation of a vision for the future that embraces the strength of [plurality](https://www.radicalxchange.org/media/announcements/a-new-chapter-for-radicalxchange/) and doesn&#39;t just rely on empty idealism to get us through. Technology that harnesses diversity of values, ideas, and relationships between individuals and groups from the bottom-up can truly be &quot;better&quot; than top-down in a complex world.

This paper is a rallying cry and one the Geo Web wants to answer.

We&#39;re excited about the possibilities of [partial common ownership](https://docs.geoweb.network/concepts/partial-common-ownership) and believe that&#39;s the seed of something potentially special. But for the network to reach its potential, we want to embrace values, ideas, and frameworks like the ones laid out in the DeSoc paper.

How will we address edge cases of &quot;economic abuse&quot; in the PCO market? How will users be able to manage the content (good, bad, and otherwise) that they&#39;re shown on the network? How will the funds from the PCO market be managed and spent? How will a global network be governed in a way that addresses geographic and social differences? How will we empower individuals to take advantage of economic opportunities on the network over bots and malicious actors?

Our small team doesn&#39;t have and will never have perfect answers to those questions, but we can attempt to design and adopt pluralist systems that lead to better emergent ones.

## Technical

- The Cadastre has REALLY slowed down, so we&#39;re taking some time to make changes to the v1 testnet even with our eyes on v2. Graven has been testing and Cody started making performance improvements to better handle the number of claimed parcels…plus bug fixes ([https://github.com/Geo-Web-Project/geo-web-subgraph/pull/17](https://github.com/Geo-Web-Project/geo-web-subgraph/pull/17), [https://github.com/Geo-Web-Project/cadastre/pull/130](https://github.com/Geo-Web-Project/cadastre/pull/130), [https://github.com/Geo-Web-Project/cadastre/pull/132](https://github.com/Geo-Web-Project/cadastre/pull/132), [https://github.com/Geo-Web-Project/cadastre/issues/131](https://github.com/Geo-Web-Project/cadastre/issues/131)).
- Zhyd1997 continued work on the v2 Cadastre Claims &amp; Fair Launch Claims ([https://github.com/Geo-Web-Project/cadastre/pull/126](https://github.com/Geo-Web-Project/cadastre/pull/126))
- Cody began exploring and optimizing the Geo Web coordinate grid size for an L2 launch. A smaller grid means better granularity, but there is a lower limit because of block sizes and gas costs. We&#39;re also attempting to ease any future migrations to smaller grid sizes or polygon definition of parcels with our initial implementation ([https://github.com/Geo-Web-Project/cadastre/pull/125](https://github.com/Geo-Web-Project/cadastre/pull/125)).

## Community

- We&#39;ve talked about how [clr.fund](https://twitter.com/clrfund) many times on this blog for their efforts in advancing quadratic funding infrastructure. So, we&#39;re excited to see them working with [ETHStaker](https://twitter.com/ethStaker) to run a [quadratic funding round focused on the Ethereum staking ecosystem](https://qf.ethstaker.cc/#/). The round runs for another 5 days and is on Aribitrum. Go donate!
- Trent Van Epps wrote a [good overview of The Protocol Guild](https://thedailygwei.substack.com/p/the-protocol-guild-the-daily-gwei?s=r) for [The Daily Gwei](https://twitter.com/thedailygwei). It&#39;s another valuable experiment/mechanism for funding public goods on Ethereum. This time it&#39;s focused on funding the individuals that contribute to the foundational protocols of the network. Everyone agrees these people should be getting paid and we want more funds flowing to this development, but doing it fairly, sustainably, and efficiently is tough. Looking forward to seeing this effort progress!

## On Deck

- L2 contract optimizations
- Continue work on the Cadastre v2
- Creating more visible and easy to grok content
