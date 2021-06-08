# P2P Content on the Geo Web: Weekly Update #32

https://www.geoweb.network/post/weekly-update-32

Decentralization doesn&#39;t end with smart contracts: the peer-to-peer content layer on the Geo Web completes the circle. That plus updates from the last week on the Geo Web project (6/2/21 - 6/8/21).

## P2P Content on the Geo Web

Peer-to-peer digital money and decentralized finance get a lot of the headlines in the blockchain space, but they aren&#39;t the only exciting use cases enabled by cryptography and [Merkle trees](https://en.wikipedia.org/wiki/Merkle_tree). After all, money, logic, data, and media are all just digital bits online.

So while the Ethereum smart contracts that administer our [digital land registry](https://docs.geoweb.network/concepts/digital-land-registry) and [partial common ownership market](https://docs.geoweb.network/concepts/partial-common-ownership) are certainly foundational to the Geo Web vision, they&#39;re not the full story.

The Geo Web&#39;s p2p content layer (composed of [Ceramic](https://ceramic.network/), [IPFS](https://ipfs.io/), &amp; [Filecoin](https://filecoin.io/)) plays a critical role in creating the decentralized, permissioness, &amp; uncensorable network that we believe an augmented reality metaverse should be.

Most of the web today runs on a client-server architecture. When you open an app or type a URL into a browser on your device (the client), it triggers a series of steps to retrieve the appropriate content from a specified server (via an IP address) in some far off place. That server (or group of servers) is a centralized point of failure, control, and censorship.

On a p2p network like IPFS, content is identified not by _THE_ server that holds it, but with a unique identifier for each atomic piece of content. Any peer on the network can retrieve content from other peer(s) by broadcasting the desired unique content identifier (you can learn more about [the mechanics and awesomeness of CIDs here](https://docs.ipfs.io/concepts/content-addressing/)). Ceramic comes in as a layer above IPFS that makes the management of mutable content (i.e. data/media/links that can change) easy and efficient.

This p2p content layer aligns with the project values mentioned earlier but also creates significant user experience benefits with network scaling, resiliency, speed, and efficiency.

High-fidelity augmented reality content files are typically very large. Geo Web content is geo anchored, so content seekers will naturally be geographically clustered. Why incur the cost and time required to retrieve the content off a remote server when a peer 10 feet away can share it directly with you?

Think of this in the context of a crowded concert or live sporting event. Instead of the usual degraded service on your smart device, the Geo Web experience improves with each peer that comes online. Instead of scaling remote servers + bandwidth or making huge local infrastructure investments, a seed small node can end up elegantly scaling to thousands of concurrent users with the help of peers. It&#39;s almost magical.

We&#39;re still in the early innings of the distributed web and smart contracts, but the building blocks are there. We couldn&#39;t be more excited to be exploring all of these p2p technologies.

On to the updates…

## Technical

- Added automatic stream pinning for content linked from the Cadastre ([https://github.com/Geo-Web-Project/cadastre/pull/41](https://github.com/Geo-Web-Project/cadastre/pull/41))
- GPS relocalization for the Geo Web Spatial Browser ([https://github.com/Geo-Web-Project/browser/pull/14](https://github.com/Geo-Web-Project/browser/pull/14))

## Community

- The Ethereum Foundation announced their [Core Dev Apprenticeship Program](https://blog.ethereum.org/2021/05/13/core-dev-apprenticeship/) about a month ago and they [received around 400 applications](https://twitter.com/trent_vanepps/status/1399817600486494209). It&#39;s an amazing initiative. Permissionlessness is a core value of Ethereum and many blockchain/crypto projects, but even better than not standing in the way of someone pursuing their idea/passion is building the bridges to help more people realize them. (Note: Staying consistent with permisionlessness, anyone can follow along and learn with the cohort even though there are a limited number of funded slots).
- [Funding Round 7](https://blog.clr.fund/round-7-announcement/) over at [clr.fund](https://clr.fund/#/) is wrapping up this evening. It&#39;s been so successful that they&#39;ve actually[hit the hard cap for contributors](https://twitter.com/clrfund/status/1401478368244158465). We&#39;re beneficiaries and big fans of quadratic funding (QF). We&#39;ve participated in both [clr.fund](https://clr.fund/#/project/0xeae9349d669abad47bb3adff2cef492247ed50a3eedd6c1d3e5420f66fd53473) and [Gitcoin](https://gitcoin.co/grants/1403/the-geo-web) QF matching rounds. Gitcoin recently took a big step toward decentralization with the [launch of their governance token](https://gitcoin.co/quadraticlands/mission). Clr.fund has been experimenting and building from a more decentralized starting place and done awesome work in implementing [MACI (minimal anti-collusion infrastructure)](https://github.com/appliedZKP/maci). We appreciate the trailblazing both of these platforms have done, and look forward to the day when Geo Web network funds are used to fund public goods with QF.

## On Deck

- Polish and prep for an end-to-end Geo Web beta release (contracts, Cadastre, publishing tooling, &amp; browser)
- Moving to Ceramic&#39;s Fire mainnet
- [Gitcoin GR10](https://gitcoin.co/grants/1403/the-geo-web) is starting June 16th!
