# FullOn Improvement Proposals (FIPs)

FullOn Improvement Proposals are the primary mechanism for proposing, discussing, and documenting changes to the FLON protocol, system contracts, governance, token economics, and ecosystem standards.

## Proposal lifecycle

```text
Idea -> Draft -> Review -> Last Call -> Accepted -> Implemented -> Final
                 |                         |
                 +-> Rejected/Withdrawn <-+
```

Status changes are made through pull requests and require reviewer evidence appropriate to the proposal category. A proposal being merged as `Draft` does not activate it on-chain.

The complete process, status definitions, review requirements, numbering rules, and activation policy are specified in [FIP-0000](FIPS/fip-0000.md).

## Proposal index

| FIP | Title | Category | Status |
| ---: | --- | --- | --- |
| [0000](FIPS/fip-0000.md) | FIP Purpose and Process | Meta | Draft |
| [0001](FIPS/fip-0001.md) | Supernode Election, Performance, Rewards, and DAO Governance | Core / Economics / Governance | Draft |

## Contributing

1. Discuss the idea with the community and identify an author or champion.
2. Copy [the template](FIPS/fip-template.md) and fill every required section.
3. Open a pull request with status `Draft`. Do not assign a number yourself unless a maintainer has reserved one.
4. Resolve technical, economic, security, and governance review comments with explicit rationale.
5. Progress status through separate pull requests according to FIP-0000.

All normative requirements use the terms MUST, MUST NOT, SHOULD, SHOULD NOT, and MAY as described by RFC 2119/RFC 8174.

## Repository scope

This repository records decisions and specifications. Implementations live in their respective source repositories. A FIP marked `Accepted` is an approved specification; a FIP reaches `Final` only after its implementation and activation criteria have been verified.
