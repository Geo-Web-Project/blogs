# Wen Metaverse?: Weekly Update #91

[https://www.geoweb.network/post/weekly-update-91](https://www.geoweb.network/post/weekly-update-91)

Rather than timing the next computing paradigm, the Geo Web is an attempt to build a hyperstructure agnostic to when "the future" arrives. Plus updates from the Geo Web project (10/20/22 - 10/26/22).

## Wen Metaverse?

Ever since Facebook rebranded as Meta about a year ago, the $10,000,000,000 question has been, "When is the metaverse going to become _the thing_?"

That dollar figure is the size of the annual investment that Meta has publicly committed to its ongoing Reality Labs initiatives.

For some skeptics, this is like lighting money on fire. They believe that augmented and virtual reality will never become big parts of our lives. (Note: While AR and VR can use similar underlying technology, their user experience implications are different enough that a blanket dismissal of the _potential_ of both probably points to a lack of understanding.)

But as Meta announces their quarterly results today, even [long-term Facebook/Zuckerberg backers](https://medium.com/@alt.cap/time-to-get-fit-an-open-letter-from-altimeter-to-mark-zuckerberg-and-the-meta-board-of-392d94e80a18) and metaverse believers are questioning the size and timing of Meta's bet. After all, there's been hype around virtual reality for decades at this point. It is fair to question.

So as a project focused on a "metaverse opportunity," are we worried about timing?

Yes, timing in frontier tech can be everything.

But the five to six orders of magnitude difference in annual budget between Meta and the Geo Web probably understates the difference in implications of the strategies that we're each pursuing. Our timing challenges are opposites.

Meta is spending, come hell or high water, to make the metaverse happen as soon as possible and for their benefit. They don't want their business to be subjugated to Apple and Google in the next era (Zuckerberg talks about building an "open" platform, but their incentives as a business will always be to create an unfair advantage for themselves).

Being too early will cost them potentially hundreds of billions of dollars with limited return on investment. To add potential insult to injury, competitors will benefit from the years of Meta hardware R&D whenever the timing does become right.

For the Geo Web and the open metaverse, we're playing a different game. We can't be early enough. Our existential threat is having open spatial web browsing capabilities foreclosed on the next generation of smart devices [like Apple iOS rules would have done with web browsers if given the chance](https://twitter.com/tolmasky/status/1297199788316692480).

By building the right foundation for scale and proto-experiences now, consumers will demand that truly open experiences be included on their next-gen devices. There won't be excuses or plausible technical levers to keep them out.

Our ultimate goal aligns with this "timing be damned" perspective too. We're building the Geo Web to be a [hyperstructure](https://jacob.energy/hyperstructures.html)—_a protocol that can run for free and forever, without maintenance, interruption, or intermediaries_.

If we get it right, our core work can live on with or without the founding team. If/when we get things wrong, others can learn from, fork, and improve upon our work in the pursuit of the public good. ([This strategy is uniquely enabled by crypto and why I believe crypto will bring about a golden age of public goods](https://www.youtube.com/watch?v=RUijxzBs4Xg&t=30s).)

Rest assured, we're still trying to position the Geo Web for short-term success: the Geo Web can enable killer use cases on smartphones. Information-centric, geosocial, audio, and "novelty" AR experiences on the Geo Web can all work today.

So personally, I'm agnostic to Meta continuing to spend like this or slowing down. The metaverse is really just the inevitable, immersive evolution of the internet. It might pick up some new branding along the way (_Information Superhighway_ anyone?), but it will come.

We're not there yet, but we believe that we can make the Geo Web and the open metaverse inevitable too.

## Technical

- We made a change in our smart contracts to limit parcel claims to rectangles only ([https://github.com/Geo-Web-Project/core-contracts/pull/105](https://github.com/Geo-Web-Project/core-contracts/pull/105)). We were already doing this on the Cadastre UI, but now parcels are defined now as a single coordinate (SW corner) + height/width dimensions rather than a coordinate + arbitrary traversal path. We thought long and hard about this change. There are trade-offs. Ultimately this will help us with Cadastre/subgraph performance ([https://github.com/Geo-Web-Project/cadastre/pull/278](https://github.com/Geo-Web-Project/cadastre/pull/278)), long-term upgradability, and limiting "unnatural" early land claims. We believe arbitrary polygons which can be verified as non-overlapping are the ultimate answer, but doing that trustlessly & efficiently isn't currently possible. Maybe we could achieve it with an L3 zk-rollup someday?
- We continue to push out small tweaks and quality-of-life improvements on the Cadastre ([1](https://github.com/Geo-Web-Project/cadastre/pull/276), [2](https://github.com/Geo-Web-Project/cadastre/pull/279), [3](https://github.com/Geo-Web-Project/cadastre/pull/280), & [4](https://github.com/Geo-Web-Project/cadastre/pull/283)).

## Community

- Matt Levine of Bloomberg wrote a [massive "What is Crypto?" overview](https://www.bloomberg.com/features/2022-the-crypto-story/). It's a good read for crypto veterans and newcomers alike.
- The [Azuki NFT project proposed a new standard for Physical Backed Tokens (PBTs)](https://twitter.com/AzukiOfficial/status/1582057921516474368). The team released a [website exploring the hardware, UX, and standard further](https://www.pbt.io/). I'm excited to see this sort of idea combined with Geo Web land parcels for scavenger hunts and check-ins. Geo Web AR could help users find the PBT chip to scan & claim the NFT or become "king of the hill."
- [Superfluid streams (including on the Geo Web) are now NFTs](https://medium.com/superfluid-blog/superfluid-streams-are-now-visible-as-nfts-in-your-wallet-15b8f39b0b03)! This creates more visibility, composability, and ultimately some interesting opportunities for DeFi applications (like borrowing with your streamed income as collateral).
- [Optimism](https://twitter.com/optimismFND) and [Lattice](https://twitter.com/latticexyz)[released a Minecraft-inspired world](https://dev.optimism.io/opcraft-autonomous-world/) that's fully encapsulated in an OP-stack rollup. [OPCraft](https://opcraft.mud.dev/) is pretty impressive and shows the power and scalability we'll be able to achieve with L2s.

## On Deck

- More Cadastre work
- Security focus
- Demos
