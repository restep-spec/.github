# Restep

An open specification for HTTP APIs with JSON, at REST level 2½, and the tools to build, check and
use those APIs. Read the specification at **<https://restep.wubytes.com/1/>** ([en español](https://restep.wubytes.com/es/1/)).

## Start here

- **Read the spec:** [`spec`](https://github.com/restep-spec/spec), where issues and proposals about Restep go.
- **Check an API:** [`restep-check`](https://github.com/restep-spec/restep-check) (`npx restep-check https://api.example.com/`), or
  [`restep-action`](https://github.com/restep-spec/restep-action) to run it on every pull request.
- **Build an API:** [`restep-server`](https://github.com/restep-spec/restep-server) as a library, or the agent skills in [`skills`](https://github.com/restep-spec/skills).
- **Try one:** the demo API at <https://demo.restep.wubytes.com/>.

## Tools

| Repository | What it does |
|---|---|
| [`restep-check`](https://github.com/restep-spec/restep-check) | Conformance checker: tries every requirement the API announces |
| [`restep-action`](https://github.com/restep-spec/restep-action) | GitHub Action: restep-check and restep-diff on each pull request |
| [`restep-diff`](https://github.com/restep-spec/restep-diff) | Compares two discovery documents and classifies each change as compatible or breaking |
| [`restep-from-openapi`](https://github.com/restep-spec/restep-from-openapi) | Says what an OpenAPI-described API lacks to follow Restep and drafts its discovery document |
| [`restep-server`](https://github.com/restep-spec/restep-server) | Server library: you write the data access, it does the rest of Restep |
| [`restep-mock`](https://github.com/restep-spec/restep-mock) | A fake Restep API from a discovery document |
| [`restep-mcp`](https://github.com/restep-spec/restep-mcp) | MCP server for any Restep API: a few generic tools built from its discovery document |
| [`restep-proxy`](https://github.com/restep-spec/restep-proxy) | Reverse proxy that watches the Restep contract in real traffic |
| [`restep-explorer`](https://github.com/restep-spec/restep-explorer) | Web explorer for any Restep API, built from its discovery document |
| [`restep-cli`](https://github.com/restep-spec/restep-cli) | Generic command line client for any Restep API |
| [`restep-ts`](https://github.com/restep-spec/restep-ts) | Typed TypeScript client whose response types follow `fields` and `include` |
| [`restep-py`](https://github.com/restep-spec/restep-py) | Generic Python client, sync and async |
| [`restep-sync`](https://github.com/restep-spec/restep-sync) | Offline-first client: a local replica with the `sync` profile and a write queue |
| [`restep-export`](https://github.com/restep-spec/restep-export) | Example requests for .http, Bruno and Postman from a discovery document |
| [`skills`](https://github.com/restep-spec/skills) | Agent skills: `restep-design` and `restep-review` |

The tools are developed alongside the specification and mirrored here, each with its own tests
against the reference server. Most of their READMEs are in Spanish. Everything is MIT licensed.
