# Climeworks

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
