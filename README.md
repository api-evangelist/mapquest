# MapQuest (mapquest)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

MapQuest provides mapping, geocoding, routing, and traffic data APIs for developers to build location-aware applications. The developer portal offers free API keys and documentation for directions, static maps, geocoding, and traffic incident services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mapquest/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mapquest/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Geocoding
- Mapping
- Maps
- Navigation
- Routing
- Traffic

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-05-19

## APIs

### MapQuest Directions API

The MapQuest Directions API provides routing capabilities with turn-by-turn directions, alternate routes, optimized routes, and travel time estimates using real-time traffic data.

- **Human URL:** [https://developer.mapquest.com/documentation/directions-api/](https://developer.mapquest.com/documentation/directions-api/)
- **Base URL:** `https://www.mapquestapi.com/directions/v2`

#### Tags

- Directions
- Navigation
- Routing

#### Properties

- [Documentation](https://developer.mapquest.com/documentation/directions-api/)
- [OpenAPI](openapi/mapquest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mapquest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapquest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MapQuest Geocoding API

The MapQuest Geocoding API converts addresses into geographic coordinates and vice versa, supporting both single and batch geocoding requests.

- **Human URL:** [https://developer.mapquest.com/documentation/geocoding-api/](https://developer.mapquest.com/documentation/geocoding-api/)
- **Base URL:** `https://www.mapquestapi.com/geocoding/v1`

#### Tags

- Geocoding
- Location

#### Properties

- [Documentation](https://developer.mapquest.com/documentation/geocoding-api/)
- [Postman Collection](collections/mapquest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapquest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MapQuest Static Map API

The MapQuest Static Map API returns a map image based on specified parameters including center, zoom, size, and map type.

- **Human URL:** [https://developer.mapquest.com/documentation/static-map-api/v5/](https://developer.mapquest.com/documentation/static-map-api/v5/)
- **Base URL:** `https://www.mapquestapi.com/staticmap/v5`

#### Tags

- Maps
- Static Maps

#### Properties

- [Documentation](https://developer.mapquest.com/documentation/static-map-api/v5/)
- [Postman Collection](collections/mapquest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapquest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MapQuest Traffic API

The MapQuest Traffic API returns traffic incidents for a specified bounding box in JSON or XML formats, including road construction and collisions.

- **Human URL:** [https://developer.mapquest.com/documentation/traffic-api/](https://developer.mapquest.com/documentation/traffic-api/)
- **Base URL:** `https://www.mapquestapi.com/traffic/v2`

#### Tags

- Incidents
- Traffic

#### Properties

- [Documentation](https://developer.mapquest.com/documentation/traffic-api/)
- [Reference](https://developer.mapquest.com/documentation/api/traffic/incidents/get.html)
- [Postman Collection](collections/mapquest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapquest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MapQuest Search API

The MapQuest Search API supports radius, rectangle, polygon, and corridor searches against MapQuest hosted data tables, returning matching points of interest with attributes.

- **Human URL:** [https://developer.mapquest.com/documentation/searchapi/](https://developer.mapquest.com/documentation/searchapi/)
- **Base URL:** `https://www.mapquestapi.com/search/v2`

#### Tags

- Points of Interest
- Search

#### Properties

- [Documentation](https://developer.mapquest.com/documentation/searchapi/)
- [Postman Collection](collections/mapquest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapquest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MapQuest Place Search API

The MapQuest Place Search API returns places matching a search query, with support for category, location, and bounding-box filtering.

- **Human URL:** [https://developer.mapquest.com/documentation/place-search-api/v5/](https://developer.mapquest.com/documentation/place-search-api/v5/)
- **Base URL:** `https://www.mapquestapi.com/search/v5`

#### Tags

- Place Search
- Points of Interest
- Search

#### Properties

- [Documentation](https://developer.mapquest.com/documentation/place-search-api/v5/)
- [Postman Collection](collections/mapquest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapquest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MapQuest Search Ahead API

The MapQuest Search Ahead API delivers prediction-based search suggestions as users type, supporting addresses, places, categories, and admin areas.

- **Human URL:** [https://developer.mapquest.com/documentation/searchahead-api/v5/](https://developer.mapquest.com/documentation/searchahead-api/v5/)
- **Base URL:** `https://www.mapquestapi.com/search/v5`

#### Tags

- Autocomplete
- Search
- Search Ahead

#### Properties

- [Documentation](https://developer.mapquest.com/documentation/searchahead-api/v5/)
- [Postman Collection](collections/mapquest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapquest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MapQuest Geolocation API

The MapQuest Geolocation API returns the approximate location of a device based on cell tower and Wi-Fi access point information.

- **Human URL:** [https://developer.mapquest.com/documentation/geolocation-api/](https://developer.mapquest.com/documentation/geolocation-api/)
- **Base URL:** `https://www.mapquestapi.com/geolocation/v1`

#### Tags

- Geolocation
- Location

#### Properties

- [Documentation](https://developer.mapquest.com/documentation/geolocation-api/)
- [Postman Collection](collections/mapquest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapquest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MapQuest Icons API

The MapQuest Icons API serves customizable map marker icons for use with MapQuest static and interactive maps.

- **Human URL:** [https://developer.mapquest.com/documentation/icons-api/](https://developer.mapquest.com/documentation/icons-api/)
- **Base URL:** `https://www.mapquestapi.com/icons/v2`

#### Tags

- Icons
- Maps

#### Properties

- [Documentation](https://developer.mapquest.com/documentation/icons-api/)
- [Postman Collection](collections/mapquest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapquest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MapQuest Data Manager API

The MapQuest Data Manager API allows developers to upload, manage, and query custom hosted data tables for use with MapQuest search and mapping services.

- **Human URL:** [https://developer.mapquest.com/documentation/data-manager-api/v2/](https://developer.mapquest.com/documentation/data-manager-api/v2/)
- **Base URL:** `https://www.mapquestapi.com/datamanager/v2`

#### Tags

- Custom Data
- Data Management

#### Properties

- [Documentation](https://developer.mapquest.com/documentation/data-manager-api/v2/)
- [Postman Collection](collections/mapquest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mapquest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/MapQuest)
- [LinkedIn](https://www.linkedin.com/company/mapquest)
- [Portal](https://developer.mapquest.com/)
- [Getting Started](https://developer.mapquest.com/documentation/)
- [Sign Up](https://developer.mapquest.com/plan_purchase/steps/business_edition/business_edition_free/register)
- [Login](https://developer.mapquest.com/user/login)
- [Support](https://developer.mapquest.com/support/)
- [Terms of Service](https://hello.mapquest.com/terms-of-use)
- [Privacy Policy](https://hello.mapquest.com/privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
