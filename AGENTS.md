# Valyu Publisher API Docs

## About this project

- Documentation site for the Valyu Publisher Analytics API
- Built on [Mintlify](https://mintlify.com) with the "aspen" theme
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- OpenAPI spec at `api-reference/openapi.yaml`
- Run `mint dev` to preview locally

## Terminology

- Use "publisher" not "seller" in user-facing docs (even though API paths use "seller")
- Use "API key" not "token" or "credential"
- Use "retrieval" for when a buyer's query returns publisher content
- Use "earnings" not "revenue" for publisher income

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for endpoints, parameters, key prefixes (`vypub_`)
- All code examples in three languages: cURL, Python, JavaScript

## Content boundaries

- Document the Publisher Analytics API only (not the main Valyu Search API)
- Don't document internal dashboard implementation details
- Don't expose infrastructure details (Lambda function names, DynamoDB table names)
- Reference the publisher dashboard for key management, not internal APIs
