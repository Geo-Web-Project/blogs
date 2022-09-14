# Appreciating The Merge: Weekly Update #86

https://www.geoweb.network/post/weekly-update-86

The Merge is about more than ETH issuance reduction, energy usage, and blockchain security models. It demonstrates the values and unwavering commitment of the Ethereum core engineers and community that we should all appreciate. Plus updates from the Geo Web project (9/1/22 - 9/14/22).

## Appreciating The Merge

Depending on where you are in the world, the biggest crypto event since the inception of Bitcoin or the launch of Ethereum will happen later today or tomorrow—[The Merge](https://ethereum.org/en/upgrades/merge/).

The Merge is the name given to the Ethereum network's move from proof-of-work to proof-of-stake consensus mechanism. It's [breaking through to mainstream media](https://www.google.com/search?q=The+Merge) unlike any software upgrade since the [Y2K scare](https://en.wikipedia.org/wiki/Year_2000_problem).

The Merge has practical implications that are easy for technical and non-technical people alike to appreciate: it lowers ETH issuance from the protocol (investors love less ETH being minted), and it reduces Ethereum's carbon footprint (PoS requires ~99.95% less energy than PoW).

Those attributes are about the end-state of being a PoS system. There is a huge amount of engineering that's gone into the short transition period between PoW and PoS to make sure it goes without a hitch that we should appreciate too.

Billions of dollars of applications rely on the Ethereum network continuing to produce block after block. There's no "(un)scheduled maintenance" or the ability for a phased roll-out for Ethereum. It's a hot swap in an adversarial, complex environment. It has to work.

Some rival blockchains haven't committed to that same rigor and have accepted some downtime as inevitable in their development. That's a mistake. Blockchains and smart contracts aren't _just software_. There are deep values and societal impact embedded in the things that we build. Moving fast and even occasionally breaking things should be anathema because that undermines the broader mission.

Another engineering-y attribute of The Merge (and Ethereum in general) that should receive more attention is [client diversity](https://ethereum.org/en/developers/docs/nodes-and-clients/client-diversity/). By design (technical and very much social), nodes on the Ethereum network don't all run the same code. They are developed to run to the same specification so that they can effectively run the network together, but each client implementation is different.

With sufficient client diversity, a client bug doesn't become a protocol/consensus bug because the other clients won't have the same coding mistake. This redundancy comes at a cost, especially as The Merge establishes separate _execution_ and _consensus clients_. Each execution/consensus client permutation can lead to different edge cases that must be handled.

The tradeoffs are worth it for Ethereans. Commitment to client diversity is yet another reason why Ethereum is the most robust and reliable smart contracting platform there is—even through a major change like this one. It also reinforces the cultural value that there isn't just one centralized team "building Ethereum." If you have strong differing opinions about how a client should be implemented, you're encouraged to do so. Instead of splintering the community, it is strengthened. That mindset bubbles up to the rest of the stack too.

The final dragon that the Ethereum core engineers and community needed to slay for The Merge was social in nature. For years there's been FUD (fear, uncertainty, and doubt) spread about Ethereum and its move PoS.

There's too much to rehash here, but it's easy enough to find a sampling on Twitter from people with "rival" blockchain tags in their bio. Some of the misinformation is water under the bridge: Ethereum's code will just keep doing its thing regardless.

But there are real social attack threats to The Merge that had to be taken seriously. Miners (the people that run the machines that create blocks in PoW consensus) had/have a strong vested interest in proof of work not going away on Ethereum. That's how they earn money!

The Ethereum core developers had to prepare for any and all shenanigans. The mechanisms for and orchestration of the consensus switch had to be hardened to reduce the miners' degrees of freedom to cause chaos even as they're needed up until the very last block. They're still going to try (the "ETHW" fork is a thing), but even if this cash grab survives it won't be a threat to The Merge.

After The Merge, Ethereum will be stronger and better than ever. That will continue to be true each successive day. It's worth celebrating the how and not just the what.

## Technical

- 0xtekgrinder completed work on the Reclaimer Facet contract. This was the final major piece of functionality for our v3 core contracts. This facet handles the Dutch foreclosure auction and reclaiming of a parcel when its Network Fee stream run dry ([https://github.com/Geo-Web-Project/core-contracts/pull/79](https://github.com/Geo-Web-Project/core-contracts/pull/79)).
- Cody added an [Orbis](https://orbis.club/)-powered chat element to the Spatial Browser which creates a chatroom for each Geo Web land parcel! Thanks to the Orbis team for open-sourcing the UI element/SDK and Ceramic's composability, this was really quick to implement and shows the model we want to replicate for Geo Web use cases ([https://github.com/Geo-Web-Project/browser/pull/35](https://github.com/Geo-Web-Project/browser/pull/35)).
- tnrdd released a preview build of our new Profile/Land Portfolio page for the Cadastre. Can't wait to release this one ([https://github.com/Geo-Web-Project/cadastre/pull/237](https://github.com/Geo-Web-Project/cadastre/pull/237))!
- We pushed several fixes to the v3 contracts and the Spatial Browser ([https://github.com/Geo-Web-Project/core-contracts/pull/83](https://github.com/Geo-Web-Project/core-contracts/pull/83), [https://github.com/Geo-Web-Project/browser/pull/36](https://github.com/Geo-Web-Project/browser/pull/36), & [https://github.com/Geo-Web-Project/core-contracts/pull/88](https://github.com/Geo-Web-Project/core-contracts/pull/88)).

## Community

- Gitcoin Grant Round 15 is live and the Geo Web needs your support! Every DAI counts at [https://gitcoin.co/grants/1403/geo-web](https://gitcoin.co/grants/1403/geo-web)!
- Vitalik continues to [advocate for Haberberger-ish pricing systems for ENS domain names](https://vitalik.eth.limo/general/2022/09/09/ens.html). Many of the reasons that he cites for why this would be a major improvement for ENS are even stronger when applied in the context of geospatial AR property rights like the Geo Web…

## On Deck

- Writing documentation
- Polishing the v3 core contracts and Cadastre
- Exploring more Geo Web use cases
