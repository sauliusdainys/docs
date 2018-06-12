# **K2N.IO - White Paper**

## Smart Data Platform for Decentralized Apps

**Build, deploy and run smart, data rich &amp; dynamic DAPPs**

# _Author_

 [http://k2n.io](http://k2n.io)
 [https://www.linkedin.com/in/amavashev/](https://www.linkedin.com/in/amavashev/)
 [info@k2n.io](mailto:info@k2n.io)

# Disclaimer

Copyright © 2018 MAVA STRATEGIES, LLC.

Without permission, anyone may use, reproduce or distribute any material in this white paper for non-commercial and educational use (i.e., other than for a fee or for commercial purposes) provided that the original source and the applicable copyright notice are cited.

This K2N.IO Technical White Paper v1.0 is for information purposes only. K2N.IO does not guarantee the accuracy of or the conclusions reached in this white paper, and this white paper is provided &quot;as is&quot;. K2N.IO does not make and expressly disclaims all representations and warranties, express, implied, statutory or otherwise, whatsoever, including, but not limited to: (i) warranties of merchantability, fitness for a particular purpose, suitability, usage, title or noninfringement; (ii) that the contents of this white paper are free from error; and (iii) that such contents will not infringe third-party rights. K2N.IO and its affiliates shall have no liability for damages of any kind arising out of the use, reference to, or reliance on this white paper or any of the content contained herein, even if advised of the possibility of such damages. In no event will K2N.IO or its affiliates be liable to any person or entity for any damages, losses, liabilities, costs or expenses of any kind, whether direct or indirect, consequential, compensatory, incidental, actual, exemplary, punitive or special for the use of, reference to, or reliance on this white paper or any of the content contained herein, including, without limitation, any loss of business, revenues, profits, data, use, goodwill or other intangible losses. K2N.IO reserves the right to make changes to this white paper without any notice.

# Introduction

Explosion of digital smart contract platforms such Ethereum, EOS.IO, NEO, NEM, WANCHAIN and others introduces a unique set of challenges for DAPP developers. These platforms are based on a decentralized, permission less, trust less model where anyone can develop and deploy decentralized applications (DAPPs aka smart contracts).  While in theory smart contracts allow execution of business logic on the blockchain, their actual use is currently limited to a few simple use cases such as:  a token of value which can be transferred to someone else (e.g. a digital token).

**Building smart, data rich &amp; dynamic DAPPs requires access to secure, accurate, high fidelity data lakes &amp; streams which can be accessed via push (pub/sub) and pull (request/reply) methods.** Such data streams are currently available via Web APIs using request and reply calls. Data streaming via publish subscribe becomes a key ingredient for the next generation of dynamic, data rich DAPPs.

DAPP developers should be able to write, query, access data via PUSH and PULL, select payment and terms of service using digitally signed data contracts. This allows maximum flexibility for DAPP developers such as:

- Write to external data lakes (data repositories or databases)
- Query and select required Oracles
- Select data access and terms of service
- Agree on terms of payment
- Run data aggregations and computations
- Receive call backs when data or computation is ready to consume
- Audit and analyze data streams historical and real-time

**K2&#39;s mission is to provide a data integration platform which makes it easy to develop, deploy and run secure and auditable data rich DAPPs**. K2 is not just an Oracle with publish/subscribe – it is a data marketplace where DAPPs do &#39;data shopping&#39; and data providers can monetize their data – Data as Service (DaaS).

K2 also opens conduits for integration and growth of both on-chain and off-chain eco-systems (private and public) such as:

- Bridge existing data silos with decentralized, crypto ecosystem
- Quickly expose your data stash without lengthy and expensive integration effort
- Provide rich and dynamic data feed for DAPP developers
- Create data channels between off-chain and on-chain world
- Allow non-crypto data providers (companies) partake in the blockchain ecosystem
- Democratize data by allowing it to be traded and monetized in a consistent fashion
- Quickly integrate your DAPP with any Oracle using a single consistent interface
- Write data off-chain to an external data lake
- **Run off-chain data computations, analytics and pipe results back into your DAPPs**

# Challenges

## Data Marketplace

DAPPs must be able to buy and sell data just like buying and selling commodities or products in a store. This requires a digital market place where data can be bought and sold at prices determined by free market forces. DAPPs should be able to query and select various data sources by topic, price, rating and other attributes, execute a data contract and obtain data streams all using digital channels and verified by the underlying blockchain (such as ETHEREUM).



This model makes it easy to get data and computations into any smart contract without complex development and integration. DAPPs can simply query the data marketplace and source in data on the fly using a consistent programming model across all data sources. The relationship between DAPP (consumer) and Oracle(s) is managed by Smart Data Contract (SDC) which defines the rules of engagement, terms of service &amp; cost structure.

There are instances when DAPPs may want to write data to an external data store (Data Lake). Data marketplace allows DAPPs not only to query data sources but also record data that may not be appropriate on-chain.

## Unpredictable Cost Structure

Data consumers want a predictable cost structure, while data providers a predictable revenue model. How do you price services when token&#39;s value may fluctuate dramatically on the open market? One of the goals of the K2 ecosystem is to introduce a stable cost structure via a K2 token, where costs are pegged to something external such as USD, EUR, gold, etc. and actual price of K2 tokens fluctuates dynamically based on a market exchange rate. This dynamic data pricing model ensures consistent cost and revenue model within K2 ecosystem.

## Data Delivery Modes

DAPPs must be able to query as well as subscribe to various Oracles (data feeds).  The first model is based on request/reply mode where DAPPS makes a request for a specific data element and receives a response (PULL method). Subscription model is based on a push method where data source pushes data directly into the DAPPs based on parameters specified in the smart data contract (SDC). This could be done based on time interval or &quot;as available&quot; basis. See SDC for more information.

## Scalability

Current decentralized blockchain implementations have serious scaling limitations, where processing is measured in &lt; 1000 transactions per second which is miniscule in world of big &amp; fast data.  Smart data ecosystem must be able to deliver rates of many orders of magnitude higher in order to satisfy growing demand for data across all types of applications including DAPPs. High data rates simply cannot be accommodated by today&#39;s public or private blockchain implementations and therefore requires a Layer 2 (off-chain) data pipeline which serves as a &quot;fuel&quot; for the smart economy.

## Data Security &amp; Privacy

Fundamentally smart contracts require data from trusted sources which can be proven to come from such sources. This can be achieved by using cryptographic proofs and end to end encryption, however such proprietary data sources make this task difficult and often impossible.  Currently there is no consistent way to verify what data sources are being used by a given DAPP, how these data source are secured and validated. What happens when a smart contract executes business logic based on compromised data?

All data in K2 is encrypted by Oracles and validators which verify and sign each data frame.  Each subscriber can independently verify 1) data comes from authentic Oracle and 2) validated and verified by a given set of validators. The contents of the data can be optionally encrypted to ensure end-to-end security and privacy.

