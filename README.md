API Network Protocol and Whitepaper
==========

API Network Protocol Version 0.1 (Whitepaper Proposal Edition)

=================================

**Contributors:**

Ian Stewart https://github.com/ianmstew

Marv Schneider https://github.com/marvgmail

Faiz Khan https://github.com/faizkhan00

Curtis Lacy https://github.com/curtislacy

Sam Yilmaz https://github.com/Onat


## Introduction
The market for API calls is enormous one, the number of API calls per day is astronomical. They power most of the Apps that you use on a daily basis, however they are still tough for developers to connect and maintain. The API Network project was born out a desire to make it easier for developers to connect to application programming interfaces (APIs). The team involved in the API Network has spent the last two years building out tools to make that process easier. The project has moved more and more toward open source until it became evident to be successful the project had to be 100% open source and incentives had to be built in with a crypto currency to reward developers who contribute their work and APIs to the network. The focus has since expanded to IMAP and related work to make this common source of data useful to most developers. 

So if you are a developer and want to easily access APIs and IMAP data? Join the API Network project. The API / IMAP / OAuth 2 / Email Classifiction Open Source Project for Developers.

##Alice and Bob Examples

EXAMPLE WITHOUT API NETWORK

1. Alice has an bitcoin to dogecoin exchange website. One of the features Alice offers is a price ticker from the trades being done on her order book. In theory Alice's price data feed is available as an API... somewhere, well maybe if you contact her directly and figure out how to use it.

2. Bob has a bitcoin and crypto currency charts website that shows real time prices for bitcoin and many other crypto currencies. Bob wants to add the price of of bitcoin to dogecoin to his website charts. Bob first has to survey the exchanges that trade bitcoin for dogecoin and find out who offers an API. Bob finds out that Alice offers the API he needs and reaches out to her. Bob connects with with Alice's API but it has many limits: only so many calls per hour can be made. So instead of real time data Bob's charts show a 20 minute delay. 

3. Later on Charlie, Dan, and Ethan want to connect to Alice's API too. But Alice doesn't want to support all the calls to her server or go to the trouble of setting up a payment mechanism and decides to shut off this service. Now Bob, Charlie, Dan and Ethan must go find another exchange offering an API for bitcoin to dogecoin trades.     

EXAMPLE WITH API NETWORK

1. Alice has an bitcoin to dogecoin exchange website. One of the features Alice offers is a real time price ticker from the trades being done on her order book which she has listed on the API Network.

2. Bob has a bitcoin and crypto currency charts website that shows real time prices for bitcoin and many other crypto currencies. Bob wants to add the price of of bitcoin to dogecoin to his website charts. Bob goes to the API Network and finds that Alice offers the API he needs. Bob uses the API for free for a while and later decides to pay a little API Coin to Alice for real time data and more calls to her service.

3. Later on Charlie, Dan, and Ethan connect to Alice's API through the API Network. Alice's API service becomes popular and she gets paid lots of API Coins, some of which she converts into bitcoin and uses the money to sustain and improve her API service over time. 

## The Problem
There are four central issues with today's providers of API calls:

1. Many of the most popular API's you can think of (Facebook, Twitter, Salesforce) have artificial limits on the number of API calls a developer can make to their system. This creates critical scaling issues and often breaks smaller applications that depend on these API calls when they reach these limits put in place by API providers.

2. Today, websites that provide a single interface for accessing multiple API's, there isn't any price competition for the API calls developers want to make and the central service takes a margin on top of its costs, so the price the developer (and his or her users) pay for convenience is a higher price per API call.

3. Singly.com as an example is a private centralized company, and so if it doesn't support the API you want, then its tough luck for you. Of course you can send in a request and maybe one day they will support it.

4. Lastly because these services are not open source, you can't see the back end of how their code is handling the data from the API to you. So you have a much simpler interface with less function possible.

## The Solution
The ideal solution one would want is: 

1. A marketplace where API providers compete on price and thus API providers can monetize their API as a service.

2. An open standard so anyone can add additional APIs to the interface that people want support for.

3. An open source view into how all the data is handled so that you can customize it for your application if you need a more powerful solution.

And once we build this open source marketplace for API's then we can build more powerful and less centralized versions of other services such as IFTTT https://ifttt.com/ and many other programs that provide value to end users by preforming tasks for them with API data in the back end.

Now imagine creating a competitive market scripts / agents that preform just about any action on the internet that a user can then easier find and use. Thats the longterm vision here.

## Summary of Features

We claim that API Network will 

