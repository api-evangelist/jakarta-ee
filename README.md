# Jakarta EE (jakarta-ee)

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

Jakarta EE is the open source successor to Java EE, providing a set of specifications for enterprise Java development. Jakarta EE is developed under the Eclipse Foundation and includes specifications for web services, messaging, persistence, security, and other enterprise computing needs.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/jakarta-ee/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Jakarta EE, Java, Enterprise, Standards

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### Jakarta RESTful Web Services
Jakarta RESTful Web Services (formerly JAX-RS) is the API specification for developing web services that follow the REST architectural pattern. It defines a set of Java APIs and annotations that enable the development and deployment of RESTful web services on the Jakarta EE platform.

**Human URL:** [https://jakarta.ee/specifications/restful-ws/](https://jakarta.ee/specifications/restful-ws/)

#### Tags:

 - REST, Web Services, Specification

#### Properties

- [Documentation](https://jakarta.ee/specifications/restful-ws/)
- [GitHubRepository](https://github.com/jakartaee/rest)

### Jakarta JSON Processing
Jakarta JSON Processing (formerly JSON-P) provides an API to parse, generate, transform, and query JSON documents. It includes a streaming API similar to StAX and an object model API similar to DOM for working with JSON data in Jakarta EE applications.

**Human URL:** [https://jakarta.ee/specifications/jsonp/](https://jakarta.ee/specifications/jsonp/)

#### Tags:

 - JSON, Parsing, Specification

#### Properties

- [Documentation](https://jakarta.ee/specifications/jsonp/)
- [GitHubRepository](https://github.com/jakartaee/jsonp-api)

### Jakarta JSON Binding
Jakarta JSON Binding (formerly JSON-B) is a binding framework for converting Java objects to and from JSON documents. It provides a default mapping between classes and JSON, with the ability to customize the mapping process through a comprehensive configuration API.

**Human URL:** [https://jakarta.ee/specifications/jsonb/](https://jakarta.ee/specifications/jsonb/)

#### Tags:

 - JSON, Binding, Specification

#### Properties

- [Documentation](https://jakarta.ee/specifications/jsonb/)
- [GitHubRepository](https://github.com/jakartaee/jsonb-api)

### Jakarta WebSocket
Jakarta WebSocket defines a standard API for creating server and client endpoints that communicate using the WebSocket protocol (RFC 6455). It enables full-duplex, bidirectional communication between clients and servers over a single TCP connection in Jakarta EE applications.

**Human URL:** [https://jakarta.ee/specifications/websocket/](https://jakarta.ee/specifications/websocket/)

#### Tags:

 - WebSocket, Streaming, Specification

#### Properties

- [Documentation](https://jakarta.ee/specifications/websocket/)
- [GitHubRepository](https://github.com/jakartaee/websocket)

### Jakarta Servlet
Jakarta Servlet is a server-side Java API for handling HTTP requests and generating dynamic responses. It provides the foundational programming model for Java-based web applications and underpins many other Jakarta EE web technologies including RESTful Web Services and WebSocket.

**Human URL:** [https://jakarta.ee/specifications/servlet/](https://jakarta.ee/specifications/servlet/)

#### Tags:

 - HTTP, Web, Specification

#### Properties

- [Documentation](https://jakarta.ee/specifications/servlet/)
- [GitHubRepository](https://github.com/jakartaee/servlet)

### Jakarta Validation
Jakarta Validation (formerly Bean Validation) provides an object-level constraint declaration and validation facility through annotations and a runtime API. It is widely used to validate inputs in REST endpoints, persistence entities, and other Jakarta EE components.

**Human URL:** [https://jakarta.ee/specifications/bean-validation/](https://jakarta.ee/specifications/bean-validation/)

#### Tags:

 - Validation, Specification

#### Properties

- [Documentation](https://jakarta.ee/specifications/bean-validation/)
- [GitHubRepository](https://github.com/jakartaee/validation)

## Common Properties

- [Website](https://jakarta.ee/)
- [Specifications](https://jakarta.ee/specifications/)
- [Documentation](https://jakarta.ee/learn/)
- [GitHub Organization](https://github.com/jakartaee)
- [News](https://jakarta.ee/news/)
- [Community](https://jakarta.ee/community/)
- [Eclipse Foundation](https://www.eclipse.org/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
