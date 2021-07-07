# State of the Spatial Browser: Weekly Update #36

https://www.geoweb.network/post/weekly-update-36

Walking through the alpha Spatial Browser plus updates from the last week on the Geo Web project (6/30/21 - 7/6/21).

## State of the Spatial Browser

An alpha version of our Geo Web Spatial Browser has been live for a few weeks. I wanted to walk through some of the features, limitations, decisions, and future possibilities for spatial browsing.

If you haven&#39;t used it yet, go claim your current location on the [Cadastre](https://cadastre.geoweb.eth.link/) and open the [browser](https://browse.geoweb.eth.link/) on your smartphone.

The first big item to note is that the spatial browser is a web app. We did this for practical and philosophical reasons.

From a practical standpoint, it&#39;s great not to require an app download for someone to try something experimental. We also get some limited cross-device compatibility right off the bat (mobile OS limitations bubble up into web browsers too).

On the philosophical side, we talk a lot here about our issues with app stores/mobile OSs being opposed to the open internet… So yeah. Eventually the spatial browser will need to be a native application to tap into additional capabilities, sensors, and APIs, but hopefully (or necessarily) there will be foundational changes to app store rules along the way.

Even as a native app, Geo Web spatial browsers should be thought of in the context of Chrome, Safari, and Firefox (general purpose, open information) rather than Pokemon Go (siloed use case, closed). Many don&#39;t think twice about the difference, but for the Geo Web vision the difference is night and day.

As for the alpha browser, it has two basic experiences: a web content view &amp; a 3D media gallery.

The web content view uses an iframe to display traditional websites. This mode swaps the URL bar for GPS as the navigation mechanism between websites.

A restaurant could link their menu and mobile ordering, retail stores could show their sales promotions page, parks could anchor maps, etc. Visitors don&#39;t need to know or search for the links. Their location is the only context needed to browse. The idea here is to provide the simplest publishing and browsing experience possible by leveraging existing/familiar content.

The media gallery is like a 3D and augmented reality photo album. It uses [Model Viewer](https://modelviewer.dev/) which enables 3D model views on modern web browsers and AR views on Safari (on iOS+ARKit) and Chrome (Android+ARCore). Again simplicity is the key.

This mode doesn&#39;t have the persistence and effortless UX that we&#39;ll eventually deliver with geopoint-anchored content (think of a photo album vs a wall painting).

The blank canvas of spatial browsers will eventually be the physical world seen through an always-on lens and heard through headphones/speakers. We&#39;re not there yet, but we&#39;ll get there.

On to the updates...

## Technical

- Completed work to use Cloudflare workers for content pinning ([https://github.com/Geo-Web-Project/storage-workers/pull/1](https://github.com/Geo-Web-Project/storage-workers/pull/1) &amp; [https://github.com/Geo-Web-Project/storage-workers/pull/2](https://github.com/Geo-Web-Project/storage-workers/pull/2))
- Integrated [Tiles](https://tiles.ceramic.community/) to provide a detailed view of a land parcel&#39;s Ceramic Stream ([https://github.com/Geo-Web-Project/cadastre/pull/58](https://github.com/Geo-Web-Project/cadastre/pull/58))
  - Congrats to the Tiles team on [going live on Ceramic mainnet](https://blog.ceramic.network/tiles-a-browser-for-open-source-information/)!
- We added secondary domain names for both the Spatial Browser ([geoweb.app](https://geoweb.app/)) and the Cadastre ([geoweb.land](https://geoweb.land/)) that are shorter and a little more &quot;approachable&quot; than our .eth links. Both sets will stay active and point to the same applications, so it&#39;s just personal preference.

## Community

- Is Web 3.0 ahead or behind [this relative point of maturity from Web 1.0](https://www.youtube.com/watch?v=U_o8gerare0&amp;t=2s)? Seriously, check out that video. It&#39;s really fun to see the common threads and values from this early age of the internet that continue today.
- I&#39;m not fully caught up on [this series](https://www.matthewball.vc/the-metaverse-primer) from [Matthew Ball](https://twitter.com/ballmatthew) yet, but if you&#39;re interested in the Geo Web, you&#39;ll be interested in Matthew&#39;s takes on the Metaverse. He&#39;s gained a reputation as &quot;The Metaverse Guy&quot; and he&#39;s started going down the crypto rabbithole...

## On Deck

- Finish additional wallet integrations on the Cadastre
- Finish our updated storage integration (IPFS pinning &amp; Filecoin archive)
- Exploring one version of a markerless tracking system for the Geo Web browser