* A. provide a platform for developers to easily access multiple APIs + IMAP.
* B. provide access to a wide variety of both private and public API's.
* c. provide access to the private and public API's in a federated manner for data that is technically easy to host and index, such as IMAP and Exchange information. 
* D. aquire initial backing as part of crowdsale to incentizive developers to build the API Network Protocol's software.
* E. operate using the "APICoin (XAP)" to grant access its service.
* F. compensate and incentivize nodes that are providing the API Network service in "APICoins (XAP)"

## Technical Assumptions

Our claims are built on the following technical assumptions of technologies the API Network Protocol relies on for implimentation:
* A. The Bitcoin Network can be used as a cryptographic ledger for the secure transfer of value and recording.
* B. The Master Protocol can provide the issuance of digital and unique tokens on top of the Bitcoin cryptographic ledger.
* C. The Safe Network can provide secure decentralized storage of data for the caching of API information.
* D. API Network Protocol can host and manage Bitcoin wallets in an automated manner as indicated by users.
* D. API Network Protocol can leverage digital marketplace tools such as decentralized escrow, reputation, identity, and arbitration to operate an efficent Federated marketplace for pulbic APIs.

## Visualization of the APIcoin Token Tech Stack

The proposed protocol layers of Bitcoin, Master Protocol, and the API Network can be visualized as follows, with arrows representing users exchanging between currencies:

