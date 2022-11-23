---

<center>
<img width="50%" src="https://monero.shopping/MoneroShopping-Logo.png" alt="Monero-Logo">
<br>

## [Monero.Shopping](https://monero.shopping)
### Monerotize the World!
</center>

---

### 💡 The Idea
You surely heard this one: 
>"Yeah, Monero is nice but what can you actually buy with it?"

#### Presenting [Monero.Shopping](https://monero.shopping):
- A universal Monero-Checkout for the whole internet!
- Use Monero on almost any marketplace on the Internet!
- Buy multiple products from multiple Vendors at once! 
- Complete privacy!
- No registration
- No KYC
- A ProxyStore on steroids!

1. Monero.Shopping is a service that allows you to send in a list of product from one or multiple supported vendors and pay for it with one convenient and private Monero Payment.
2. Monero.Shopping also allows you to buy/sell gift cards, from supported vendors, using Monero.

Monero.Shopping introduces Monero to a wider, non-technical audience and has the potential to turn into a "weapon of mass adoption".

#### Order process:
1. User provides a list of Products and shipping address
2. A Monero Invoice is provided to the User
3. After payment, Monero.Shopping fulfills the order and provides tracking numbers

#### Gift cards:
Users can sell and buy gift cards, from supported Vendors, with Monero.


##### Spend Monero on a ever-growing list of Merchants/Stores/Services/Marketplaces:

| Spend Monero on: |  |  |
| ------------ | ------------ | ------------ |
| Amazon| Apple |Google |
| Netflix | Ebay |  Playstation |
| Just Eat | Zalando | Uber |
| Hotels.com |Bol.com | Target |
| Walmart | Rewe | Aldi |
| AirBnB | IKEA |Media Markt |
| Nike | Alibaba | and many more... |

---

### 🛠️ How do we build Monero.Shopping?

#### Stack
- No Frameworks
- No bloat
- No proprietary code
- Pure HTML/CSS and vanilla JS(if needed) on the front end
- hosted on GitHub at the moment, will eventually be moved to self hosted Git and IPFS

