# Strategic Diseconomies of Scale: Weekly Update #94

[https://www.geoweb.network/post/weekly-update-94](https://www.geoweb.network/post/weekly-update-94)

Economies of scale can create tremendous value, but in some cases, they're the opposite of what we want to design for in web3. Plus updates from the Geo Web project (11/17/22 - 11/30/22).

## Strategic Diseconomies of Scale

The defining forces of the Internet Age are network effects and their cousin economies of scale.

Early web advocates had utopian visions for the future. Society would be more connected than ever and free to exchange information and value without gatekeepers.

While the architectures that underpin most of what we know as the internet were designed as peer-to-peer protocols, in practice they evolved into client-server-dominated ecosystems.

The intention was to create decentralized networks, yet seemingly paradoxically some of the largest concentrations of wealth, power, and de facto gatekeeping ensued. Network effects and economies of scale are the reasons why.

The crypto/web3 movement aims to "retake" the internet with many of those same goals for a more egalitarian, free, and open future. But the cold hard economic truths of networks and scale haven't disappeared because we wave a _blockchain_ wand over them (nor would we necessarily want them to; lots of surplus value can be created through these processes).

So, the challenge for web3 is to embrace network effects and economies of scale while also explicitly assigning and strategically enforcing value toward decentralization (i.e. lack of scale & homogeneity).

In the Ethereum ecosystem, there is a deeply-held commitment to [client diversity](https://ethereum.org/en/developers/docs/nodes-and-clients/client-diversity/). It's a core tenant of the community to support multiple, distinct client implementations which adhere to the Ethereum protocol specification.

This commitment requires more work. It fights against natural economic forces. The community believes that it makes up for the cost with a more resilient network and a culture that doesn't enshrine a [cathedral](https://en.wikipedia.org/wiki/The_Cathedral_and_the_Bazaar). Those "soft" benefits don't cleanly map into microeconomic decision-making though. There's a [tragedy of the commons](https://en.wikipedia.org/wiki/Tragedy_of_the_commons) dynamic at play.

Ethereum's enforcement mechanisms for client diversity are mostly social rather than technical or economic (Proof-of-Stake slashing does create defensive incentives to use a minority consensus client). The [efforts of many in the community are laudable](https://clientdiversity.org/), but the challenge is never-ending.

The Geo Web shares many of the same values and goals as Ethereum, so we'll face these challenges as well. The ace-in-the-hole that we have in designing the Geo Web that the early web pioneers didn't is native protocol revenue which can be used to assign explicit economic value toward encouraging decentralization and its downstream effects.

We talk about [funding more public goods here all the time](https://www.geoweb.network/blog). We have lots of [ideas that we can't wait to experiment with](https://forum.geoweb.network/c/public-goods/10). A thread that I hope to explore throughout the implementation of those ideas is the diseconomy of scale; protocol funding receipt that slows (or even goes negative) as a market participant reaches undesirable levels of dominance.

Instead of run-away compounding advantages for the most used Geo Web [Cadastres](https://geoweb.land/)[,](https://geoweb.land/)[Spatial Browsers](https://geoweb.land/), and services funded by the protocol, can we implement mechanisms that encourage innovation and economic surplus without introducing de facto gatekeepers or centralized risk?

To apply this idea in Ethereum client diversity terms, client development teams could be paid from protocol revenue based on their weighted-average market share during a time period. Up to 33%, the team receives an accelerating payment per point of market share. Incentives are aligned for teams to compete to build the best client and attract users.

At 33%, their payout growth could slow. Teams still are rewarded for continuing to innovate, but payments start to shift to the "best laggards" with marginal adoption to help them catch up. As the market share for a client climbs closer to 66% (the existential risk point), the earned payout would start to decrease in absolute terms and eventually reach zero at 66%.

Maybe we'll get there with the Geo Web! Client development teams have always been in search of sustainable business models.

## Technical

- We've continued to focus on our smart contract security with a friend of the project [colinnielsen](https://github.com/colinnielsen). We've made changes to [help prevent reentrancy attack angles](https://github.com/Geo-Web-Project/core-contracts/pull/108), updated our [versioning approach for our upgradable facets](https://github.com/Geo-Web-Project/core-contracts/pull/107), and are now taking a [more conservative default approach to token authorizations](https://github.com/Geo-Web-Project/cadastre/pull/313). Other improvements and changes are in progress, but we're feeling really good about launch preparedness!
- We've added new [validations](https://github.com/Geo-Web-Project/cadastre/pull/324) and [warnings](https://github.com/Geo-Web-Project/cadastre/pull/319) to the UX to help improve UX.
- The XR Goods team (ecosystem partner) has been [experimenting with a WebXR implementation](https://github.com/Geo-Web-Project/browser/pull/53) on the Geo Web's Spatial Browser.
- We've made some changes to the header of the Cadastre to [highlight the public goods funding generated by our PCO land market](https://github.com/Geo-Web-Project/cadastre/pull/310) and (when appropriate) [provide information related to the Geo Web's fair launch](https://github.com/Geo-Web-Project/cadastre/pull/317)!

## Community

- We released a [video tutorial explaining the Geo Web's approach to on-chain land definition](https://www.youtube.com/watch?v=1dWMou7OCtg&t). Check it out!
- The [ETHDenver 2023 application](https://www.ethdenver.com/apply) is live. Get your app in early! The whole Geo Web team plans to be there and would love to see you there. We'll be developing some Geo Web experiences around Denver for the conference. If you'd be interested in partnering, hit us up!
- We released a few new governance-focused documents in preparation for our mainnet launch. [Check them out here](https://docs.geoweb.network/community-and-governance/geo-web-principles)! Feedback and participation are always [welcome on the forums too](https://forum.geoweb.network/).

## On Deck

- Security & polish
- Deploying contracts
- Spreading the word about the Geo Web
