# GraphQL Scalars

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
