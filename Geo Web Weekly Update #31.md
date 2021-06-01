# AR Platform Wars: Weekly Update #31

https://www.geoweb.network/post/weekly-update-31

How will our augmented, future reality be delivered? Plus updates from the last six days on the Geo Web project (5/27/21 - 6/1/21).

## AR Platform Wars

Pervasive augmented reality experiences are inevitable.

Our world is getting more and more digital. Digital content will eventually cross a threshold of fidelity and depth that our brains will perceive as &quot;real.&quot; Digital content will be used side-by-side with physical objects to enhance reality because we&#39;re quite a ways off from completely opting out of the physical world.

The enabling technologies and platforms that enable this are TBD. We have our hypothesis on the Geo Web, but it&#39;s also helpful to examine the alternative solution types that will define this future.

There are several high-level attributes that we can categorize potential solutions on:

1. Proprietary vs open
2. Hardware vs software-centric
3. Natively isolated vs shared

I don&#39;t have an implementation example for each of the eight attribute combinations, but let&#39;s explore a few of the most likely ones:

### Open, software, shared

Let&#39;s start with the attributes that we think best deliver the promise of augmented reality (and naturally define our project). We believe that a system based on open standards, scalable, composable software, and shared reality experience will be the defining platform for AR. These attributes capture the power of information sharing and credibly neutral opportunities for billions to outcompete the alternatives. The biggest challenges are coordination related (classic tragedy of the commons or prisoner&#39;s dilemma problems). Our implementation (Harberger-administered land) helps overcome coordination challenges and accentuates the value of open-source software and public goods with direct economic incentives, but other &quot;consensus mechanisms&quot; are possible.

**Example:** Geo Web

**Strengths:** Legitimacy, scalability, compounding effects of information sharing

**Weaknesses:** Jumpstarting network effects, Moloch (God of Coordination Failure)

### Proprietary, software, isolated

We talk a lot here about the app store model that defines our smartphone usage. The companies behind the most popular operating systems will continue to try to exert control over and profit from the externally developed content, tools, and applications that actually make their hardware valuable. Directly translating the current app model to augmented reality will create more isolated experiences; each smartphone owner controls their own reality. There will continue to be a place for this type of experience, but alternatively ceding a few individual degrees of freedom would actually result in new, more valuable AR experiences.

**Example:** App Stores

**Strengths:** Incumbency, centralized funding, easy implementation

**Weaknesses:** Walled garden, lack of credible neutrality, political/social backlash

### Proprietary, software, shared

This category feels like shoehorning the previous category into the next (spatial) computing paradigm. Apple didn&#39;t announce [App Clips](https://developer.apple.com/app-clips/) and [AirTags](https://www.apple.com/airtag/) as AR-focused products, but it&#39;s easy to extrapolate these offerings to triggering/coordinating content and experiences for a group of people within a defined location. This starts to tap into the power of shared, concurrent AR, but unless we end up with a 100% monopoly in this space, it&#39;s unlikely a proprietary solution would aggregate into a single augmented reality.

**Example:** App Clips, AirTags

**Strengths:** Physical landowner control, incremental innovation

**Weaknesses:** Interoperability across OSs, technically discrete experiences

### Proprietary, hardware, shared

Up to now, I&#39;ve focused just on headset-based experiences. The big challenge is coordinating those individual headsets to create shared experiences. Hologram-like solutions offer a completely different model. If a piece of hardware projects 3D images so that everyone can see them, coordination is moot. Holograms are a big technical challenge, so they&#39;ll likely roll out as proprietary, integrated solutions first. There could be long term limits/drawbacks to projections as well. If holograms evolve into an open, democratized technology, I&#39;d take this solution over proprietary software models any day.

**Example:** Holograms

**Strengths:** Physical landowner control, easy &quot;coordination&quot; for viewers

**Weaknesses:** Lack of standardization, information sharing, cost/redundancy if everyone is wearing smart glasses

### Open, hardware, shared

Beacons or hardware with short-range, peer-to-peer communication (e.g. Bluetooth) have been around for years and could develop into AR coordination devices. They&#39;d need to directly communicate with all of the various smart glass OSs &amp; models. Creating universal, robust standards will be a tough hill to climb with the hardware vendors favoring their proprietary solutions.

**Example:** Bluetooth beacons

**Strengths:** Physical landowner control, local p2p communication

**Weaknesses:** Proprietary favoritism, security model, lack of global information sharing

### Open, software, isolated

Run back the Apple App Store and Google Play Store, but in a decentralized/open model. NFT marketplaces like Rarible, OpenSea, and SuperRare could develop into full-fledged application stores and complement shared AR experiences (like the Geo Web) nicely. Competition from non-OS controlling corporations (Snap, Facebook, or Microsoft) could open the door for competition from another angle as well.

**Example:** NFT marketplaces

**Strengths:** Credible neutrality, open innovation, incremental innovation

**Weaknesses:** Content curation (in practice and expectations), sustainable network effects?

### ~~Open, hardware, isolated &amp; Proprietary, hardware, isolated~~

Not sure what these would look like. Ideas?

On to the updates…

## Technical

- Spatial Browser cleanup ([https://github.com/Geo-Web-Project/browser/pull/13](https://github.com/Geo-Web-Project/browser/pull/13))
- New [Geo Web Architecture](https://docs.geoweb.network/developers/architecture) &amp; [Smart Contract](https://docs.geoweb.network/developers/smart-contracts/erc-721-license) overviews ([https://github.com/Geo-Web-Project/docs/pull/7](https://github.com/Geo-Web-Project/docs/pull/7))
- Research &amp; design for provisioned pinning &amp; archival storage (IPFS &amp; Filecoin). We&#39;re looking at provisioning storage per land parcel with the land parcel as the controller of the allocation via [IDX](https://idx.xyz/) &amp; [NFT DID method](https://github.com/ceramicnetwork/nft-did-resolver)

## Community

- Is it going to be &quot;L2 Summer?&quot; We sure hope so! We&#39;re deep into research and evaluation for the L2 network which the Geo Web will launch. [Offchain Labs](https://offchainlabs.com/) announced the [launch of their beta Arbitrum One mainnet last week](https://offchain.medium.com/introducing-arbitrum-one-our-mainet-beta-ed0e9b63b435). Matter Labs updated the world on [their progress with zkSync 2.0](https://medium.com/matter-labs/zksync-2-0-hello-ethereum-ca48588de179). Their alpha testnet is live. We have one optimistic and one ZK roll-up solution close to their respective finish lines. [Optimism](https://optimism.io/) is still targeting July for public release the last we heard. Congrats and godspeed to these teams!

## On Deck

- Experimentation with Arbitrum mainnet
- Provisioned storage prototype 2.0
- Moar docs