## Data Access

How do smart contracts access data in the real-world? Accessing data such as stock, insurance, weather, sensor, energy across variety of various providers is a huge problem. They must have a consistent interface to data in real-time. Such data must also be available historically for DAPPs that base their decisions on past history. The interface must be consistent regardless of which data source is being accessed. Imagine having to code 10-20 interfaces into your smart contract? This is a huge integration challenge.

## Data Accuracy

How do you build a smart contract on fresh, secure and accurate data? Transferring value based on inaccurate or false data could wreak havoc across the entire digital ecosystem.  Data accuracy must be ensured to gain trust in the trustless model. K2 introduces a concept of data validators which act to verify data fidelity and accuracy and not just authenticity of the source. Authentic data does not necessarily mean it is accurate.

## Data Fidelity

Decentralized applications can only deliver on their promise if data available to them is of high fidelity. Fidelity is defined as:  _is the quality of faithfulness or loyalty. Its original meaning regarded duty in a broader sense than the related concept of fealty. Both derive from the Latin word fidēlis, meaning &quot;faithful or loyal&quot;_. Contract execution can be easily compromised if data streams are hi jacked or spoofed. Data fidelity must be ensured for contract execution to be trusted and secure. One of the main attributes of K2 is to ensure data fidelity.

## Data Joins

