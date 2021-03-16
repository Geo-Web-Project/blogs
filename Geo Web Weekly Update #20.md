# User-Centric Content Moderation: Weekly Update #20

weekly-update-20

Our plans for putting the user at center of the Geo Web experience and updates from the last week (3/10/21 - 3/16/21)

## User-Centric Content Moderation

We&#39;ve had an awesome week of engagement from the community, largely spurred by [our Gitcoin grant](https://gitcoin.co/grants/1403/the-geo-web). We&#39;ve really enjoyed sharing the Geo Web vision with a lot of new people.

The first question that we get in an introduction is typically around land allocation and our [SALSA/Harberger Tax system](https://www.geoweb.network/post/the-geo-web-salsa). The second is some form of a question around content moderation.

The idea of ads or unwanted content being shoved in your face at any time sounds even less appealing in the physical world than it does on the web. This is actually [a big motivation for why we&#39;re building the Geo Web](https://twitter.com/thegeoweb/status/1370079913944961040).

We think that the economic incentives of SALSA will play a role in encouraging pro-social content (i.e. good for both the publisher and the consumers) on the network, but it&#39;s not the whole answer. Any network at global scale will include bad actors with bad incentives. It&#39;s part of the human condition.

The cost of bad actors can be felt by publishers (who incur the opportunity cost in not being able to publish in a space) and of course by users (whose attention and resources are abused, manipulated, or sold).

We&#39;re still early in our development, so we don&#39;t have all the answers nor are there absolutes when it comes to content moderation vs free speech. But, we do have some principles and frameworks outlined which we believe can make the Geo Web protocols a part of the solution for pervasive AR rather than just the source of a problem that is externalized.

It starts with putting the user at the center of the Geo Web experience. That should be uncontroversial, but is tough to effectively put into practice. We&#39;d argue it&#39;s impossible if your network/platform has profit motives anchored in the attention economy. So, we started by explicitly shedding that conflict of interest and are committed to community ownership of the network and its fees.

Putting the user at the center also means giving them effective tools and information to enact their preferences. &quot;We&quot; won&#39;t take explicit action to block content, but instead give individual users the ability to avoid undesirable content and the network (being the collection of all users) the power to punish those that take actions harmful to others and/or are illegal.

We think that a system that includes a combination of the following can effectively scale to the type of global (but finitely sized!) network that we aspire to be:

- **Browser filtering** - Geo Web browsers should be built with user-controls for filtering/blocking content. The Geo Web protocols are open-source, so we hope to encourage competition and innovation in the browser space that emphasizes the user-centricity.
- **Unique humanity** - Simply proving that a unique human is behind a publishing account is a huge step to promoting the type of network that users desire. It changes the dynamic of whack-a-mole for bots and zero reputational costs to bad actors.
- **Publisher reputation** - Past actions are one of the best predictors of current and future actions. Does the publisher have a long history and cumulative investment of licensing a land parcel? Have they previously been identified as serving extractive content? Our core protocols should aggregate and provide transparency to this type of information in a credibly neutral way.
- **Land ownership incentives and safeguards** - Physical land owners will have different motivations for utilizing Geo Web land than digital-only licensors. As physical land records become more digitized and integrated to Web3, we can offer &quot;tax rebates&quot; to land owners/tenants to advantage cohesive digital-physical content publishing. We&#39;ll also explore moving from effectively continuous SALSA auctions to periodic auctions (like monthly rent or a mortgage) and transitional periods to discourage &quot;hit and run&quot; attacks.
- **Content type labeling** - Create objective categories by which all Geo Web content must be labeled. These categories can illuminate the publisher&#39;s motivations and the experience created through consumption. Users can filter accordingly. Publisher reputations would be punished by the network for violating the objective category standards. Example categories could include passive content (like architecture and art), interactive content (requires user input or is fully immersive), 1st-party ads, 3rd party ads, and adult content.

Let us know what you think of this early framework. Free speech and content moderation are a fraught subject, so the more discussion the better (Is there a German word for whatever irony that just was?).

On to the updates...

## Technical

- We want to make it super easy for even non-web3 native users of the Geo Web to store their linked content in a p2p/distributed manner. We&#39;re taking the first step in that process by i[ntegrating the IPFS Pinning Service API](https://github.com/Geo-Web-Project/js-pinning-service-http-client) to the Cadastre. Users will be able to upload content (including AR files) via the Cadastre and pin them to the service/node of their choice—local, a Geo Web hosted service, [Pinata](https://pinata.cloud/), etc. After that, it&#39;s on to [Filecoin](https://filecoin.io/build/#intro) and [Textile Powergate](https://docs.textile.io/powergate/) integrations.
- We posted our first ever paid, open bounty: [upgrade our Web3 wallet integrations on the Cadastre](https://github.com/Geo-Web-Project/cadastre/issues/28). If you&#39;re interested or know someone who might be, jump in on the issue comments! There are more bounties to come, so keep an eye out and [join our Discord](https://discord.com/invite/pxvgHuT6Rg).

## Community

- It&#39;s easy to gloss over when someone says that &quot;their expectations were blown away,&quot; so in this case I really want to emphasize… our expectations for [our Gitcoin Round 9 grant](https://gitcoin.co/grants/1403/the-geo-web) have ABSOLUTELY been blown away. The NFT space has been on fire lately, and we&#39;re beneficiaries of that. So far, we have 557 contributors and have raised over $5,200 in direct contributions. Amazing.
- More importantly, Gitcoin has been great for raising awareness for the project. We&#39;ve stayed mostly heads down building out this crazy idea, so the influx of new [Discord community members](https://discord.com/invite/pxvgHuT6Rg), [Twitter followers](https://twitter.com/thegeoweb), and [newsletter subscribers](https://landing.mailerlite.com/webforms/landing/l0s9s9) is super gratifying. We&#39;re trying to build an open org around this exciting technology, so invite anyone and everyone that might be interested in joining our little movement.
- We [approved](https://aragon.1hive.org/#/geoweb/0xd5a7aea1034e82976843134c64792373ee34bd04/vote/2/) our first ever [SourceCred Grain distribution](https://geo-web-project.github.io/sourcecred-instance/#/accounts) to the tune of 1,000 xDAI. As the community and network grows, we look forward to larger and more frequent distributions to all the different types of Geo Web contributors.

## On Deck

- More Gitcoin grant shilling... [Please donate](https://gitcoin.co/grants/1403/the-geo-web) if you haven&#39;t yet and tell your friends too! Gitcoin is a great place to introduce your non-crypto friends to a bunch of different tools and ideas in Web3.
- Continue development on Cadastre publishing (e.g. pinning, linking, media gallery template) and browsing functionality
