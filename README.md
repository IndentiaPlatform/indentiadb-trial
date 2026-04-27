# IndentiaDB Trial

Trial image for [IndentiaDB](https://github.com/IndentiaPlatform/IndentiaDB) — Multi-Model Database for Knowledge Graphs & Enterprise AI.

## Quick Start

```bash
docker run -p 7001:7001 -p 9200:9200 ghcr.io/indentiaplatform/indentiadb-trial:latest
```

- **SPARQL / GraphQL / REST / WebSocket** → `http://localhost:7001`
- **Elasticsearch-compatible API** → `http://localhost:9200`
- **Health check** → `http://localhost:7001/health`

## Trial Limitations

This image is a time-limited trial build. The expiry date is baked into the binary at compile time.

For production licensing, contact [indentia.ai](https://indentia.ai).

## Build

The trial image is built automatically by the private GitLab CI pipeline and pushed to:

```
ghcr.io/indentiaplatform/indentiadb-trial:latest
ghcr.io/indentiaplatform/indentiadb-trial:<version>
```

## Documentation

Full documentation at **[dbdocs.indentia.ai](https://dbdocs.indentia.ai)**.

## License

Copyright 2024-2026 Indentia B.V. — Trial use only.

## Ownership and licence status

This repository is controlled by Indentia B.V. for trial or evaluation use. See `NOTICE`, `OWNERSHIP.md`, and `CONTRIBUTING.md`.