It is quite common for apps to use multiple data sources and algorithms to implement required business logic. For example: your contract may need pricing from Kraken, weather from Yahoo, news from Google &amp; social feed from Twitter to implement a specific function. This presents a unique set of challenges:

- Multiple interfaces to various Oracles
- Data quality &amp; fidelity may not be the same across Oracles
- Managing time synchronization and latency is a pain
- Data communication, session &amp; exception management is complex
- Payment and quality of service may differ and need to be managed for each Oracle
- Changes in each Oracle&#39;s interface may break your application logic

K2 creates a consistent way to query, compute and join Oracles together via a &quot;data join&quot;. Data join works similar to a shopping cart – put all your data items in one bag &quot;data frame&quot;, check out and pay. This makes building applications easy, efficient while dramatically improving quality and accelerating release cycles.

## Smart Data Contracts &amp; Quality of Service

Developers of decentralized applications should be able to form and execute a Smart Data Contract (SDC) which defines a relationship between Oracles, validators, and consumers. SDC defines all required actors (producer, consumer and validator) quality of services, pricing and mode of data delivery:

- Publish/subscribe vs request/reply
- Frequency: e.g. no later than X seconds of age
- Retention (how long to keep history for replay)
- Accuracy and fidelity constraints (e.g. 5% margin)
- Payment details: price and unit of measurement
- Entities responsible for data services
- Fees and penalties paid for data services

## Data Retention and Replay

Data inputs which are available for contract execution must also be auditable and available for replay. How does one independently verify a contract execution and subsequent results? They must have access to data inputs which trigger smart contract execution. Destroying such data will render smart contracts unverifiable and therefore not trust worthy. Who would trust a smart contract which cannot be independently verified? This capability is critical to enable trust, weed out fraud and theft in the digital smart economy. K2 establishes an off-chain data retention facility which can be used to audit execution of DAPPs utilizing one or more Oracles. Retention is specified in the SDC (Smart Data Contract).

## Data Consistency across Blockchain

Smart contracts can be executed anywhere on a decentralized network. How does one ensure data streams are consistently applied to all executions? Latency introduced in such execution can create some real challenges especially when dealing with highly volatile data feeds such as pricing information which can change on sub-second basis. Data platform must ensure that &quot;same&quot; data is delivered to a specific contract in a consistent fashion to avoid ambiguous or conflicting results.

## Uniform Access to Oracles

DAPPs should have a single and consistent interface to access all Oracles, run computations, aggregations, queries which span one or more Oracles without having to interface with each Oracle separately. This model simplifies development, integration and deployment of DAPPs as well as removes dependency on changes in individual Oracle&#39;s APIs and data formats. DAPPs need a single interface to bind, query, compute and pay for Oracles at runtime.

## Data Lakes vs Real-time Streams

Data lake is repository holding static or dynamic data sets while real-time streams are taps into data as it is being generated (near real-time e.g. stock quotes). DAPPs need ability to write and execute queries against public and private data lakes as well as real-time streams. These queries can be lookups, aggregations, computations, classification, machine learning and other algorithms. Data could be structured or unstructured depending on the nature of a data set.

Real-time streams typically carry time series data elements or events (something happening at a moment in time). DAPPs will require ways to query and analyze real-time feeds as they happen. Such data can be conditionally retained in a data lake for historical analysis. Examples of real-time feeds: stock price quotes, token price quotes, news, weather events, blockchain events, body vitals, telemetry, IoT sensor readings. Often such data has a short life-span as its relevance and value may erode with time and therefore requires timely evaluation and action.