#### Invoice Generation
- a script that goes through every provided URL and gets the Price of all products
- the prices+fees are added up and a monero address is generated and send/displayed to the customer
- Community Projects could be utilized:
  - [Metronero checkout](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/353) by @sausagenoods
  - [moneropay](https://moneropay.eu/)

#### Order fulfillment
- Will be done manually/semi automated in the beginning
- Hard to automate
- Right now we are looking at solutions with APIs from vendors and exchanges and browser automation tools like [Selenium](https://www.selenium.dev/)
- any input on how to achieve this is welcome!

#### Privacy
Monero and Gift cards already provide great privacy.
The only identity revealing information is the shipping-address of the Client.

A possibility should be research to anonymize the address.
- This feature could be groundbreaking and open the door for making Monero.Shopping decentralized
  - User could fulfill orders for other users
  - A bit like [TornadoCash](https://en.wikipedia.org/wiki/Tornado_Cash) but for marketplace orders

#### Escrow
- Escrow should be done by including established people from the Monero community
  - The Monero CCS team is already running a Escrow service
  - The Monero CCS team should be asked to provide, overlook or assist in a Escrow-Service for Monero.Shopping
    - A Monero Escrow could be crowdfunded through the Monero CCS
    - A Monero Escrow could be build into a standalone Service
  - Being backed by an officially Monero-Escrow would give Monero.Shopping instant credibility and build client-confidence

#### Similar projects to learn from:
- https://order.proxysto.re/
  - This is a proxystore that operates out of and only in Germany
  - This Project is perfect to learn from and proves the viability of the Idea behind Monero.Shopping
  - The feature of the numbered accounts without the need for registration should be adopted. ([mullvad](https://mullvad.net) has a similar system)
  - We should reach out to them:
    - ask for advice and insight into running a business like this
    - ask them for recorded video call/interview
      - they can present their service 
      - talk about their experience with running a service like this
      - ask [Monero Talk](https://www.monerotalk.live/) to do the Interview
    - present them with the Idea of Monero.Shopping and ask their opinion
    - consider partnering up so they could deal with the fulfillment in Germany and maybe EU.

---

### 💰 ~~Chashflow~~ Moneroflow
There are 2 main "revenue/asset streams"

1. Fees from Order-fulfillment
2. Gift cards
   - Users can sell git cards for Monero
   - Users can buy gift cards with Monero

No fiat handling!
Monero.Shopping operates without the use of fiat currency, the only assets controlled by Monero.Shopping is a Monero wallet and a database of Gift-card-Codes.
No need for a Bank/Stripe/Paypal -Account, which is a huge time/labor/bureaucracy saver and makes Monero.Shopping more independent and less bloated.

#### Ordering Product:
1. User transfers Monero to Monero.Shopping
2. Monero is exchanged for other cryptocurrency's 
3. Gift cards for the specific vendors are purchased
4. The order gets fulfilled

Gift Cards are used to order Products from vendors by utilizing services like:
- [coingate](https://coingate.com)
- [coinsbee](https://www.coinsbee.com/en/)
- [bitrefill](https://www.bitrefill.com)
- [egifter](https://www.egifter.com/)
- [tillo](https://www.tillo.io)
- [bitpay](https://bitpay.com)

Monero.Shopping will not hold any fiat which is a huge time/labor saver.
The only assets controlled by Monero.Shoping will be a Monero wallet and a list of gift card codes.

---

### ⚖️ Legal

- The Legal setup of Monero.Shopping is still being discussed. 
- To avoid costly and time consuming audits, licensing, authorized capital as stated by @sausagenoods we would aim to register Monero.Shopping as a E commerce-Service-Provider.
- Any advice and suggestions are welcome! 

---

### 📣 Marketing/Outreach/Partnership
The main "selling point" of Monero.Shopping is not Monero itself, its privacy which should be reflected in marketing campaigns.
The biggest potential we see here is the fact that this service could bring people to Monero who are not even into Crypto, just by being more convenient to use, providing privacy and eliminating the hassle to register on every Marketplace/Vendor.

#### Buzzwords:
- One Storefront for the whole internet!
- Protect your data from big tech!
- No registration!
- No KYC!
- Monerotize the World!

We count on organic grow and want to build a service that people are excited to share so we don't rely on expensive marketing campaigns.

Monero.Shopping will be shared on the following channels/websites to get to people that are already familiar with Crypto/Monero:
Suggestions are always welcomed!

#### Websites/Platforms/Directories:
- [xmr.market](https://xmr.market/)
- [/r/Monero/](https://www.reddit.com/r/Monero/)
- [monero.observer](https://monero.observer)
- [cryptwerk](https://cryptwerk.com)
- [kycnot.me](https://kycnot.me/)
- [acceptedhere](https://www.acceptedhere.io/) - seems to be offline
- [medium](https://medium.com/)
- [dev.to](https://dev.to)

#### Conventions:
- [Monerotopia](https://monerotopia.com/)
- [Monerokon](https://monerokon.com/)

#### Influencers/"Content Creators"
- [Luke Smith](https://lukesmith.xyz/ "Luke Smith")
- [MentalOutlaw](https://odysee.com/@AlphaNerd:8 "MentalOutlaw")
- [DistroTube](https://distro.tube/index.html "DistroTube")
- [Monero Matheo](https://odysee.com/@MoneroMatteo:b "Monero Matheo")
- [NetworkChuck](https://networkchuck.com/ "NetworkChuck")
- [Monero Talk](https://www.monerotalk.live/ "Monero Talk")
- suggestions are always welcome

#### Video Ads:
We plan to produce 2 different Video Ads:
- One rather generic and simple explainer video to attract the "average consumer"
- One with more of a anti establishment messaging, there is the risk to "scare" the "average consumer" but would probably resonate with younger audiences
- @monerobullgitlab should be asked to produce another banger explainer video like [this](https://www.youtube.com/watch?v=QYfUSImvRnQ)

#### Possibility of a Partnership/API use:

- Proxystores:
  - [order.proxysto.re](https://order.proxysto.re/)

- Exchanges:
  - [trocador](https://trocador.app/en/)
  - [tradeogre](https://tradeogre.com/)

- Gift Card Sellers:
  - [coingate](https://coingate.com)
  - [coinsbee](https://www.coinsbee.com/en/)
  - [bitrefill](https://www.bitrefill.com)
  - [egifter](https://www.egifter.com/)
  - [tillo](https://www.tillo.io)
  - [bitpay](https://bitpay.com)

---

### ❤️ Philosophy

We believe that privacy is the next big market that will explode in demand and monero will be crucial in meeting this demand! 
A demand that cant be met by "the establishment", an open field... THE opportunity of this generation!

- We are here to build reliable and open solutions for the Monero Ecosystem.
- We have ambitions that go beyond Memes, middle fingers and edgy humor towards the "establishment" 
- We are not here to destroy the old system, we are here to BUILD a better one!
- We don't operate on aggression but on COMPASSION!

#### Why Monero?
- Monero is the most advanced and proven privacy tool out there and will be the basis for Monero.Shopping!
- We chose Monero not for its memes and funny art (although some are certainly enjoyable, some of them very creative and a great way to create interest in Monero) 
- We chose it because we see it as one of a few beacons of hope, in a crumbling crypto/banking landscape.
- We build with and for Monero because we want to be part of building a future that we want to be part of.

---

### 🤝 Team

All of us!
Different people with different skills united by an Idea!

Everyone is welcome to join the [disccusion](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/360) or [development](https://github.com/MoneroShopping) of Monero.Shopping!

Any surplus, raised or earned by Monero.Shopping will be shared with all major contributors.

Stay anonymous! 🥷

---
