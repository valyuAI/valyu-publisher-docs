# Valyu Publisher API Documentation

Documentation site for the Valyu Publisher Analytics API, built with [Mintlify](https://mintlify.com).

## Development

```bash
npm i -g mint
mint dev
```

Open [localhost:3000](http://localhost:3000).

## Deployment

Pushes to `main` auto-deploy via Mintlify GitHub integration.

## Structure

```
/
+-- index.mdx                    # Homepage
+-- quickstart.mdx               # Getting started guide
+-- authentication.mdx           # API key authentication
+-- guides/                      # Conceptual guides
|   +-- usage-analytics.mdx
|   +-- earnings-tracking.mdx
|   +-- data-export.mdx
|   +-- how-it-works.mdx
|   +-- api-keys.mdx
+-- api-reference/               # API endpoint docs
|   +-- overview.mdx
|   +-- openapi.yaml             # OpenAPI 3.1 spec
|   +-- endpoint/
|       +-- seller-usage.mdx
|       +-- seller-earnings.mdx
|       +-- latest-usage.mdx
|       +-- export-analytics.mdx
+-- docs.json                    # Mintlify config (aspen theme)
```