## Off-chain Computations, Aggregations

Running on-chain computation are slow and expensive within today&#39;s set of decentralized blockchains such as Ethereum. DAPPs will need a way to off-load computations, aggregations, machine learning and other algorithms to a layer 2 platform such as K2. In addition to data integration pipeline, DAPPs will need access to off-chain data analytics &amp; compute resources where complex computations can be done efficiently and cost effectively. Results of such computations can be piped back into smart contracts for on-chain processing.

## Off-chain Contract to Contract Communication (C2C)

Contracts should be able to exchange data without on-chain settlement. C2C communication is often necessary to deliver high throughput, data rich, dynamic applications. Such data exchanges can occur via Oracles and/or Data Lakes using variety of data access methods as described in previous sections.

# K2N.IO – Intelligent Data Marketplace for DAPPs

K2N.IO is a data integration and analytics platform which serves to connect off-chain data with the decentralized ecosystem. K2 interconnects decentralized applications with on and off chain data streams (Oracles) and enables building data rich &amp; dynamic DAPPs. Digital, decentralized economies require high fidelity data streams to execute smart contracts and gain trust in a trustless model.  Such data streams are currently fragmented, not easily/readily available and most importantly un-auditable and un-verifiable introducing a significant roadblock for the development of decentralized, smart economy.

K2 allows data providers monetize data services while fueling development and integration of decentralized applications via a K2 Data Marketplace.

## Smart Data Contract (SDC)

SDC (Smart Data Contract) is an on-chain algorithmic agreement between Oracle(s), subscriber and validator. It outlines several categories of service:

- How data is delivered (scheme) – publish/subscribe or request/reply
- Retention – how long will the data be retained for auditing
- Frequency – what is frequency of data delivery (every sec, min, hour)
- Message Format – JSON, XML, etc.
- Message Structure – describes required and optional fields
- Pricing Model – agreed pricing model and cost structure (e.g.  BTC/byte, $/byte)
- Penalty – agreed upon penalty for not delivering a service
- Router(s) – agreed upon intermediary for data exchange
- Validator(s) associated with the contract (verify)
- Algorithm(s) associated with the contract (execute, compute)
- Oracle(s) associated with the contract (read/query only)
- Data Lake(s) associated with the contract (write with optional read)
- Terms of service such as expiration (date or event)

## Messages (Data Frames)

Messages (Data Frames) address the issue of consistently applying chunks of related data to a contract execution and provide a hashed, time stamped record of what is exchanged between Oracles, validators and subscribers. Messages consist of a uniquely identified data envelope which encapsulates all required data streams (which can come from one or more Oracles) and values required for contract execution.  **Messages are cryptographically signed by all participants defined in the smart data contract (SDC). Each message has a unique hash (identifier) and can be referenced later if retained for audit off-chain.**

**Example** : Contract has a method **pay\_call(address, amount, msg[weather, stock\_price])** where **pay\_call** pays a certain amount to a specific address given specific weather conditions and stock price. Weather and stock price are delivered from an external data source and packaged into a message which can be retrieved and referred to independently from any other contract execution its unique hash (ID). Messages solve the problem of consistently applying business logic on a decentralized network by referencing each message by its unique ID.

## Algorithms (Compute Oracles)

Algorithms are specialized Oracles which deliver computational capacity to the K2 ecosystem. Smart contracts can call K2 algorithms on a given data set. K2 will deliver a standard set of algorithms for analyzing times series data such as: mathematical operators, aggregations, statistical operators, anomaly detection, machine learning.



## Oracles (Read &amp; Compute only)

Oracles are owners and providers of data, which produce the underlying data required for contract execution. This data could be public such as on-chain data: Bitcoin, ETH, LTC, etc. Data can also be private and delivered by certain companies or entities such as: weather, stock pricing, sensor data, automotive telemetry, insurance, banking etc. K2 platform is responsible for converting raw data streams provided by Oracles and turning them into Messages consumable by DAPPs.

