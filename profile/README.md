# JunctionIO

Junction is an open source webhook and event routing platform.

## Components

| Repo | Language | Description |
|------|----------|-------------|
| [api](https://github.com/JunctionIO/api) | PHP | HTTP API — event ingest, destination management, delivery status |
| [cli](https://github.com/JunctionIO/cli) | PHP | CLI — database migrations and operator setup |
| [http-destination](https://github.com/JunctionIO/http-destination) | Go | Worker — delivers events via outbound HTTP POST |
| [system-worker](https://github.com/JunctionIO/system-worker) | Go | Worker — processes delivery status updates |
