# CarGurus

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

CarGurus is an automotive marketplace providing REST APIs for dealer inventory management, vehicle pricing and market valuation, dealer performance analytics, consumer vehicle research, and dealer-to-consumer SMS communications. CarGurus is the most visited automotive shopping site in the US, operating marketplaces in the US, Canada, and the UK.

## APIs

- **Dealer Stats API** - Daily performance statistics for dealer inventory including search views, VDP clicks, and leads across email, phone, chat, and SMS
- **Instant Market Value API** - Vehicle market valuations and deal ratings (Great Price through Overpriced) based on make, model, trim, mileage, and location
- **Dealer Reviews API** - Consumer dealer reviews including ratings, text, and dealer responses
- **Dealer SMS API** - Send SMS and MMS messages from dealers to consumers
- **Car Selector API** - Vehicle make/model lookup and search URL generation for affiliates
- **SEM Ad Landing Page URL Generator API** - Generate targeted landing page URLs for SEM ad campaigns
- **SEM Filter Values API** - Filter values for SEM campaign configuration
- **Body Type Groups API** - Vehicle body type classification and translation data

## Authentication

All authenticated APIs require an `appId` and `authToken` provided by CarGurus upon partner or dealer approval. APIs accept credentials as URL query parameters or POST body fields.

## Developer Resources

- [Developer Portal](https://www.cargurus.com/Cars/developers/)
- [Engineering Blog](https://cargurus.dev/)
- [GitHub Organization](https://github.com/cargurus)
- [X / Twitter](https://x.com/CarGurus)
- [LinkedIn](https://www.linkedin.com/company/cargurus)

## Maintainer

Kin Lane (kin@apievangelist.com)