Oracles can be joined into a single stream which can be consumed as a single message containing variables from all the Oracles required for contract execution.

## Data Lakes (Read, Write &amp; Compute)

Data Lake is a data repository holding static, dynamic data. It could be database, filesystem, stream or anything else that store and retain data over a period of time. Data lakes inherently designed for write read &amp; compute operations. DAPPs can store data off-chain into a data lake as specified within a smart contract definition. This data can be used by other DAPPs via an Oracle and therefore enables contract-to-contract communication. Essentially Data lakes can be Oracles if used not only to store but also to query data.

## Data Routers (Data Intermediary)

Data Router is K2 network intermediary which provides data routing &amp; delivery medium between data consumers and producers. Example of data routers could be: TOR, VPN, onion routing implementations, point-to-point and others. Smart data contract outlines the medium of exchange and defines the routing method between K2 data services. Routers can also provide an additional level of security and anonymity required by data consumers. Routing services are paid for by data consumers and codified within a smart data contract.

## Subscribers (Data Consumers)

Subscribers are consumers (DAPPs) of Messages delivered by Oracles. Subscribers would typically subscribe to one or more Oracles (data streams) and get notified when certain Messages are available for consumption. Subscribers can also query specific messages on demand using RPC model. Oracles and subscribers are bound by a Smart Data Contract which outlines the terms of service between the two parties.

## Validators (Verification)

Validators are independent entities responsible for verification of promised quality and data accuracy delivered by Oracles to subscribers via Smart Data Contracts. Validators also provide facility for retaining data exchanged between Oracles and subscribers. Validators verify, store and retain all messages exchanged between a given Oracle and subscriber. One of the most important objectives of a validator is ensure data accuracy and fidelity. Validators must cryptographically sign all validated data frames. These signatures are used by data consumer to ensure data accuracy and integrity.

## Patterns (Pre-Packaged Data Services)

Pattern is a pre-packaged set of data services such validators, oracles, data lakes and algorithms which accomplish a specific functional or business objective. For example: a crypto pricing pattern, news feed pattern, logging pattern, etc. Each pattern includes a set of predefined data inputs and outputs and can be consumed by the underlying DAPP as a package instead of individual parts. Patterns make it easy for developers to build and deploy applications by simply sourcing proven patterns into their business logic. Developers can also create and publish patterns into K2 data marketplace. Pattern can also include other patterns.

## Pricing Models for Data Services

K2 introduces a consistent pricing model for all data services. The following pricing models will be introduced:

- **Pay-per-use** – consumer pays for each write/request/reply when accessing data services. This model works for contracts which need data on as-needed basis. Fee can be measured either per call or per byte.
- **Pay-per-batch** – typically for long term data services where consumer pre-pays for a batch of messages (or bytes) which covers data, validation, intermediary and gas. It works very much like a pre-paid &quot;charge card&quot; where a service fee gets automatically deducted as data services are rendered to the underlying smart contract. Consumers must periodically replenish the &quot;charge card&quot; with more tokens or contract expires and stream terminates. Batches can be measured as the total number of calls or messages or total number of bytes.

A pricing model is specified in the SDC (smart data contract) which outlines the terms of service between consumers and data services.

## Data Query &amp; Compute Language (Liquid)

K2 provides several ways to write, query and analyze data:

- Stream – write (un)structured  data into a data lake with a specific retention policy
- Request/Reply – query and filter a specific data set from an oracle or a data lake
- Publish/Subscribe – subscribe one or more topics and receive a call back when data is available
- Computations  -- run computations, aggregations on data stored in data lakes
- Complex Event Processing  -- queries, computations, aggregations  on real-time feeds (CEP)
- Call external web APIs (HTML, JSON, XML, etc.)

Queries are expressed using a common data query language called **Liquid**. Examples of K2 Liquid queries:

