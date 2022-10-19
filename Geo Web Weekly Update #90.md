# Forward to Protopia: Weekly Update #90

[https://www.geoweb.network/post/weekly-update-90](https://www.geoweb.network/post/weekly-update-90)

We're trying to build a better future (which includes new challenges)—not a perfect one. Plus updates from the Geo Web project (10/13/22 - 10/19/22).

## Forward to Protopia

I was talking an entrepreneur friend through the full vision of the Geo Web a couple of weeks back over beers: [our land market's "edge case" handling](https://docs.geoweb.network/concepts/partial-common-ownership), [approaches to user-controlled content filtering](https://www.geoweb.network/post/weekly-update-20), [how partial common ownership promotes productive usage](https://www.geoweb.network/post/weekly-update-85),[the network effects at play](https://www.geoweb.network/post/weekly-update-67), [the public goods funding flywheel](https://www.geoweb.network/post/weekly-update-77), and [ultimately an optimistic perspective on human organization and innovation](https://www.geoweb.network/post/weekly-update-43).

He said something to the effect of "It's awesome you've worked out this utopian vision for the future in your heads and built a detailed system to make it happen."

He meant it as a compliment. I took it as one. It's hard to find better fuel to keep pushing to do something ambitious than having someone you respect "get it."

But, another reason I remember it vividly is because I winced internally at one of the words he used: _utopian_.

It's a loaded word. History is littered with promises of _perfect_ futures gone very wrong.

I am an optimistic person. The Geo Web is an optimistic project. We're certainly prone to believing that good things are possible a standard deviation or two outside the perceived norm.

But, we readily admit that we don't have it all figured out, there will always be tradeoffs, and there's no such thing as perfect.

It was serendipity that I received an email from the [Trusted Seed](https://trustedseed.org/) last week which had the word I'll be using to better describe the Geo Web vision: [_protopian_](https://wiki.p2pfoundation.net/Protopia).

[The aim of progress shouldn't be perfection, but continuous incremental improvement](https://aeon.co/ideas/utopia-is-a-dangerous-ideal-we-should-aim-for-protopia). That statement doesn't look controversial on the page. But as Kevin Kelly highlighted in [the post where he coined the term](https://kk.org/thetechnium/protopia/), optimistically marching into an unknown future isn't the default these days.

It takes courage (and space for nuance) to say that things can get better with technology, the economy, and politics after being burned. It takes courage to truly believe it.

But that's the type of future that we want the Geo Web to represent. We won't prove it with words, but we'll keep trying with our actions.

## Technical

- Tnrdd continues to crank out improvements and fixes for the Cadastre. Every day we're getting closer to the smooth, intuitive experience we want for users claiming Geo Web land ([https://github.com/Geo-Web-Project/cadastre/pull/267](https://github.com/Geo-Web-Project/cadastre/pull/267), [https://github.com/Geo-Web-Project/cadastre/pull/274](https://github.com/Geo-Web-Project/cadastre/pull/274), [https://github.com/Geo-Web-Project/cadastre/pull/271](https://github.com/Geo-Web-Project/cadastre/pull/271)).
- The biggest challenge on the Cadastre remaining is likely the performant rendering of parcels from the [Geo Web subgraph](https://thegraph.com/hosted-service/subgraph/geo-web-project/geo-web-subgraph). We've made some recent changes to handle extra large parcels ([https://github.com/Geo-Web-Project/cadastre/pull/266](https://github.com/Geo-Web-Project/cadastre/pull/266)), but we might need some deeper changes to our approach to get where we want to be ([https://github.com/Geo-Web-Project/cadastre/issues/268](https://github.com/Geo-Web-Project/cadastre/issues/268)).
- The Geo Web core contracts are going to be upgradable (for now) to allow the protocol to adapt and mature over time. Maintaining upgradability comes with trade-offs versus having immutable contracts—security, decentralization, & governance. We'll be launching with a multi-sig of founding members plus respected community members to manage the contracts and treasury initially ([https://github.com/Geo-Web-Project/core-contracts/pull/104](https://github.com/Geo-Web-Project/core-contracts/pull/104)).

## Community

This week it is all talks from Devcon for those (like me) that couldn't attend…

- Phil Daian gave [an important talk about the future of MEV](https://www.youtube.com/watch?v=ACXAzLy3iWY) and how Flashbots sees its role in helping promote better outcomes for the Ethereum ecosystem.
- Flashbots has done a lot for the Ethereum ecosystem, but [the controversial design decisions](https://twitter.com/thegostep/status/1578520702574960640?s=20&t=1J7mkYLoAtQ7TiA-dWWmSQ) they've made with their MEV-boost relay have put the network in a precarious position (note: they have open-sourced the code). So, Eric Wall's talk about the [Ethereum Layer 0 (i.e. the common user and builders) taking control of the direction of the network](https://www.youtube.com/watch?v=sFMEeQ4mebA&t=2s) by drawing a line in the sand for network-level censorship in the face of OFAC compliance overreach is a must-watch.
- Optimism announced their [OP Stack approach to their modular L2 rollup architecture](https://twitter.com/optimismFND/status/1582132280184954881?s=20&t=Z02NrVD4qnPJQt4vvDtwhw). Karl Floersch gave [a rundown in his usual high-energy way.](https://www.youtube.com/watch?v=HiU-g8XHi5s)
- Griff Green's [public goods funding and business model talk](https://www.youtube.com/watch?v=DBGoX7DON54) is right up the Geo Web's alley.

## On Deck

- Cadastre polish
- Contract security
- Launch prep :)
