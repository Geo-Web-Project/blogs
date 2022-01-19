# Open + Accessible: Weekly Update #57

https://www.geoweb.network/post/weekly-update-57

Openness is required, but not sufficient for the world we want to build. Plus updates from the last week on the Geo Web project (1/13/2022 - 1/19/2022).

## Open + Accessible

I&#39;ve been working through taxes and year-end finances the last couple weeks for the Geo Web project. Two things keep coming to mind:

1. I can&#39;t wait for the day that we give up the reins to the project (to the community and code), and there isn&#39;t a centralized entity which regulators and tax authorities would deem &quot;in charge.&quot;
2. All this _open_ data sure is hard to make use of.

99% of our financial transactions for the project have been on chain. The challenge is that they&#39;re spread out across ETH mainnet, zkSync, Gnosis Chain (formerly xDAI), and Polygon. And there&#39;s quite a few transactions thanks to the generosity of our community on our [Gitcoin Grant](https://gitcoin.co/grants/1403/geo-web)!

Each network is public and even has a hosted block explorer, but each has its own quirks. The data is there, but it&#39;s just not easy to get it into the format and context needed.

There&#39;s too many crypto tax software companies to count that are built on this fact. They&#39;ve each built closed-source integrations with exchanges, wallets, and blockchain networks which make this open, public data easier to use—_for a fee_.

(Note: I didn&#39;t find a single zkSync integration, so I used this [OS repo which could use some love](https://github.com/benjaminion/zksync-csv-export). I found only one mention of plans to integrate xDAI. In the fierce battle for L1/L2 users, this seems like an underappreciated competition vector for the network builders).

This pattern of for-profit/closed-source business models that offer convenience and accessibility on top of open data/standards isn&#39;t unique. It&#39;s seen all over Web 2.0. Web pages are open and free. Google has become one of the most valuable companies in the world by leveraging that open data (and sucking up as much private data as they can) then making it more accessible…but under their terms. Last I checked, repeating that cycle isn&#39;t the vision for the future that most web3 enthusiasts have in mind.

I&#39;m not here just to whine about unmet idealism though. It requires hard work to build and maintain these types of tools/services that make open data and standards accessible. That&#39;s why public goods funding is so important. That&#39;s why new crypto-enabled business models that better align user and builder incentives are so important.

So as I look forward to this year on the Geo Web, accessibility will be one of our key themes. As a value-based project, we can&#39;t just settle for &quot;we made it open-source&quot; and let the chips fall where they may. We can do a better job of making all that we do operationally and technically not just open, but accessible. As we transition into a net provider of public goods funding, we can propagate that priority throughout the Geo Web ecosystem and web3.

## Technical

- We&#39;ve started implementing of our new streaming network fee and auction setup ([CollectorSuperApp](https://github.com/Geo-Web-Project/garden/blob/main/content/notes/Draft%20Proposal%20-%20CollectorSuperApp.md),[ETHxPurchaser](https://github.com/Geo-Web-Project/garden/blob/main/content/notes/Draft%20Proposal%20-%20ETHxPurchaser.md), &amp;[SimpleETHxClaimer](https://github.com/Geo-Web-Project/garden/blob/main/content/notes/Draft%20Proposal%20-%20SimpleETHxClaimer.md)). We&#39;re utilizing [Superfluid](https://www.superfluid.finance/home). The contracts are open-source, so we&#39;re excited to get a streaming partial common ownership/Harberger tax implementation out there that others can leverage. 2022 is going to be the year of Harberger tax applications.
- We&#39;re also experimenting with 3D model anchoring to Lat,Long coordinates in a Geo Web parcel. The Geo Web isn&#39;t a monolithic app, so we&#39;re excited to put out more experimental use cases that the community can fork and remix this year. This use case in particular will hammer home the impact of the persistence of digital objects in the real world.
- Our core contracts are deployed on the testnet which we hope is our long-term L2 network home…

## Community

- [ETHDenver and BUIDLWeek](https://www.ethdenver.com/) (2/11-2/20) is quickly approaching! If you haven&#39;t [applied](https://www.ethdenver.com/apply), do so ASAP and start planning your travel. We&#39;ll be there all week and would love to meet up with any community members. Hit us up in [Discord](https://www.ethdenver.com/apply)—I&#39;ll buy you a drink of your choice (beer, coffee, tea, kombucha, whatever) there!
- Help us increase our matching from the Panvala League by [staking PAN to the Geo Web (no gas, no loss tx)](https://panvala.com/staking/)! You can swap for some[PAN on Uniswap](https://app.uniswap.org/#/swap?outputCurrency=0xd56dac73a4d6766464b38ec6d91eb45ce7457c44&amp;use=V2) if you don&#39;t have any yet.
- As the [proposal authors Dave White &amp; Kevin Owocki admit](https://twitter.com/_Dave__White_/status/1481406113404780544?s=20), [Gitcoin Aqueduct](https://gov.gitcoin.co/t/gitcoin-aqueduct/9684) is still in its early stages, but count us interested. I&#39;ll call it QFaaS (quadratic funding as a service). We&#39;ll be keeping an eye on this as a potential tool to effectively distribute Geo Web network funds. We always planned to utilize quadratic funding rounds for our ecosystem, but this can help pull forward the timeline.

## On Deck

- Point-anchored AR content demo
- Streaming network fees &amp; bid matching auctions
