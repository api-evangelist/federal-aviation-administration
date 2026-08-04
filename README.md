# Federal Aviation Administration (federal-aviation-administration)

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

The Federal Aviation Administration (FAA) is the U.S. Department of Transportation agency responsible for the regulation and oversight of civil aviation. The FAA publishes a range of public data products and APIs covering airport status, NOTAMs, aeronautical information, airmen and aircraft registries, and System Wide Information Management (SWIM) feeds for air traffic operations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/federal-aviation-administration/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Aviation, Federal Government

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-04-28

## APIs

### FAA NOTAM
The FAA NOTAM API provides access to Notices to Air Missions (NOTAMs), which are time-critical aeronautical information that could affect a pilot's decision to make a flight. The API allows developers to query active NOTAMs by location, type, and effective date for use in flight planning and situational awareness applications.

**Human URL:** [https://api.faa.gov/notamapi/](https://api.faa.gov/notamapi/)

**Base URL:** https://external-api.faa.gov/notamapi/v1

#### Tags:

 - Aeronautical Information, Air Traffic, NOTAM

#### Properties

- [Documentation](https://api.faa.gov/notamapi/)

### FAA Airport Status
The FAA Airport Status Web Service (ASWS) provides current airport conditions, including delays and ground stops, for major United States airports. Developers can use the service to retrieve real-time status information for use in flight planning, traveler-facing applications, and operational dashboards.

**Human URL:** [https://www.faa.gov/data_research/aviation_data_statistics](https://www.faa.gov/data_research/aviation_data_statistics)

**Base URL:** https://soa.smext.faa.gov/asws

#### Tags:

 - Airport, Air Traffic, Delays

#### Properties

- [Documentation](https://www.faa.gov/data_research/aviation_data_statistics)

### FAA NASR Subscription
The FAA National Airspace System Resources (NASR) Subscription provides authoritative aeronautical data covering airports, navigation aids, airways, fixes, and special-use airspace on a 28-day publication cycle. The data is the source of truth used to update aeronautical charts and flight planning systems.

**Human URL:** [https://nfdc.faa.gov/nfdcApps/services/ajv5/airportSubscriberFile.jsp](https://nfdc.faa.gov/nfdcApps/services/ajv5/airportSubscriberFile.jsp)

#### Tags:

 - Aeronautical Information, Airports, Navigation

#### Properties

- [Documentation](https://nfdc.faa.gov/nfdcApps/services/ajv5/airportSubscriberFile.jsp)

### FAA Airmen Registry
The FAA Airmen Registry provides downloadable data on certificated pilots and other airmen in the United States, including pilot certificates, ratings, and medical certificates. The dataset supports verification, research, and analytics use cases.

**Human URL:** [https://www.faa.gov/licenses_certificates/airmen_certification/releasable_airmen_download](https://www.faa.gov/licenses_certificates/airmen_certification/releasable_airmen_download)

#### Tags:

 - Airmen, Certification, Pilots

#### Properties

- [Documentation](https://www.faa.gov/licenses_certificates/airmen_certification/releasable_airmen_download)

### FAA Aircraft Registry
The FAA Aircraft Registry provides downloadable data on civil aircraft registered in the United States, including registration, ownership, and airworthiness information. The dataset is widely used for safety analysis, fleet research, and aircraft tracking applications.

**Human URL:** [https://www.faa.gov/licenses_certificates/aircraft_certification/aircraft_registry/releasable_aircraft_download](https://www.faa.gov/licenses_certificates/aircraft_certification/aircraft_registry/releasable_aircraft_download)

#### Tags:

 - Aircraft, Registration, Certification

#### Properties

- [Documentation](https://www.faa.gov/licenses_certificates/aircraft_certification/aircraft_registry/releasable_aircraft_download)

### FAA System Wide Information Management
The FAA System Wide Information Management (SWIM) program is a service-oriented information sharing platform that delivers real-time National Airspace System data to authorized consumers. SWIM publishes message-oriented data streams covering flight, weather, surveillance, and aeronautical information through a common infrastructure.

**Human URL:** [https://www.faa.gov/air_traffic/technology/swim](https://www.faa.gov/air_traffic/technology/swim)

#### Tags:

 - Air Traffic, Real-Time, System Wide Information Management

#### Properties

- [Documentation](https://www.faa.gov/air_traffic/technology/swim)

## Common Properties

- [Website](https://www.faa.gov/)
- [Documentation](https://www.faa.gov/data_research)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
