---
slug: /
---

# HomeDAO Whitepaper

:::caution Draft

Please note, that this version of the HomeDAO whitepaper is still in a draft state. Any information hereafter are
subject to change. We are actively looking for feedback to take into account for future iterations. Please note that all
changes can be transparently reviewed by the community within the [HomeDAO Github](https://github.com/homedao/docs/commits/main).

:::

In many cities in the world, the property rental industry is fast approaching a potentially disastrous turning point.
Residential rent prices in the EU have risen 16% in ten
years[^1], roughly in line with income[^2], but in Berlin, rent has increased
by 46% in five years. In London, the average rent jumped over 10% in one year, and in Dublin, over ten years, rent has
doubled[^3].

There is a distinct sense, when reading these statistics, that "someone should do something". And often these sentiments
manifest themselves as demands to governments to impose top-down measures, such as rent
freezes[^4], state purchase of properties[^5], or even nationalisation of large renters[^6]. Aside from the political
difficulty and cost to the taxpayer of these
measures[^7], economists often argue that such measures are regressive and counterproductive. Whether they are right or
not, most
people agree that governments "should do something". However, are governments the only actors capable of making a
difference here? After all, governments also have to balance the interests of investors and homeowners. Are the
interests of tenants, prosective tenants and the next generation sufficiently represented by their governments? Can
these groups make their voices heard in some other way? Influence their future in some other way?

For generations, rental collectives and co-ops have offered an alternative model, allowing tenants protection against
rising rents, in addition to, or in many cases, replacing, legal protection. These collectives typically work by taking
properties "off the market", in other words, transferring ownership from a private company or individual, to a
non-profit foundation, controlled by the tenants themselves or their representatives, on the understanding that the
properties are no longer treated as assets. These cooperatives have often been successful in protecting their members,
and belong, alongside governments, to the "arsenal" of weapons that tenants can yield against property investors and
speculators. But these cooperatives have their own difficulties. They are difficult to scale, they arguably prioritise
the existing tenant over the prospective tenant, and do not address the supply-side of the problem, that surely must be
a component of the solution.

A missing part of the puzzle is a mechanism by which cities can incentivise investment, promote new development, but
protect the interests of tenants, both existing and prospective.

## DAO

A new form of "self-governance" is emerging, that offers an opportunity to add to the tool chest of modern economic
systems, by combining crowdfunding, democracy, and the alignment of incentives. This form is the Decentralised
Autonomous Organisation, or DAO, and has emerged in recent years in the blockchain and cryptocurrency communities. By
enabling trustless voting mechanisms, DAOs extend the collectivisation and co-operation principles of organisations such
as tenant collectives to a wider population, and by using Smart Contracts, DAOs allow investment to follow strict
constraints, similar to laws passed by governments, that control how the investment upside can be distributed.

## HomeDAO

The HomeDAO is a decentralized autonomous organization that focuses on maximizing the sustainable usage of real estate.

HomeDAO enables the decentralized, representative participation in the acquisition, management and rental of real-estate
property. HomeDAO focuses on the private home and apartment market and models its incentives to maximize community, on
behalf of tenants and DAO members.

Core guiding principles are manifested in the HomeDAO Constitution.

Processes within the DAO are implemented in trustless Smart Contracts that govern, among others:

* The creation and management of funding proposals around a new HomeDAO Property.
* Conversion of successful proposals into a tokenized representation of the real-world asset.
* Long-term rental management of properties with a focus on predictable, protected rents and maximum occupancy
* Short-term rental model with market-rate rents, used as a funding mechanism.
* Rental payments to HomeDAO are modeled on the blockchain, with proxy on-ramps for non-crypto renters.

In order to bridge the gap between virtual participation and real-world property assets,
HomeDAO operates foundation that is able to purchase and hold the real-estate for its members.

HomeDAO models several levels of membership, ranging from pseudo-anonymous governance token holders to fully KYCed
tenants. In this, personal information is only accessible to the foundation. Only the representative pseudo-anonymous
levels are visible to other members of the DAO.

HomeDAO is built around a governance token (HOME) and a utility token (RENT). The HOME token allows members to actively
participate in the governance of the DAO, for example, initiate, vote and execute on proposals to update or change
processes within the DAO.

RENT is the utility token of HomeDAO. RENT is distributed upon acquisition of new properties, and is staked by holders,
allowing them to participate in rental income of existing properties.

## HomeDAO Structure

[//]: # (Original Board: https://miro.com/app/board/uXjVO0opSu4=/ )
![HomeDAO Structure](/whitepaper/home-dao-structure.jpeg)

HomeDAO is made up of the following components:

* The Foundation
* The DAO
* The Protocol

### The Foundation

The Foundation is a non-profit, off-chain legal entity, that owns the property and is the legal landlord in property
rental contracts. As well as its legal role in rental contracts and property ownership, it also handles property
management. In these respects, it operates like a traditional housing company, except that it operates according to the
wishes of the DAO.

The foundation is led by a director who represents the decisions of the DAO externally.

### The DAO

The DAO is an on-chain, decentralised organisation, where membership is determined by possession of a Governance token
called the HOME token.

The role of the DAO is

1. to regulate, manage and upgrade the HomeDAO protocol.
2. To direct the action of the foundation, with regard to purchasing of property, allocation of budget, etc.

### The Protocol

The Protocol is an on-chain smart contract that governs the peer-to-peer renting of property via the RENT token. The
RENT token is a utility token, used by tenants of HomeDAO properties to pay rent into the protocol. This rent is repaid
to token holders in the form of yield.

By staking RENT tokens in a pool, token holders earn yield in proportion to their stake.

## Relationship between Tenants and the Protocol

HomeDAO intends to issue long- and short-term rental contracts. Rental contracts are "standard" contracts, issued in
accordance with local laws and regulations, and are as such unrelated to the HomeDAO protocol and the cryptocurrency
layer beneath it. Tenants are not required to directly borrow Rent tokens, and do not pay rent daily.

Behind the scenes, however, each rent payment is translated to a transfer of RENT tokens in the protocol. By modelling
rental activity on-chain in this way, the protocol allows for the following three important factors that "power" the
tokenomics of HomeDAO, and further the goals of the HomeDAO constitution.

* It enables short-term renting, for the benefit of long-term tenants
* It guarantees the flow of rental income into the system, and brings value to Rent tokens
* It disincentivizes using HomeDAO as a vehicle for property speculation

### Short-term renting, for the benefit of long-term tenants

The protocol allows for short-term property rentals while incentivising longer-term borrowing, through a function that
reduces the cost of renting according to the length of time committed.

Short-term rental thereby brings in disproportionately high income into the protocol. In a traditional business model,
this would encourage a company to maximise short-term rental over long-term.

The HomeDAO protocol, on the other hand, allows the income from short-term rental to act for the benefit of long-term
tenants. It does so in the following ways:

* While properties can be rented at short-term rates, investors can only earn yield at long-term renting rates. The
  difference between the two rates are kept in the system.
* Long-term token reservation is rewarded with RENT tokens, allowing long-term tenants to earn yield.
* The protocol limits the availability of properties for short-term rental, in order to guarantee the balance remains in
  favour of the long-term tenants. As with all protocol parameters that have the capability to disrupt the mission of
  HomeDAO as stated by the constitution, the protocol includes safety mechanisms that require a voting supermajority to
  adjust.

### Brings value to Rent tokens

Despite tenants not being required to directly interact with the protocol, the foundation operates surrogate accounts,
which convert off-chain rent payments into on-chain RENT token borrowing transactions. This guarantees a steady flow of
income into the pool, and a predictable and steady yield to the RENT token holders, backed by a reliable asset.

### Disincentivize HomeDAO as a vehicle for property speculation

Property rental companies frequently leave properties empty for speculative purposes. Through the HomeDAO protocol, RENT
token holders can earn only through rental income. Any capital gains earned through property value appreciation does not
flow to token holders, rather it is retained in the protocol and used to grow the property portfolio, or pay costs, as
determined by the DAO.

## Tokenomics

HomeDAO issues two primary token types:

* HOME tokens: governance tokens, that grant voting rights in the DAO
* RENT tokens: utility tokens that can be staked to earn yield in the Protocol

### HOME Token

HOME tokens come in four forms:

* Level 1: No KYC required, limited voting rights, available to all
* Level 2: Issued to KYCed holders of Level 1 HOME tokens.
* Level 3: Issued to tenants of HomeDAO properties and foundation board members.

Level 1 tokens are issued at a rate of $1 = 1 HOME Level 1.

Level 1 holders may upgrade their tokens to Level 2 by going through KYC (see below)

Level 2 tokens are not necessarily issued at a rate of 1:1 but are limited to a fixed amount per individual.

Level 3 tokens are managed by the foundation and are issued to (or held in trust for) the tenants of DAO properties or
members of the foundation board.

See Proposals and Voting below for details on how HOME tokens are used in the DAO

### RENT token

The RENT token is the utility token used to pay rent in the HomeDAO protocol.

#### RENT token issuance

The quantity of minted RENT tokens is tied directly to the foundation’s property portfolio. In particular, RENT tokens
are issued on acquisition of new property, in relation to the value of the property.

At any point in time, one or more "funds" are active, linked to a wallet under the control of the foundation.

This fund has a target amount and a target date, as determined by the DAO.

Investors in the fund are given "placeholder" tokens representing their investment. Funds invested in the fund are
locked, and cannot be withdrawn, unless the target amount is not reached by the target date.

Once the fund reaches the target amount, it is "triggered", which releases the funds to the foundation for the purpose
of acquiring rental property (note, this funding takes the place of traditional capital - it is not expected that
HomeDAO will need to obtain capital through bank loans or bond issuance, as in a traditional housing company, though not
explicitly ruled out).

Upon triggering the fund, investors can swap their placeholder tokens 1:1 for newly-minted RENT tokens.

#### Investment and Issuance Phases

1. The DAO creates a new fund
2. Investors deposit into the fund, earning Placeholder tokens
3.
    1. The target is reached - RENT tokens are issued, the fund is passed to the foundation to invest in property
    2. The target is not reached, funds are returned to the investors
4. Return to 1

[//]: # (Original Board: https://miro.com/app/board/uXjVOzxWf2k=/ )
<div style={{textAlign:'center'}}>
    <img src="/whitepaper/funds.jpeg" alt="HomeDAO Funds" width="700" />
</div>

#### Staking RENT tokens and reserving properties

As mentioned above, the foundation ensures that rental contracts in the "real world" are buffered from the protocol.
However, in this section, we discuss what is happening at the protocol level when a tenant rents a HomeDAO property. So
for the purposes of this section, "tenant" can be interpreted as "an agent that operates on the tenant’s behalf".

RENT tokens can be deposited into a pool, controlled by the protocol. This is called "staking". By doing so they
receive pool tokens called sRENT. The protocol will start with just one common stake pool, however depending on
regulatory requirements, other pools may be created, which may have additional KYC or other requirements in order to
stake there. Properties will be associated with one pool only.

Properties are represented in the protocol as a form of NFT, which contains the following values:

* Daily rent $R$ (denominated in RENT tokens)
* Supply $S$

The tenant states that they wish to rent a property for $X$ days, by requesting the transfer of one of these NFTs to
their
wallet. To do so, they must pay $X * R$ RENT tokens into the pool.

This transfers one NFT to the tenant’s wallet for $X$ days, after which it would revert to the protocol.

The RENT deposited into the pool would be paid out to stakers depending on the proportion of the pool that they hold.
This works in a similar way to an AMM liquidity pool, in that the RENT is returned to the pool, and the value of the
associated pool tokens thereby increases.

#### How is the exchange rate between sRENT and RENT calculated?

The stake pool maintains an exchange rate of sRENT

$$
Rate=\frac{staked\ RENT}{minted\ sRENT}
$$

#### A working example

1. The pool contains 400k RENT tokens. 400k sRENT has been minted
2. Alice invests 100k RENT tokens, bringing the pool to 500k
3. 100k sRENT is minted and sent to Alice (less a fee determined by the DAO - assume 0% in this example). 500k sRENT has
   now been minted
4. Time passes, and tenants pay 10k RENT into the pool, bringing the pool to 510k
5. Alice withdraws her RENT tokens. She burns her sRENT and recovers 102k RENT

In this case, the exchange rate $R$ is

$$
R=\frac{510k}{500k}=1.02
$$

#### How does the tenant obtain RENT tokens?

In order to take part in the rental process, tenants must deposit RENT tokens in the protocol. The tenant pays rent
denominated in a fiat currency. Regardless of the target city, for simplicity, we assume USD in this paper. Tenants (
through their surrogate agents - see above) convert their fiat currency to stablecoin, and from there to RENT using an
exchange.

During the bootstrapping phase, the foundation will retain a treasury of RENT that it will exchange on the tenant’s
behalf, in order to ensure stability of the RENT price before there is sufficient external liquidity in exchanges.

#### How is the Daily rental rate R calculated?

The daily rent rate $R$ is set by the DAO on each property NFT. Typically, each rentable property is represented as a
separate NFT, so $S$ would be $1$, and $R$ would be the daily cost to rent this property long-term.

Since tenants pay rent denominated in fiat, this rate is influenced by the RENT/USD exchange rate. Specifically, $R$ is
calculated by

$$
R=cx
$$

where

- $c$ is the daily property rent in USD (typically fixed and changes rarely)
- $x$ is the current exchange rate as set by a trusted oracle.

#### Bootstrapping the RENT pool

The model proposed by HomeDAO is ambitious and novel - earning a proportion of rental income, through staking tokens in
an on-chain protocol, without the token holder entering into a legal relationship with either the landlord (the HomeDAO
foundation) or the tenants, has regulatory ramifications which will take time and money to resolve.

In order to incentivise early investment in HomeDAO, while the infrastructure is established to meet these regulatory
requirements, the DAO is permitted to take a number of actions, including, but not limited to:

* Granting options to HOME token holders to purchase RENT at a fixed price once RENT tokens are made available
* Airdropping RENT tokens to early HOME token holders

## KYC & Regulatory Compliance

Due to legal and regulatory requirements, some HomeDAO participants are required to undergo KYC (know your customer).

HomeDAO uses on-chain tokenized identity in order to decouple the KYC process itself, carried out by the foundation,
from the on-chain protocol. This ensures that, once authorised, actors on the protocol can operate independently of the
foundation.

As the DAO develops, this section will be fleshed out with answers to the following questions:

* What are the KYC and/or other requirements for a staker earning yield through rent payments
* Do we need stakers to be residents in the same country as the rental properties they are staking "against"?
* KYC and/or other requirements for voting in the DAO (at any level).
* Proof of address for stakers or governance token holders?
* Do stakers or gov. token holders (of any level) need to be legally members of the foundation in some capacity?

## Proposals and Voting

The primary governing body of HomeDAO is the DAO itself, a collection of individuals that collaborate to manage and
evolve HomeDAO, in accordance with the constitution and the overriding goals of the undertaking.

Unlike purely on-chain protocols, HomeDAO is dealing with the accommodation and living conditions of real-life people,
as well as local, national and international laws and regulations, and therefore requires a more rigid hierarchical
structure than pure DAOs. This form of DAO is sometimes called a "Hybrid DAO".

However, unlike a traditional company or foundation, HomeDAO operates according to two policies:

* "open-door". Decisions are made in the open
* "social mobility". There is a clear mechanism for moving between the hierarchies of the DAO

Along these lines, the DAO issues a governance token: HOME at three [levels](#home-token).

Proposals can be made by any token holder and are discussed on forums open to all levels. The nature of the proposal
determines the level of HOME token that is permitted to vote on it. The level is set by the proposer, and must be at the
level of the proposer or below.

A majority of higher-level voters can nullify a lower-level vote, if deemed to be at the wrong level. This is done by
proposing a new proposal, to nullify the original one

1. For example, a level 1 proposal P1 is proposed and passed.
2. A level 2 voter proposes a new level 2 proposal P2 which proposes to nullify P1.
3. A majority of level 2 votes agree that P1 should be nullified.
4. P1 is nullified

In order to reduce abuse and conflicts, the following measures are also applied:

If the initial P1 vote passed with a majority of votes from all levels, then the P2 proposal is deemed invalid.

The DAO may be extended to require staking of HOME tokens to make a proposal.

Proposals that change the HomeDAO constitution, or that require changing the goals of the foundation, require a level 3
supermajority to pass.

### Example proposals, and their levels

<table>
  <tr>
    <th>Proposal</th>
    <th>Level</th>
  </tr>
  <tr>
    <td>Change colour of the website</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Buy a property</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Increase the daily rate for a property, within accepted margins</td>
    <td>3</td>
  </tr>
  <tr>
    <td>Amend the HomeDAO constitution</td>
    <td>3 supermajority</td>
  </tr>
</table>

## Privacy

One important effect of operating on a public blockchain, is that all activity, including voting,
staking and rent payments are public.

In DAOs managing on-chain protocols, this is rarely a problem. Participants interact behind the safety of pseudonymous
public keys or wallet addresses, and there is little risk of correlation to real-life entities, especially if
participants take simple precautions such as using a dedicated wallet.

However, in the case of HomeDAO, the potential exists to track on-chain payments to private property rental payments.
Care must therefore be taken in development of the protocol and foundation structures, that the privacy of the
participants is protected, especially at the early stage where on-chain activity will be less, and therefore more easily
tracked. In these cases, the foundation reserves the right to obfuscate the transactions on-chain in order to protect
the privacy of participants.

## Conclusion

The HomeDAO is made up of three components,

1. a foundation, that formally owns the property in law, and coordinates the management, rental and upkeep of the
   properties in accordance with the wishes of
2. the DAO, which directs the operations of the organization as a whole via a level-based voting system, and
3. the protocol, which aligns incentives between tenants and investors, and provides stability and funding for expansion
   of the organization through staking.

This document describes the operations of the three structures, particularly focusing on the on-chain aspects including
staking, token issuance and voting. The details of the whitepaper are subject to change in accordance with the wishes of
the DAO and the legal framework in which the organization operates, but are ultimately bound by the goals of the
foundation, as exemplified in the HomeDAO constitution.

[^1]: https://ec.europa.eu/eurostat/web/products-eurostat-news/-/ddn-20220114-1

[^2]: https://www.statista.com/statistics/1201068/annual-net-earnings-in-the-eu/

[^3]: https://www.dublinlive.ie/news/dublin-news/dublin-rents-growing-fastest-country-23033574

[^4]: https://mietendeckel.berlin.de/

[^5]: https://www.rbb24.de/wirtschaft/beitrag/2021/09/berlin-senat-wohnungen-kollatz-kauf-vonovia-deutsche-wohnen.html

[^6]: https://www.dwenteignen.de/

[^7]: https://www.tagesspiegel.de/berlin/enteignungsinitiative-in-berlin-entschaedigung-an-vergesellschaftete-firmen-soll-zwischen-14-und-23-milliarden-euro-kosten/27531020.html