![Mastercoin Protocol Layers](https://raw.github.com/mastercoin-MSC/spec/master/images/layers.png) 

Note that all transfers of value using the Master Protocol are still stored in the normal bitcoin block chain, but the protocol assigns, stores and interprates additional meaning to some transactions utilizing the feature of embedded metadata. See Master Protocol for more additional information on user issued currencies and hosting crowdsales.

# Document History

* Version 0.1
This version seeks to describe the features that will be implimented after the API Network crowdsale.

## Features of the API Network

1. Private API Marketplace: A node may join the API Network and publish a private API that it will provide calls for. The node will accept and price the calls to its API in API Tokens. This will establish a link between the value of the service and that of the tokens. While the demand for the service will reflect in the demand for the token, the market place of nodes opertaing to perform a variety of API calls will be competing with each other thus rendering the service cheaper to perform. The competing supply and the competing demand will give rise to the dynamic emergent market place.

2. The use of the SAFE Network: When the API Publisher stores information on the SAFE Network, the SAFE protocol will issue tokens to the Bitcoin address provided by the API publisher, to enable sustained storage and recall.

3. Storage of Cached API Data: The API Network will use SAFE Network in the back-end to store the cached API data for users. This will be accomplished through the conversion of API Tokens to SAFE coins to purchase storage space for the user in the decentralized exchange.

4. API Billing Module: The API Network will require sending of API tokens before the API services are provided, and the system will use AnArk.it for the escrow and holding of the API tokens for its billing module. That way the handling of the API tokens can be done in a completely decentralized manner where neither the user nor the API publisher will be able to access the API tokens until the promised action is preformed to the satisfaction of both parties.

5. Data Normalization: The API Network contains libraries and tools for the normalizatin of data. This tool set is open-source, available to all users of the API Network system, and will be maintined as part of the core implimentation of the API Network Protocol. 

6. IMAP Intergration: The API Network contains libraries and tools for the intergration of IMAP email systems. This tool set is open-source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol. 

6. Exchange Intergration: The API Network contains libraries and tools for the intergration of exchange email systems. This tool set is open-source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol. 

7. Single Developer Interface: The API Network contains libraries and tools for developers to interact with multiple API's through a single interface. This tool set is open-source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol.

8. Natural Language Processing Tools:  The API Network contains libraries and tools for the processing and indexing of natural language. This tool set is open source and available to all users of the API Network system and will be maintined as part of the core implimentation of the API Network Protocol.

9. Public API Marketplace: The API Network will provide a marketplace for public APIs (Gmail, Facebook, Twitter and so forth) to be accessed through a Federated Network of API hosting providers. This marketplace of public API's will provide access to reputation and identity systems (anark.it and onename.io for example) to allow users to pick the API call provider of their choice. The marketplace for public API's will leverage the API Network opensource data normalization, interface and natural language process tools. 

## Example of the Facebook API from Demo Website

From Demo Website https://docs.apinetwork.co/

The Facebook API for example gives the developer:

User Profile for {userID}

User's friends list

User's news feed

User's status feed

User's created events

User's group details

User's likes

Links shared by user

User's photos

Posts shared by user

Albums shared by user

User's notes

User's videos

Note: Of course the developer only gets access to this information if the user gives them access.

## Operating on Top of the Master Protocol

The “Master Protocol" layer exists between the existing bitcoin protocol and user-issued currencies. The software implementing the Master Protocol contains simple tools which allows anyone to design and release their own currency with their own rules without doing any software development.

## Total Distribution of APIcoins (XAP)

XBT (BTC) Crowdsale 3,000,000 XAPs (30%)

Third Party Developers 2,000,000 XAPs (20%)

Core Developers 2,000,000 XAPs (20%)

Open Sourcing 2,000,000 XAPs (20%)

Node Incentive 1,000,000 XAPs (10%)

Total APIcoins that will ever exist 10,000,000

**Notes:** 

See details on the following Google Spread Sheet: https://docs.google.com/spreadsheets/d/1Jo58sfAfXJ05ZUylzf9dGDbJ2ngPlDbCZ2B6FSP_xBc/edit?usp=sharing

These algorithms and rates of distribution here are approximations and will not be locked in until each category is defined by the community via a final distribution algorithm. 

For example the rate at which the third party developers XAP pool will pay out depends on the SAFE Network being able to provide the algorithm to track and reward the usage of a file on their system for the API Network to award its XAP tokens to its third party developers using the same methodology. See "Algorithms" section below. 

## Algorithms and Logic APICoin (XAP) Generation

The following sections define the algorithms and logic assossiated with the generation of each category of XAP.

## The Crowdsale “APICoin (XAP) Generation”

The API Network uses the Master Protocol to create a user currency identifer. These tokens are generated by the participants in the "API Address", a Bitcoin address starting June 18th 2014. The generation will continue until the end of the 'crowdsale' event until the target amount of API Coins (XAP) are sold or the ending date is reached.

Initial distribution of APICoins (XAP) will essentially be a effort to incentivize developers to write the software which fully implements the protocol. The issuance of tokens will proceed as the following simple steps:

1. Starting on June 18th 2014 at 11 AM U.S. Central time, anyone sending bitcoins to the "API Address" is recognized by the protocol as purchasing API Coins (XAP).

2. The first 500 XBT (BTC) sent to the "API Address" will generate 1 API Coin (XAP) for each 1.6 mXBT (millibits / 1/1,000th of a bitcoin). 

3. The next 1,000 XBT (BTC) sent to the "API Address" will generate 1 API Coin (XAP) for each 2.13 mXBT (millibits / 1/1,000th of a bitcoin). 

4. The next 2,000 XBT (BTC) sent to the "API Address" will generate 1 API Coin (XAP) for each 2.66 mXBT (millibits / 1/1,000th of a bitcoin).  

5. The last 4,692 XBT (BTC) sent to the "API Address" will generate 1 API Coin (XAP) for each 3.2 mXBT (millibits / 1/1,000th of a bitcoin). 

6. The details of the pricing of the API Coins (XAP) during the crowdsale event can be found on this Google Doc: https://docs.google.com/spreadsheets/d/1Jo58sfAfXJ05ZUylzf9dGDbJ2ngPlDbCZ2B6FSP_xBc/edit?usp=sharing

7. Attempts to send funds to the API "Address" on or after 11 AM (central time) July 18th 2014 (as determined by bitcoin block chain records), will not be considered APICoins purchases and shall be sent back to the originating Bitcoin wallets in the form of Bitcoin minus transaction fees.

8. The total number of APIcoins generated during the crowdsale shall be limited to 3,000,000. Any APIcoins generated after this point shall be invalid and the bitcoin sent for their generate returned to the sender.

9. If less than 500 XBT (BTC) are collected during crowdsale, then the post crowdsale purchase of MSC and MSAFE will be reduced or elimited based on the amount of MSC and MSAFE collected during the crowdsale.

**Notes:**

In the event that a purchase has multiple inputs, the input address contributing the most funds is recognized as owning the APICoins.

Anyone who purchases APICoins also receive the ability to test new features before they are available for use in the API Network Protocol.

If the full 3,000,000 APICoins (XAP) are not generated during the crowdsale event, the remaining portion will be generated and distributed to the participants of the crowdsale on a proportional basis. Meaning that if for example a purchaser brought 1 APICoin (XAP) for 1.6 mBTC during the first segment of the crowdsale, and the crowdsale sold 1,000,000 APICoins (XAP) (out of the possible 3,000,000) then all holders of 1 APIcoin (XAP) would gain 2 additional APIcoins (XAP) and in this example the purchaser would end up with 3 APIcoins (XAP).  

## Third Party Developer APICoins (XAP) Pool + Generation of Other Crypto Currency by the Network and its Distribution

When the SAFE Network completes its test net phases and launches into production, the Network will generate SAFE coins for those users that add content to the network. The SAFE coin reward is based on the amount of usage that content recieves on the network and is paid out to the bitcoin address of the person who provided the content. 

The API Network intends to use the SAFE Network to host its APIs and other content in a decentralized way and thus produce these SAFE coins. The SAFE coins generated by the use of API's published by the API Network on the SAFE Network will be sent to the API Network Foundation wallet in order purchase APICoins on the Master Protocol Decentralized Exchange. These purchased API Coins (XAP) will be sent on a regular basis to the holders of API Coins (XAP).

## Core Developer APICoins (XAP) Pool

For every 5 APICoin sold, an additional “Core Developer APICoins” will also be created, which will be awarded to the API Address slowly over the following years. These delayed API Tokens will ensure that the community can incentivize developers to increase the value of API Token by completing the features desired by users. The reward will be structured so that the distributed bounty system receives the tokens on a logarithmic scale: 25% of all the Dev API Tokens by one year after the initial sale, 37.5% by a year later, 43.75%  by the year after, and so on.

## Open Sourcing APICoins (XAP)

This pool of APICoins (XAP) will be generated after the completition of the crowdsale on July 18th 2014 or at an earlier date should the crowdsale generate the maximum 3,000,000 tokens before that time.

This allotment of XAP will be used to purchase intellectual property, specifically code related to APIs, IMAP, Exchange and other internet services that the API Network will integrate into its systems and subsequently open source to the community for further development.

## Node Incentive APICoins (XAP)

This pool of APICoins (XAP) will be generated based on the storage and other resources that nodes provide to the API Network for the operations of its clients. For example if a node stores the list of APIs and their providers and makes it available to the community based on the API Network's protocol then they would recieve a portion of this reward. The algorthm will be determined by the community at the time the client is implimented and available for nodes to provide this function. 

## Transferring APICoins

The transfer of APICoins (XAP) will is done through the Master Protocol client implimetations.

Note that the amount to transfer is accounted for in Lacys (hundred million Lacy's add up to make 1 APICoin) before it is stored, which allows for APICoins to be sent with the same precision as bitcoins (eight decimal places).

## Use of the XBT (BTC) from the Crowdsale Event

1. Buy the intellectual property and codebase to jump start the development of the API Network from Engine Inc. (website www.Engine.co) related to API and IMAP interfaces and then open source that code to the API community. Cost 900 XBT (BTC) (or a lower amount if less than 900 BTC is collected during the crowdsale) and 2,000,000 API Coins (XAP) to be generated at the end of the crowdsale event.

2. Buy additional intellectual property and codebase related to Exchange and other common data standards and open soure it the API community.

3. Buy crypto currency in the protocols that API Network is built on top of. For example after the purchase of intellecual property and code from API services as described above, 25% of the remaining XBT (BTC) collcected during crowdsale will be used to purchase MSC, SAFE, and any other digital token that it functions on top of in order for the API Network to hold a stake in the platforms it is built on top of. Thus holding a mix of XBT (BTC), MSC and SAFE provides the API Network with a longterm stake in the future of these protocols.
 
4. Engage core developers to work full time to impliment the API Network protocol into a functional client. The Role Based Bounty system will be engaged to accomplish this.

5. Engage community members in bounties and challenges build up the number and type of APIs available on the API Network.  

6. The management of the XBT (BTC) contributed during the crowdsale will be done by the Non Profit API Network Foundation (until such time as the tools exist to decentralize its functions as decided by the community). The Foundation Board of Directors will be made up of volunteers from each of the five token distribution pools including a volunteer who participated in the crowdsale, a volunteer who is a third party developer, a volunteer who is a core developer, a volunteer who was involved in the propriatary code that is being open sourced, and a volunteer who is running a API Network node.  

##Appendix Disclosures

Disclosures PLEASE READ

1. Friendly Report: 
Those involved in preparing this informational report were among the co-founders and advisors of Engine Inc. in 2012 (the original API effort that was proprietary and is now being open sourced) and the views expressed here (while intended as neutral), should be taken as friendly to the project and its success.

2. This Is Not Stock or Equity
Participation in the API Network / XAP crowdsale will not provide you with a "security" or "equity" stake in this project. The digital token known as XAP is only useful for accessing the API Network software after its development is complete.

3. No Refunds
No refunds of BTC will be made to purchasers of XAP, should they change their mind at a later time, as the creation of the XAP tokens is locked in. Of course, once the purchaser receives his or her tokens after the crowdsale, they are free to send or sell them to anyone of their choice.

4. If You Send BTC From Coinbase You Can't Claim Your XAP
If you send the API Network Crowdsale address BTC from a wallet that you do not control the private key for (example Coinbase), then you will not be able to claim the API Coins (XAP) you purchased and the API Network will be unable to generate new ones for you.

5. Low Liquidity / Ability to Sell These Digital Tokens Will Be Limited
If you purchasing token XYZ in order to hold it as "a store of wealth or value" please understand that this project is in its early days of development and that the market for these tokens will be very shallow and thus make it will be harder to buy and sell these tokens without effecting the price on the market.
