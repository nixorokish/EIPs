---
title: Governance Transparency
description: This meta EIP standardizes and formalizes existing processes to help orient the public to the governance process and allows transparency into the relevant parties and related governance meta-EIPs
author: nixo (@nixorokish)
requires: 1, 5069, 7723
status: Draft
type: Meta
created: 2024-08-05
---

## Abstract

The process for proposing and advocating for an EIP is outlined here, as well as the teams involved in the governance process.

## Motivation

The Ethereum governance process is outlined here for better transparency and public orientation

### Proposing an EIP

A new EIP must follow the criteria outlined in EIP-1 and should be opened as a pull request titled "Add EIP: [EIP title]" in the ethereum/EIPs repository. The EIP number is assigned by an EIP editor sequentially from the lowest number available

### Advocating for an EIP

The author of a new EIP seeking support should propose the topic for discussion in the current All Core Devs (ACD) meeting Github issue in the ethereum/pm repo. If added to the agenda, they should expect to attend an ACD meeting to familiarize core devs with the EIP. This may cover:
- Motivation for the EIP
- Research conducted prior to submission
- Affected parties and/or supporting teams
- Implementation details

Network upgrade inclusion stages, as defined in EIP-7723, may be assigned to an EIP at any point in the network upgrade process

### Teams facilitating governance: EIP Editors

A current list of active and former EIP editors and Keeper of Consensus elected by criteria in EIP-5069 must be kept up-to-date in the ethcatherders/EIPIP repository with a date of election and links to discussion. These nomination discussions should be conducted in an open issue in the ethcatherders/EIPIP repository

### Teams facilitating governance: Protocol Support

The governance process is shepherded by the Protocol Support team. Membership and roles in teams necessarily involved in the meta governance process must be published in the ethereum/pm repository

### All Core Devs calls

Biweekly execution ACD calls and biweekly consensus ACD calls are facilitated by a participant from any team, chosen by informal election or nomination by a departing call facilitator. A list of former and current ACD call facilitators should be kept current in the ethereum/pm repository. 

The schedule for these calls must always be available in the ethereum/pm repository. These calls are livestreamed publicly with a recording immediately available after streaming

Each meeting's agenda, notes, and recording link must be updated in the ethereum/pm repository Meetings table within two weeks of each call

## Backwards Compatibility

This EIP does not directly change the Ethereum protocol. It formalizes existing processes of governance

## Security Considerations

None.

## Copyright

Copyright and related rights waived via [CC0](../LICENSE.md).
