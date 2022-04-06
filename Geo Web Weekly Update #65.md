# Inflexible Systems or Human Judgment: Weekly Update #65

https://www.geoweb.network/post/weekly-update-65

Which do you trust more? Plus updates from the Geo Web project in the last two weeks (3/24/22 - 4/6/22).

## Inflexible Systems or Human Judgment

Last week, [Dan Robinson of the Paradigm research team](https://www.paradigm.xyz/team/danrobinson) put out a Twitter poll:

[Which do you trust more?](https://twitter.com/danrobinson/status/1509543920732196864)

- [Inflexible systems](https://twitter.com/danrobinson/status/1509543920732196864)
- [Human judgment](https://twitter.com/danrobinson/status/1509543920732196864)

_Inflexible systems_ was the winner. That&#39;s not all that surprising for a crypto-leaning audience: the genesis project of the blockchain movement prominently features a hard-cap token supply amongst other fixed attributes.

For some in the space, inflexibility/immutability is the whole purpose of blockchains. [21M Bitcoin is dogma today even in the face of existential threats](https://twitter.com/hasufl/status/1511470668457652224).

I fundamentally disagree with this perspective. My answer is _human judgment_ without a doubt. The biggest impact that blockchains and smart contracts will make in the world is [the creation of better ways to coordinate human judgment](https://youtu.be/KpXPym_m_wA?t=32), not eliminate it.

Humans definitely aren&#39;t always trustworthy, but inflexible systems ignore the fundamental properties of the universe itself. The world is constantly evolving and [entropy keeps doing its thing](https://www.geoweb.network/post/weekly-update-64) which inevitably leads to changing optimal responses.

To boot, somewhere in the chain of history a human defined (directly or indirectly) every inflexible system and even Satoshi wasn&#39;t/isn&#39;t omniscient.

There are two worldview categorizations that I think would correlate highly with the answers seen in the poll: [fixed vs growth mindset](https://fs.blog/carol-dweck-mindset/) &amp; [convex vs concave dispositions](https://vitalik.ca/general/2020/11/08/concave.html). I&#39;ll let you do the mapping.

While it may be psychologically more comforting to stake out a single immutable implementation, I&#39;ll take my chances with adaptability and constantly improving our decision making systems… including occasionally implementing an immutable-ish attribute or two :).

## Technical

- The Reclaimer module for our streaming network fee infrastructure is complete. This module is used to return a parcel to the land market when a licensor&#39;s stream runs out. It uses a Dutch auction to create fair price discovery between the previous For Sale Price and a free claim ([https://github.com/Geo-Web-Project/core-contracts/pull/55](https://github.com/Geo-Web-Project/core-contracts/pull/55)).
- The penalty that a licensor has to pay to reject a parcel bid is now calculated based on the new For Sale Price to better encourage honest self valuations ([https://github.com/Geo-Web-Project/core-contracts/pull/60](https://github.com/Geo-Web-Project/core-contracts/pull/60)). Background for this reasoning can be found[here in the Geo Web forum](https://forum.geoweb.network/t/owner-forgiving-auctions-specification-discussion/43/23?u=graven).
- We&#39;re now storing self-assessed values/for sale prices rather than deriving it for UX/rounding reasons ([https://github.com/Geo-Web-Project/core-contracts/pull/57](https://github.com/Geo-Web-Project/core-contracts/pull/57)).
- We needed to upgrade our Node version so the Cadastre could run locally on M1 Macs ([https://github.com/Geo-Web-Project/cadastre/pull/93](https://github.com/Geo-Web-Project/cadastre/pull/93)).

## Community

- I guess it&#39;s a Dan Robinson week this week. Dan and other gigabrains released some research/design for &quot;[Gradual Dutch Auctions](https://twitter.com/FrankieIsLost/status/1511011123683741698?t=6PLjtrijr1i3RqhAfI75Yw&amp;s=19).&quot; We&#39;re going to use simple linear auctions for our fair launch and reclaim functions, but this is still interesting stuff to consider.
- Vitalik released &quot;[In Defense of Bitcoin Maximalism](https://vitalik.ca/general/2022/04/01/maximalist.html)&quot; on April 1st. Is it the best steelman-ing of Bitcoin I&#39;ve ever read or is it an April Fools joke? Yes. If art is meant to make you think without the artist having to say how to think, this is that. Just perfect. :chefskiss:

## On Deck

- The [Cadastre redesign](https://hackmd.io/kfTmkCQ3RnmsCs96WoIL9A?both) corresponding to all the smart contract changes we&#39;ve been making is coming!
- [Integrating the new Self.ID SDK](https://github.com/Geo-Web-Project/cadastre/issues/107) and other changes to improve the DID &amp; stream management UX
