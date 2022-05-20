# Specification of Powers

This document is a concise outline of what powers and privileges exist in the DAO and who they are currently assigned to. 

## Access to Treasury Funds

Funds may only be transferred out of the DAO treasury via a community proposal (not an emergency proposal). 

## Royalty Split

Royalty fees from exchanges (as of now, OpenSea) will be split with 50% of royalties going to the DAO treasury and 50% going to the Core Team directly. 

This arrangement is intended to be fluid rather than permanent. For now, the majority of operations and development will be the responsibility of the Core Team. As more responsibility is handed over to community teams, the royalty split can and should be revisited.

## Game and Governance Contracts

Upon deployment, the governance system will be granted ownership and control of the game and governance contracts. 

This means that if a community member or team wanted to create a new career type for ships, for instance, the DAO would be able to update the contract code to make it happen, so long as the [proper protocol](/dao/proposal/) is followed. 

Contracts may only be modified or updated via a community proposal. This means modification of the contract code requires a community proposal to pass, including those submitted by members of the Core Team. An exception is outlined under `Emergency Proposal Multi-sig`.

Alongside upgrade privileges, The Citadel DAO has the DEFAULT_ADMIN_ROLE for all contracts with [Access Control](https://docs.openzeppelin.com/contracts/2.x/access-control). This means that the DAO could grant and revoke roles specific for performing game tasks, such as publishing belts and creating new tokens.

In the interim, the Core Team will retain privileges necessary to:
- Add new belts
- Publish new belts
- Determine the number of ships up for auction each week

All of these privileges are revocable via a community proposal, and the team cannot veto this special proposal. 

To learn more about this in more technical detail, consult the [Yellowpaper](https://articles.citadel.game/yellowpaper#handoff). 

## Emergency Proposal Multi-sig

Because the proposal process involves over a week to successfully approve a contract update, the Core Team has decided to reserve the right to pass an emergency proposal to upgrade non-governance contracts via a multi-sig in the event of a game related emergency situation. 

The multi-sig is comprised of all members of the Core Team, representatives at Machinations, as well as select members from the community. All members of the multi-sig must sign for the emergency proposal to pass. 

## Proposal Veto Multi-sig

Because this project is launching with fully decentralized ownership of contracts and the majority of mint funds from the outset, the Core Team felt it necessary to reserve the power to veto proposals considered malicious or against the best interests of the community during the early phases of the DAO's development. A veto power is likely always going to be a good fail-safe to have, and at some point the multi-sig could transition to being community controlled. 

Meanwhile, this power can be revoked via a special pre-written proposal that cannot be vetoed if the community feels the Core Team has misused this power. 

## Governance Documents

All community governance documents are subject to modification via a community resolution proposal. Changes to the documents will be implemented off-chain by the appropriate DAO or Core Team representative. 

Documents include: 
- [Charter](#) 
- [Proposal Process](#)
- [Specification of Powers](#)

## Off-chain Community Accounts and Services

Due to the centralized nature of some of our core collaboration and communication tools, it's not possible to transfer ownership of accounts such as Discord to the governance contracts. For now, the Core Team will continue to hold administrator control over these accounts and steward them on behalf of the community. 

The Core Team is happy to discuss creative ideas on how these accounts could one day be handed off to community control. 

Accounts include:
- [Discord]([discord.gg/thecitadel](https://t.co/Ylupe0ZCCf))
- [Twitter](https://twitter.com/TheCitadelGame)
- Discourse
- [Machinations](machinations.io)
- [citadel.game](citadel.game)



