# Climeworks

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

Climeworks AG is a Swiss carbon dioxide removal company founded in 2009 as an ETH Zurich spin-off by Christoph Gebald and Jan Wurzbacher. It designs, builds and operates direct air capture (DAC) plants that filter CO2 out of ambient air and permanently mineralize it underground with storage partners such as Carbfix in Iceland — the Orca and Mammoth facilities. Through Climeworks Solutions it also sells risk-mitigated carbon removal portfolios blending its own DAC removals with certified third-party suppliers, tracked by corporate buyers in an online customer platform.

- https://climeworks.com/

## API surface

**None.** As of the 2026-08-01 enrichment pass Climeworks publishes no public API, no developer portal and no machine-readable contract. Contract discovery probed `/openapi.json`, `/swagger.json`, `/api-docs`, `/.well-known/*` (security.txt, openid-configuration, oauth-authorization-server, api-catalog, ai-plugin.json, agent-card.json, agent.json) and `/llms.txt` on `climeworks.com`, and found no `api.`, `developer.`, `docs.` or `status.` subdomain in DNS. See `well-known/climeworks-well-known.yml` for the recorded statuses.

The only authenticated machine surface on the domain is `platform.climeworks.com`, a Salesforce Experience Cloud customer portal where buyers track carbon removal orders; its API paths are Salesforce's own and are login-gated. Programmatic purchase of Climeworks removals happens through third-party carbon marketplaces, not through a Climeworks API.

## Artifacts

| Artifact | File |
|---|---|
| Packages | `packages/climeworks-packages.yml` |
| Well-known probe | `well-known/climeworks-well-known.yml` |
| Conformance (CDR standards) | `conformance/climeworks-conformance.yml` |
| Domain security | `security/climeworks-domain-security.yml` |
| llms.txt | `llms/climeworks-llms.txt` |
