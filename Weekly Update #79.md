# On Software Ossification: Weekly Update #79

https://www.geoweb.network/post/weekly-update-79

The forces that shape the evolution of software look a lot like the biological ones that govern change in living organisms. Plus updates from the Geo Web project (7/7/22 - 7/13/22).

## On Software Ossification

There are biological processes that generally lead organisms to change less with time. As realities of nature, people stop growing, our personalities tend toward a more stable equilibrium, and our brain&#39;s neuroplasticity decreases.

Some of these outcomes are thought of as negative. We try to take steps to slow or even reverse these processes. But, there are also clear reasons that we want the rate of change to decrease in certain contexts (or at least accept it as inherent). Infants have lots of neuroplasticity, but converting that dynamism into durable knowledge, skills, and pattern recognition (i.e. a lower rate of change) is actually the goal.

The optimal rate of change depends on the attribute, the person/organism, the goals, and the environment.

Last night, I saw a [short Twitter thread from Eric Wall (&quot;former&quot; Bitcoin maximalist) and Time Beiko (Ethereum Foundation)](https://twitter.com/TimBeiko/status/1547043172974460928?t=0B525kxEeXVpaUmmlMvbFw&amp;s=19) that reminded me that while software is not subject to biological forces, it encounters forces that end up mimicking them. There are inherent, external, desirable, and undesirable influences that govern the evolution of software (and information generally). This ends up playing out as Darwinian competition just like in nature.

The context of Eric&#39;s original tweet is that &quot;Bitcoin maxis&quot; often vehemently criticize any blockchain/crypto project that doesn&#39;t adhere to Bitcoin&#39;s strict no-[hard-fork](https://www.investopedia.com/terms/h/hard-fork.asp) ideology (and tbh just isn&#39;t Bitcoin). For Bitcoiners, the protocol&#39;s 21 million BTC cap is the holiest of attributes. It can never be changed. I think it is also fair to say that this core belief skews all other rates of change in the protocol toward zero.

Ethereum, on the other hand, has cultivated a more dynamic culture from the start. A vision for a transition from proof-of-work to proof-of-stake was communicated very early. Certain extra-protocol changes have been made and will continue to be made with social consensus. But as Tim points out in the tweet thread, natural forces are pushing Ethereum toward ossification too.

So is software ossification good or bad? [The optimal answer is usually somewhere in between two extremes](https://vitalik.ca/general/2020/11/08/concave.html). And regardless of intention, software system evolution is subject to the heavy influence of its founding DNA.

I work in the blockchain space because I believe in the social and technical value of strong guarantees [especially when it comes to platforms](https://www.geoweb.network/post/weekly-update-78). But, I&#39;m probably personally biased toward leaving some space for subjectivity, adaptability, and optimism. The world is too complex to ever design a perfect system. If you did, the world would still change on you. We should keep trying though.

We&#39;re still quite early in the Geo Web&#39;s story (_wen mainnet??_), but I hope we&#39;re already establishing a culture that rejects dogmatic inertia and embraces change where/when needed. We&#39;ve tried to take great care and patience in architecting the system to minimize future disruptions, but to paraphrase what [my co-founder Cody once wrote](https://github.com/Geo-Web-Project/garden/blob/main/content/notes/The%20Geo%20Web%20Grid%20System%20is%20Wrong.md), &quot;Every decision we make will eventually be wrong.&quot; The Geo Web&#39;s growing group of &quot;we&quot; needs room to adapt for this project to become what we envision it to be. Bitcoin maxis might scoff at us for it, but I&#39;ll take our chances.

## Technical

- We released the last required screen for market transfer functionality on the Cadastre ([https://github.com/Geo-Web-Project/cadastre/pull/192](https://github.com/Geo-Web-Project/cadastre/pull/192)). The foreclosure scenarios (i.e. a licensor&#39;s payment stream runs dry) are up next and will get us to feature complete for land market operations.
- We&#39;re making more behind-the-scenes content layer updates with Ceramic to improve the performance and stability of Geo Web publishing ([https://github.com/Geo-Web-Project/cadastre/pull/193](https://github.com/Geo-Web-Project/cadastre/pull/193)).
- We&#39;re updating the educational/help text throughout the Cadastre to ease the learning curve for our partial common ownership market structure ([https://github.com/Geo-Web-Project/cadastre/pull/194](https://github.com/Geo-Web-Project/cadastre/pull/194), [https://github.com/Geo-Web-Project/cadastre/pull/195](https://github.com/Geo-Web-Project/cadastre/pull/195), &amp; [https://github.com/Geo-Web-Project/cadastre/pull/196](https://github.com/Geo-Web-Project/cadastre/pull/196)). It&#39;s especially great that these PRs have come from new contributors to the project!
- We made a few cosmetic and navigational changes to the Cadastre map to help reinforce the tie between Geo Web land and the &quot;real world&quot; ([https://github.com/Geo-Web-Project/cadastre/pull/197](https://github.com/Geo-Web-Project/cadastre/pull/197)).

## Community

- The Geo Web isn&#39;t focused on building XR hardware and is designed to be agnostic to the hardware stack, but we&#39;re obviously still dependent on many advances in hardware to fully realize our vision. I enjoyed this rundown from XR industry pioneer, [Avi Bar-Zeev](https://twitter.com/avibarzeev), with his [roadmap to all-day smart glasses](https://avibarzeev.medium.com/the-road-to-all-day-xr-glasses-46063af34285).
- The [Geo Web Dework Bounty Board](https://app.dework.xyz/geo-web) is really picking up. I&#39;d recommend Dework to any other open-source/crypto project out there looking for bounty contributors. It&#39;s super easy to set up, managing/paying bounties is simple, and there are a lot of great contributors looking for new projects on the network.

## On Deck

- SuperFluid contract architecture review continues
- Spatial browser updates for the new testnet
