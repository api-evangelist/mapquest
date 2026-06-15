# MapQuest (mapquest)

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
