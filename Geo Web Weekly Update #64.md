# Entropy &amp; Incentives: Weekly Update #64

https://www.geoweb.network/post/weekly-update-64

Cryptoeconomic systems don&#39;t eliminate entropy, but the best ones create perpetual incentives for participants to _actively_ counteract it. Plus updates from the Geo Web project in the last week (3/17/22 - 3/23/22).

## Entropy &amp; Incentives

One lens for how I think about system design can be summarized with the Second Law of Thermodynamics: entropy in the universe (or a closed system) will always increase over time.

It&#39;s a bit of a combination of [a first principle and thinking by analogy](https://www.geoweb.network/post/weekly-update-60).

There are no perpetual motion machines, but that doesn&#39;t stop some crypto projects and speculators from touting the equivalent.

Cryptoeconomic systems, everything from hard-cap/deflationary designs to complex defi Rube Goldberg protocols, need &quot;energy&quot; continually added from outside the system to grow value (i.e. counteract entropy).

Good system design acknowledges this fact, incentivizes addition of energy (in its many forms--this isn&#39;t a PoW maxi piece), and efficiently converts it to value.

[Partial common ownership property rights](https://docs.geoweb.network/concepts/partial-common-ownership) do exactly that. Instead of getting lucky in a land grab and riding it out to eternity, licensors must continually strive to create value for themselves and the network.

Private property rights have been held up as _the solution_ to incentivize individuals to continually invest time, energy, and capital in economic systems because the individual reaps the direct benefits of their labor/capital. Commonly held property and resources completely lack that incentive mechanism ([supposedly](https://en.wikipedia.org/wiki/Elinor_Ostrom)).

The value of _a thing_ isn&#39;t just derived from the isolated investment of one though. In any system/economy/network, there are spillover effects from the efforts of others. As our world becomes more and more networked, the latter factor increases in importance and errodes the individual incentive to actively contribute.

True-blue capitalists are quick to point out free rider problems in socialist systems, but don&#39;t yet see the hypocrisy in their stance in the Information Age.

It&#39;s easy to believe in the sanctity and supreme efficacy of private property for individuals who capture value created predominantly by someone else&#39;s input (or from one&#39;s work done long in the past).

But the laws of the universe are immune to cognitive dissonance. The systems, ideas, and values that best address reality are the ones that win out in the long run. In the case of property rights, partial common ownership is the system that acknowledges that entropy exists.

## Technical

- In our L1 contracts, gas minimization was paramount in every design decision we made. It&#39;s what led us to our non-refundable deposit system for partial common ownership. Moving to an L2 roll-up (zkSync 2.0!) opens up the design space to broader considerations. One example is our move to a streaming payments system. Another just implemented is the storage of a parcel&#39;s self-assessed value instead of calculating it based on a per second network fee rate ([https://github.com/Geo-Web-Project/core-contracts/pull/57](https://github.com/Geo-Web-Project/core-contracts/pull/57)). There are 31,536,000 seconds in a 365-day year, so there are bound to be rounding issues in that calculation. So, storing the value is much better from a UX perspective.
- We&#39;re starting to lay the tracks for more non-core contributors. Keep an eye on our [Github org](https://github.com/Geo-Web-Project) and [docs](https://docs.geoweb.network/) for new issues/bounties, content, and info. We are definitely still looking for core contributors too, but our goal is to make the onramp more accessible and create opportunities for drop-in contributions.
- The current Cadastre has lots of performance issues and crashes often. Since there&#39;s a redesign coming soon and the testnet isn&#39;t mission critical right now, we haven&#39;t prioritized addressing the issues. We&#39;ll get back to a reliable Cadastre soon!

## Community

- We are in the final homestretch of Gitcoin GR13 (ends 3/26 at 6pm MDT). Contributions have picked up, but [our grant](https://gitcoin.co/grants/1403/geo-web) has been trending down below the matching funds cap of $30k. That means your contribution can result in a large match ($1=$43 as of writing). This is the final shill for the quarter. Thank you for your support!
- [Happy third birthday to Simon de la Rouviere&#39;s](https://twitter.com/simondlr/status/1505895199284899848)[_This Artwork is Always on Sale_](https://twitter.com/simondlr/status/1505895199284899848)! A true trailblazing builder and idea.
- Matters Lab (not to be confused with Matter Labs known for zkSync) built a Harberger tax/[Million Dollar Homepage](http://www.milliondollarhomepage.com/) fusion. Still early in development and I haven&#39;t been able to find the code, but it&#39;s exciting to see others experimenting with PCO NFTs! Pixels are effectively just digital land parcels :).

## On Deck

- No blog post next week because I&#39;ll be traveling
- Cadastre redesign
- Reclaimer functionality for &quot;expired&quot; parcels
