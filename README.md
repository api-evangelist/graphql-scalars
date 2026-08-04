# GraphQL Scalars

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

API Evangelist catalog entry for **GraphQL Scalars** — an open-source library from [The Guild](https://the-guild.dev/) providing 80+ production-ready custom GraphQL scalar types for building precise, type-safe GraphQL schemas.

## Overview

GraphQL Scalars extends the five built-in GraphQL scalar types (Int, Float, String, Boolean, ID) with a comprehensive set of domain-specific scalars validated at the schema layer. It is framework-agnostic and works with Apollo Server, GraphQL Yoga, Mercurius, and any other GraphQL server implementation.

**Website:** https://the-guild.dev/graphql/scalars  
**Documentation:** https://the-guild.dev/graphql/scalars/docs  
**GitHub:** https://github.com/graphql-hive/graphql-scalars  
**npm:** https://www.npmjs.com/package/graphql-scalars  
**License:** MIT

## Featured Scalar Types

| Category | Scalars |
|----------|---------|
| Date & Time | DateTime, Date, Time, DateTimeISO, LocalDate, LocalTime, Timestamp, Duration |
| Identity | UUID, GUID, CUID, CUID2, ULID, ObjectID |
| Network | IPv4, IPv6, IP, MAC, URL, Port |
| Communication | EmailAddress, PhoneNumber |
| Finance | IBAN, Currency, USCurrency, RoutingNumber |
| Geography | Latitude, Longitude, CountryCode, PostalCode, TimeZone |
| Numeric | BigInt, Long, SafeInt, PositiveInt, NegativeFloat, UnsignedFloat |
| Structured | JSON, JSONObject, GeoJSON |
| Encoding | JWT, Hexadecimal, HexColorCode, Base64 |
| Other | SemVer, ISBN, ISSN, Void, NonEmptyString |

## Repository Contents

```
graphql-scalars/
├── apis.yml                          # API catalog metadata
├── plans/
│   └── graphql-scalars-plans.md      # Pricing tiers and open-source model
├── rate-limits/
│   └── graphql-scalars-rate-limits.md # Rate limit documentation
├── finops/
│   └── graphql-scalars-finops.md     # Cost analysis and FinOps guidance
└── graphql/
    └── graphql-scalars-graphql.md    # GraphQL schema reference
```

## Maintainer

Kin Lane — [kin@apievangelist.com](mailto:kin@apievangelist.com)

Part of the [API Evangelist](https://apievangelist.com) catalog.
