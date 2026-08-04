# DataDome (datadome)

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

DataDome is a real-time bot and online fraud protection platform that
inspects every web, mobile, and API request and decides — within
milliseconds — whether it should be allowed, challenged, or blocked.
The platform combines a JavaScript tag and mobile SDKs (iOS, Android,
React Native, Flutter) on the client side with 40+ server-side
integrations (Nginx, Apache, IIS, OpenResty, HAProxy, Cloudflare
Workers, AWS CloudFront, Fastly, Bunny, Node.js, Python ASGI, Go,
Ruby, Java, ASP.NET Core, Kong, Apigee, Tyk, Traefik) that forward
signals to DataDome's decisioning service. Products in the platform
include Bot Protect, Account Protect, Ad Protect, Page Protect,
Priority Protect, Agentic Trust (governing AI agent traffic), and
DDoS Protect.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/datadome/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/datadome/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Commercial

## Tags

- Bot Mitigation
- Fraud Protection
- Account Protection
- Ad Fraud
- DDoS
- Real-Time
- Edge Security
- Application Security
- Agentic Trust

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### DataDome Bot Protect

Bot Protect is DataDome's core bot management product, scoring
every request against the platform's threat intelligence and
machine-learning models to classify and block automated traffic
(scraping, credential stuffing, inventory hoarding, fake account
creation, content theft) without adding latency to good traffic.

- **Human URL:** [https://datadome.co/products/bot-protect/](https://datadome.co/products/bot-protect/)
- **Base URL:** `https://datadome.co`

#### Tags

- Bot Management
- Scraping
- Credential Stuffing
- ML

#### Properties

- [Product Page](https://datadome.co/products/bot-protect/)
- [Documentation](https://docs.datadome.co/)
- [Postman Collection](collections/datadome.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadome.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DataDome Account Protect

Account Protect targets account takeover, fake account creation,
and post-login abuse using behavioral, device, and credential
signals layered on top of the Bot Protect decisioning core.

- **Human URL:** [https://datadome.co/products/account-protect/](https://datadome.co/products/account-protect/)
- **Base URL:** `https://datadome.co`

#### Tags

- ATO
- Account Protection
- Fraud

#### Properties

- [Product Page](https://datadome.co/products/account-protect/)
- [Documentation](https://docs.datadome.co/)
- [Postman Collection](collections/datadome.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadome.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DataDome Ad Protect

Ad Protect filters invalid traffic from ad-supported properties
and protects publishers and advertisers from automated click and
impression fraud, leveraging the same signal pipeline as Bot
Protect.

- **Human URL:** [https://datadome.co/products/ad-protect/](https://datadome.co/products/ad-protect/)
- **Base URL:** `https://datadome.co`

#### Tags

- Ad Fraud
- IVT
- Click Fraud

#### Properties

- [Product Page](https://datadome.co/products/ad-protect/)
- [Documentation](https://docs.datadome.co/)
- [Postman Collection](collections/datadome.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadome.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DataDome Page Protect

Page Protect provides client-side security and Magecart / formjacking
defense, inventorying third-party scripts and detecting unauthorized
data exfiltration from sensitive pages such as checkout and account.

- **Human URL:** [https://datadome.co/products/page-protect/](https://datadome.co/products/page-protect/)
- **Base URL:** `https://datadome.co`

#### Tags

- Client-Side Security
- PCI DSS 4
- Magecart
- Supply Chain

#### Properties

- [Product Page](https://datadome.co/products/page-protect/)
- [Documentation](https://docs.datadome.co/)
- [Postman Collection](collections/datadome.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadome.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DataDome Agentic Trust

Agentic Trust is DataDome's product for managing AI-agent traffic,
letting customers identify, authenticate, and govern interactions
from autonomous agents and LLM-driven crawlers against their web
and API surfaces.

- **Human URL:** [https://datadome.co/products/agentic-trust/](https://datadome.co/products/agentic-trust/)
- **Base URL:** `https://datadome.co`

#### Tags

- AI Agents
- LLM
- Agentic Traffic
- Governance

#### Properties

- [Product Page](https://datadome.co/products/agentic-trust/)
- [Documentation](https://docs.datadome.co/)
- [Postman Collection](collections/datadome.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadome.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DataDome DDoS Protect

DDoS Protect mitigates application-layer denial-of-service attacks
using the same edge-distributed signal pipeline as Bot Protect,
defending APIs and web properties against high-volume automated
campaigns.

- **Human URL:** [https://datadome.co/products/ddos-protect/](https://datadome.co/products/ddos-protect/)
- **Base URL:** `https://datadome.co`

#### Tags

- DDoS
- Layer 7
- Availability

#### Properties

- [Product Page](https://datadome.co/products/ddos-protect/)
- [Documentation](https://docs.datadome.co/)
- [Postman Collection](collections/datadome.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadome.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DataDome JavaScript Tag

The DataDome JS tag collects browser, device, and behavioral
signals that are forwarded to the DataDome decisioning service.
The tag is configured per property and loaded asynchronously to
avoid impacting page performance.

- **Human URL:** [https://docs.datadome.co/docs/integration-js-tag](https://docs.datadome.co/docs/integration-js-tag)
- **Base URL:** `https://js.datadome.co`

#### Tags

- JavaScript Tag
- Client Signals
- Frontend

#### Properties

- [Documentation](https://docs.datadome.co/docs/integration-js-tag)
- [Postman Collection](collections/datadome.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadome.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DataDome Server Modules & SDKs

DataDome ships 40+ server-side integrations (web servers, CDNs,
application frameworks, API gateways) that forward each request
to the DataDome decisioning service and apply the returned verdict.
These cover Nginx, Apache, IIS, OpenResty, HAProxy, Cloudflare
Workers, AWS CloudFront, Fastly, Bunny, Node.js, Python ASGI, Go,
Ruby, Java, ASP.NET Core, Kong, Apigee, Tyk, and Traefik.

- **Human URL:** [https://docs.datadome.co/docs/integration-overview](https://docs.datadome.co/docs/integration-overview)
- **Base URL:** `https://docs.datadome.co`

#### Tags

- Server SDK
- CDN
- API Gateway
- Reverse Proxy

#### Properties

- [Documentation](https://docs.datadome.co/docs/integration-overview)
- [GitHub Organization](https://github.com/DataDome)
- [Postman Collection](collections/datadome.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadome.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DataDome Mobile SDKs

Native iOS and Android SDKs (with React Native and Flutter
wrappers) integrate with common HTTP libraries (OkHttp, Alamofire,
Axios, Dio) so DataDome verdicts can be applied to mobile API
traffic, not just web requests.

- **Human URL:** [https://docs.datadome.co/docs/integration-mobile-sdk](https://docs.datadome.co/docs/integration-mobile-sdk)
- **Base URL:** `https://docs.datadome.co`

#### Tags

- Mobile SDK
- iOS
- Android
- React Native
- Flutter

#### Properties

- [Documentation](https://docs.datadome.co/docs/integration-mobile-sdk)
- [GitHub Organization](https://github.com/DataDome)
- [Postman Collection](collections/datadome.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadome.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://datadome.co/)
- [Products](https://datadome.co/products/)
- [Documentation](https://docs.datadome.co/)
- [API Reference](https://docs.datadome.co/reference)
- [Blog](https://datadome.co/blog/)
- [GitHub Organization](https://github.com/DataDome)
- [LinkedIn](https://www.linkedin.com/company/datadome/)
- [Twitter](https://twitter.com/datadome)
- [Status](https://status.datadome.co/)
- [Contact](https://datadome.co/contact/)
- [L L Ms Txt](https://docs.datadome.co/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