- Stream data: _&#39;Upsert Event EventName=&#39;Payment&#39;, Tag=(&#39;amazon&#39;,&#39;books&#39;), Properties=(D:&#39;amount&#39;=&#39;10.0&#39;, D:&#39;tax&#39;=&#39;1.3&#39;) retain for 10 days&#39;_
- Query a data lake: _&#39;get events from &quot;Orders&quot; fields amount for last 1 hour&#39;_
- Query real-time set: _&#39;subscribe to events output every 5 seconds&#39;_
- Run aggregations: _&#39;get the number of events fields Min(Price), Avg(Price)&#39;_
- Run computations: _&#39;get events compute EMA(Price, 20)&#39;_
- Call external Web API: _&#39;__get json(&quot;_ [https://myurl/ticker?pair=BTCUSD).result.BTCUSD.c.o](https://myurl/ticker?pair=BTCUSD).result.BTCUSD.c.o)_&quot;)&#39;_

Liquid queries including computations and aggregations are layered on top of Oracles and Data Lakes, which can be applied to multiple data sources at once. This allows DAPP developer a great deal of flexibility as well as ability to run data computations off-chain with callback back into a smart contract when computations are complete. Error handling is handled using a similar method: call back into a smart contract with error code and exception details.

## Scalable, Elastic Messaging Bus

K2&#39;s goal is to deliver an elastic messaging bus which can accommodate growing demand for data at many orders of magnitude of current blockchain implementations. This is accomplished by employing a combination of the following technologies and architecture principals:

- Peer-to-peer clustered &amp; stateless micro-services
- Dynamic data routing &amp; load balancing
- Combination of centralized and de-centralized computing models
- Decentralized ecosystem of Oracles, Validators, Algorithms and Routers
- On-chain settlement of payment, data contracts and terms of service

# K2 Token Economics

K2 is a &quot;digital railway&quot; for connecting Oracles, Validators and Subscribers and establishes: trust, high accuracy, fidelity, quality of service and discourages fraud or poor quality of service. DAPPs compensate high quality Oracles for timely and accurate data, conversely economic dis-incentives exist for Oracles which deliver poor quality or inaccurate information. Such incentives are expressed and codified in a Smart Data Contract (SDC) which outlines terms and condition including payment terms and quality of service.

K2 ecosystem economy grows with the number of Oracles, DAPPs and overall data volume. A portion of the fees paid for data services within SDC is allocated towards network participants such as: Oracles, data lakes, validators and routers. All fees including routing fee are codified within SDC.

K2 token ecosystem consists of following:

- K2 token – digital smart contract, voting rights and means of exchange
- K2 PoS – proof of stake model for network participants
- K2 governance – a framework and process to govern development of K2 ecosystem

## K2 Crypto Token

K2 is a consumer token used for securing and trading K2 data services. DAPPs, validators, data lakes and oracles must obtain and stake K2 tokens to partake in the K2 network. Bad actors are punished by revoking a portion of K2 tokens as defined in SDC. This creates a strong dis-incentive for Oracles and validators to provide inaccurate or fraudulent data and ensures that data is &quot;fresh&quot;. Validators are responsible for data retention and verification of data contracts between Oracles and DAPPs. Such verification includes: accuracy, fidelity and adherence to the terms and conditions of data contracts (SDC). In summary K2 token provides the following utility:

- Buy and sell data services, validation, networks fees
- Stake tokens to obtain publishing and validation rights
- Stake tokens to obtain governance and voting rights
- Dynamic pricing structure to ensure predictable costs

## K2 Proof Stake Model (PoS)

Oracle (data providers) and data validators must stake K2 tokens to partake in the K2 ecosystem. Staked tokens are used to ensure that key network participants are delivering services in good faith and abide by the terms of service outlined in the Smart Data Contract (SDC). Oracles may lose part of the staked K2 tokens if SDC is violated. Here are some examples of SDC violations:

- Data is not within the QoS (Quality of Service)
- Inaccurate data (rejected by most validators)
- Bad data format or stale data (not &quot;fresh&quot;)

