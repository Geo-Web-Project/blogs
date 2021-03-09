# Geo Web Weekly Update #2

## November??

It&#39;s been a wild year to say the least. We can&#39;t believe it&#39;s already November. Time seems to fly when your routine mostly consists of staying and working at home. While we&#39;d trade it for the normalcy/safety of non-pandemic in a heartbeat, the last ~eight months have been quite creative and productive for the Geo Web project.

The project didn&#39;t exist eight months ago. Before this pandemic is done, we&#39;ll have the infrastructure and network live. That&#39;s our personal silver lining, but we hope the Geo Web can be more than that.

We want the Geo Web to enable _magical_ experiences that get people out enjoying the world together. Whether it&#39;s a beautiful AR art installation in a public park or a new digital experience at a local restaurant, the Geo Web is designed to be shared, out in the physical world. On the other side of this pandemic, we&#39;re all going to want to get out, be social, and enjoy ourselves. The Geo Web can be part of that return to a new normal.

On to the updates...

## Technical Updates

- We completed a test integration of our [land parcel subgraph](https://thegraph.com/explorer/subgraph/geo-web-project/geo-web-subgraph) on The Graph. The subgraph indexes parcels minted in the GeoWebParcel smart contract and produces GeoJSON-like entities in The Graph. Check out the GraphQL schema on [Github](https://github.com/Geo-Web-Project/geo-web-subgraph/blob/main/schema.graphql).
- We started a design refresh of our [Cadastre UI](http://geoweb.eth.link/). The plan includes some UX improvements &amp; styling updates, but most importantly we&#39;re integrating new functionality from our [updated smart contracts](https://github.com/Geo-Web-Project/core-contracts).

## Community Updates

- We&#39;re beginning to run user sessions feedback sessions to hone our beta product design. If you&#39;re interested in participating in a session, get in contact with us [@thegeoweb](https://twitter.com/thegeoweb) on Twitter. The DMs are open!
- We joined [@TheWIPMeetup](https://twitter.com/theWIPmeetup) for their meetup in [Cryptovoxels](https://www.cryptovoxels.com/) last Thursday. It gave us the chills being a part of the event. Yes, we&#39;re biased, but it felt like a glimpse of the future. There is so much creative energy going into NFTs, cryptoart, and VR metaverses like [Cryptovoxels](https://twitter.com/Cryptovoxels), [Decentraland](https://twitter.com/decentraland), and [Somnium Space](https://twitter.com/SomniumSpace). We love it all. We know there are going to be multiple game-changing ideas, products, and companies to come out of the space. We&#39;re excited about unleashing that same creative energy into AR and the physical world!
- [_Radical Markets_](http://radicalmarkets.com/) by Eric A. Posner &amp; E. Glen Weyl &amp; [Vitalik Buterin&#39;s related writing](https://vitalik.ca/general/2018/04/20/radical_markets.html) were our initial inspiration for using the SALSA system to administer our digital land market. The [RadicalxChange Foundation](https://www.radicalxchange.org/about/) is the awesome organization looking to make the principles and ideas proposed in this writing a reality. We enjoyed their livestream [&quot;](https://www.youtube.com/watch?v=QfWZK7pB938&amp;feature=youtu.be)[How Can We Do a Better Job Finding Common Ground in Politics?&quot;](https://www.youtube.com/watch?v=QfWZK7pB938&amp;feature=youtu.be) last Thursday. If you&#39;re into this kind of thing (and you should be), we recommend you check out their newsletter, [resources](https://www.radicalxchange.org/resources/), or [YouTube channel](https://www.youtube.com/channel/UCxRk8v1Wcxa1TIKTvqrtSOw).

## On Deck

- Begin implementation of the Cadastre UI updates including integration of the land parcel subgraph.
- Begin work on parcel licenses. A license allows users to link content to land and is represented as an NFT. See the [spec here](https://github.com/Geo-Web-Project/specs/blob/master/contracts/ERC721License.md).
