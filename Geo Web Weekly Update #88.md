Public Goods Reflexivity: Weekly Update #88

https://www.geoweb.network/post/weekly-update-88

Embracing social feedback loops in addition to logical ones in the pursuit of more public goods. Plus updates from the Geo Web project (9/22/22 - 10/5/22).
# Public Goods Reflexivity
[Reflexivity](https://en.wikipedia.org/wiki/Reflexivity_\(social_theory\)) is a concept that refers to a circular relationship between cause and effect, especially in systems that include humans. 

In the context of markets, George Soros is the [most famous proponent](https://www.investopedia.com/terms/r/reflexivity.asp). He’s written [books](https://www.amazon.com/Alchemy-Finance-George-Soros/dp/0471445495) and [academic papers](https://www.georgesoros.com/2014/01/13/fallibility-reflexivity-and-the-human-uncertainty-principle-2/) to explain how he sees the markets: not as rational, equilibrium-seeking systems, but perpetually dynamic ones where subjective perception is the underlying force behind a trajectory.

He’s obviously been pretty successful in business with/because of this theory. Crypto markets probably provide some of the strongest evidence toward its merit (e.g. coins pumping with zero possibility of cash flow, but they are memes, so…).

*Irrationality* is an adjective often associated with this theory of reflexivity in markets, but that is not the whole story. The foundation of the theory is that sentiment in a system can *rationally* improve or degrade the underlying fundamentals of the system (i.e. when believing an outcome makes it more likely to occur). The feedback loop from the change in fundamentals back to perception is what creates the compounding effect that often ends in irrationality.

When we talk a lot about feedback loops, network effects, and flywheels on the Geo Web, we mostly do it through a purely logical lens. For example:



1) Funding from our [partial common ownership land market](https://docs.geoweb.network/concepts/partial-common-ownership) spurs the creation of more public goods which increases network utility which raises land values which creates more funding…
1) Better/more publishers having the opportunity to control Geo Web land means more network utility which attracts more users which attracts more publishers… 

But, there are definitely reflexive social dynamics at play in the Geo Web adoption plan (and for public goods in general).

Public goods often suffer underinvestment and development through [a version of a prisoner’s dilemma](https://en.wikipedia.org/wiki/Prisoner%27s_dilemma#Special_case:_donation_game). Participants are less likely to cooperate if they believe others will defect. Alternatively, believing that others will cooperate means that you should cooperate for a higher payoff. This is textbook reflexivity where the prevailing subjective perception ultimately impacts the outcome which compounds back into perception. (Check out [this great interactive tutorial from Nicky Case](https://ncase.me/trust/) for a refresher on game theory and how this plays out.) Social reflexivity also exists within the [concept of legitimacy](https://vitalik.ca/general/2021/03/23/legitimacy.html) that the Geo Web will rely on for adoption.

So as I see seemingly dumb meme coins skyrocketing in price, I try not to get too bothered by it. I agree with one of the greatest investors of all time: reflexivity is inherent in social systems. Rather than fight it, we should focus on channeling it toward positive-sum outcomes like public goods funding.

## Technical
- We’ve officially moved our [testnet](https://geoweb.land/) to Goerli today with the depreciation of the Kovan network! The new grid size is much smaller (mainnet size) and it uses the v3 contracts! We have one breaking change that will go in this week that will reset the registry, but we’re treating this testnet from there on out as a mainnet dry-run with a multi-sig deployment process and migrations to mitigate breaking changes (<https://github.com/Geo-Web-Project/cadastre/pull/250> & <https://github.com/Geo-Web-Project/browser/pull/40>). 
- Cody added a Superfluid SuperApp contract to serve as the beneficiary of all Geo Web PCO land market fees. This helps us close a certain security vulnerability and sets us up for [future public goods funding uses ](https://forum.geoweb.network/c/public-goods/10)(<https://github.com/Geo-Web-Project/core-contracts/pull/97>). 
- Tnrdd made performance improvements to our GPS to Geo Web coordinate library to help the Cadastre run smoother (<https://github.com/Geo-Web-Project/js-geo-web-coordinate/pull/7>). We have several other changes in the pipeline for the Cadastre that should create noticeable improvement!
- We added a Minimum For Sale Price & Claim Payment to the contracts for all Geo Web parcel claims to discourage early land grabs and squatting with dust-priced land (<https://github.com/Geo-Web-Project/core-contracts/pull/98>). The value will be configurable through governance, but the plan is to start at .005 ETHx ($6~7 currently; about the price of a cheap domain name for 1 year) with yearly Network Fees set at 10%.
- The [Geo Web’s documentation site](https://docs.geoweb.network/) is “feature complete.” Docs obviously *should be* ever-evolving, but the current version should capture our overarching vision and current implementation for mainnet launch!
## Community
- [Optimism’s Retroactive Public Goods Funding mechanism](https://medium.com/ethereum-optimism/retroactive-public-goods-funding-33c9b7d00f0c) isn’t in full swing yet… But it [sounds like we could be in for a big 2023](https://twitter.com/kelvinfichter/status/1575296142526627841?s=20&t=b7ds1x6wsNnCleSH6wJ3Bg). We’re exploring some mechanisms that could interface with RPGF on the investment side (write-up soon) and of course, are excited for Geo Web PCO proceeds to go to RPGF prizes as well.
- Our friends over at [Orbis](https://orbis.club/) have a [new website](https://twitter.com/OrbisClub/status/1575525520988684289) and continue to push social web3 forward. We’re really looking forward to integrating more geo-social experiences into the Geo Web Spatial Browser.
## On Deck
- Core contract security reviews
- Cadastre performance 
- Admin, marketing, and education for a mainnet launch…