The penalty amount is also specified within SDC and outlines the amount and who pays in case SDC terms and conditions are violated. This ensures that data consumers (DAPPs) get the highest level of service.

## K2 Governance Model

K2 PoS model also allows network participants to influence development, behavior and governance of the K2 ecosystem. All network participants who stake K2 tokens have voting rights which are proportional to the number of staked tokens. Therefore, networks participants get a say in the rules, conditions, development and governance of K2 ecosystem.

Voting is done on a quarterly schedule and get merged into the main trunk of the K2 roadmap. Any network participant (with staked tokens) can file a &quot;proposal&quot; to be voted on by the K2 stake holders.

Each proposal consists of 2 parts: problem or challenge and one or more solutions. Each proposal goes through a few rounds of feedback and public debate after which it goes out for a quarterly vote. Proposals can affect the following parts of the ecosystem:

- Request for enhancement or change
- Request to change process or implementation
- Request to change pricing, method or approach
- Request to add support for technology, ecosystem
- Request to change or augment a governance process
- Request to change release, testing schedules
- Request to change voting process
- Request to augment development team

# Technology &amp; Roadmap

K2 project is a derivative of a technology developed by jKool, LLC which is already running in production as a SaaS platform for streaming and analyzing data in motion and @ rest ( [www.jkoolcloud.com](http://www.jkoolcloud.com)). jKool, LLC ( [www.jkoolcloud.com](http://www.jkoolcloud.com)) contributes the following technology to the K2 ecosystem:

- Streaming platform for Oracles ( [https://github.com/Nastel/tnt4j-streams](https://github.com/Nastel/tnt4j-streams))
- Subscription platform for subscribers ( [https://github.com/Nastel/jkool-client-java-api](https://github.com/Nastel/jkool-client-java-api))
- Messaging and audit platform ( [https://www.jkoolcloud.com/product/technology/](https://www.jkoolcloud.com/product/technology/))
- Data analytics platform ( [https://www.jkoolcloud.com/product/jkql-query-language/](https://www.jkoolcloud.com/product/jkql-query-language/))
- Marketplace for Oracles and consumers ( [https://jkool.jkoolcloud.com/jKool/login.jsp](https://jkool.jkoolcloud.com/jKool/login.jsp))
- APIs and protocol for RPC &amp; publish/subscribe ( [https://github.com/Nastel/jkool-client-java-api](https://github.com/Nastel/jkool-client-java-api))

K2 Platform will be open sourced available @ GitHub under [LGPL-v3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html) license with development roadmap governed by community governance board as described in K2 Governance Model.

K2 Project will also develop additional extensions such as:

- K2 voting and governance platform
- Data marketplace using K2 token and other crypto currencies
- Reputation score for Oracles, validators
- Data audit and validation ecosystem
- Smart data contract implementation &amp; data pricing &amp; monetization
- High level language for implementing smart data contracts (Liquid)
- Data computations, aggregations and analytics off-chain (Liquid)
- Data integration and workflow tools for smart contract (DAPP) developers
- Integrations with various block chains (Bitcoin, ETH, EOS, NEO, WAN, etc.)

# Summary

Data integration presents a significant challenge for the development and growth of the digital smart economy. K2&#39;s goal is to deliver a data integration and analytics marketplace for powering data rich, dynamic DAPPs. This ecosystem is essential for the overall success of the smart economy. K2 combines multiple integrated technologies such as: cryptography, streaming, clustered computing, big &amp; fast data, complex event processing (CEP) as well as a data marketplace where machine data can be traded between data providers (such as Oracles) and decentralized applications.

# Resources and Links

- [http://k2n.io](http://k2n.io)
- [https://jkoolcloud.com](https://jkoolcloud.com)
- [https://github.com/K2NIO](https://github.com/K2NIO)
- [https://twitter.com/k2platform](https://twitter.com/k2platform)
