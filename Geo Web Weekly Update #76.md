# Smart contracts are the next AWS: Weekly Update #76

https://www.geoweb.network/post/weekly-update-76

AWS and the public cloud are cited as key reasons for the explosion of startups in the last ~15 years. Smart contracts and similar primitives will unlock at least another order of magnitude of capital efficiency and scalability for the next wave of innovation. Plus updates from the Geo Web project (6/16/22 - 6/22/22).

## Smart contracts are the next AWS

One commonly cited catalyst for the &quot;Golden Age&quot; of Web 2.0 startups is the emergence of the public cloud, starting with Amazon Web Services (AWS).

Once upon a time, software startups had to spend a good portion of their initial funding on buying, maintaining, and scaling the servers on which their app/service/network would run. Startups had to spend significant time and money doing something that wasn&#39;t going to be their core differentiator. That inherently meant fewer resources went to the core mission.

Enter AWS. Instead of big capital outlays and a dedicated infra team, a startup could deploy their code to AWS and immediately benefit from Amazon&#39;s economies of scale, security, and instant scalability. CAPEX was turned into OPEX that scaled with use (i.e. user growth). Small, nimble teams could compete with the behemoths better than ever before on the basis of their focused value proposition.

A couple years back, Ben Thompson of Strachery described [this era as a logical endpoint](https://stratechery.com/2020/the-end-of-the-beginning/) to the paradigm shifts that undergirded the tech industry&#39;s disruptive productivity gains. To be fair to Thompson, in subsequent writings he&#39;s acknowledged the potential of blockchains, but he and many others aren&#39;t convinced yet.

I am.

Smart contracts and decentralized services (like Filecoin, Helium, etc.) running on blockchains offer unparalleled scalability and capital efficiency for (certain types of) ideas to become world-changing realities.

Cloud OPEX morphs into transactional costs not even paid by the &quot;startup&quot; (unless they chose to). Projects can avoid hiring a team of ongoing reliability/maintenance personnel for the web3 parts of the stack. More than ever, it&#39;s about the execution and merit of the core vision.

Non-upgradable smart contracts take the idea of &quot;[default alive](http://www.paulgraham.com/aord.html)&quot; to the extreme: Uniswap contracts will live on no matter what Uniswap Labs does.

That&#39;s not to say there aren&#39;t tradeoffs and adjustments to be made in this shift. &quot;Move fast and break things&quot; is a terrible approach to designing and developing smart contracts. Gas optimization takes real expertise and is best done upfront. Blockchains have ecosystem-level scaling challenges to address, but I&#39;m confident with roll-ups and sharding that our blockchain of choice, Ethereum, [will get where it needs to be](https://vitalik.ca/general/2021/12/06/endgame.html).

The net result though is a more accessible, competitive, and powerful playing field for innovation than we&#39;ve ever seen before. Web3 is full of builders and founders making big impacts outside of Silicon Valley and with some still in high school. I&#39;ll bet on supercharged, [permissionless innovation winning in the long run every time](https://www.geoweb.network/post/weekly-update-75).

## Technical

- We released the &quot;Bid Response&quot; view on the Cadastre. This is for the current licensor to accept or reject a rival&#39;s bid for a parcel ([https://github.com/Geo-Web-Project/cadastre/pull/161](https://github.com/Geo-Web-Project/cadastre/pull/161)).
- We&#39;ve seen some instability with the Optimistic Kovan RPC through wallets, so we made a switch to use an Infura node for Superfluid data ([https://github.com/Geo-Web-Project/cadastre/pull/157](https://github.com/Geo-Web-Project/cadastre/pull/157)).
- We&#39;ve recently had some regression with our Media Gallery and integrated IPFS pinning+Filecoin archive functionality. One fix is in ([https://github.com/Geo-Web-Project/cadastre/pull/168](https://github.com/Geo-Web-Project/cadastre/pull/168)) another is on the way ([https://github.com/Geo-Web-Project/cadastre/issues/169](https://github.com/Geo-Web-Project/cadastre/issues/169)).
- We made a change to how claimed parcels are displayed for better UX [based on feedback from community member](https://forum.geoweb.network/t/geoweb-map-recommendations-feedback/91)[nickziats](https://forum.geoweb.network/t/geoweb-map-recommendations-feedback/91). More on the way. Thanks, Nick! ([https://github.com/Geo-Web-Project/cadastre/pull/159](https://github.com/Geo-Web-Project/cadastre/pull/159)).

## Community

- There&#39;s only one day left in Gitcoin GR14, so if you haven&#39;t made a [contribution to the Geo Web](https://gitcoin.co/grants/1403/geo-web) yet, we&#39;d really appreciate your support. Every DAI makes a difference! Thank you!
- We held our first community call earlier this week in the [Geo Web Discord](https://discord.com/invite/reXgPru7ck). We didn&#39;t record this first one, but here&#39;s[the short deck we used for the agenda and discussion](https://docs.google.com/presentation/d/1oQR2eT8F98OW8_t1xeIP5mAiAs4XNjJW7JWh59ChxFs/edit?usp=sharing).
- Community member Kevvles published a [SourceCred onboarding guide for the Geo Web](https://forum.geoweb.network/t/get-paid-to-contribute-to-the-geo-web-project-through-sourcecred/94). Great stuff! Looking forward to many more contributors being rewarded on this project.

## On Deck

- More Cadastre v2
- Exploring a modification to our Superfluid SuperApp for more composability and simplified core architecture
