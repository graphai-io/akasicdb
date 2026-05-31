# AkasicDB

AkasicDB is a graph-vector-relational DBMS for enterprise AI. It brings graph traversal, vector search, and SQL query processing into a single PostgreSQL-compatible database environment, so applications can work with relational, graph, and vector data without maintaining separate databases or custom result-merging pipelines.

## Highlights

- **PostgreSQL-compatible workflow**: connect with familiar PostgreSQL clients and enable AkasicDB through the `akasicdb` extension.
- **Unified graph, vector, and relational queries**: combine SQL predicates, graph traversal, and vector similarity search in one database engine.
- **Knowledge graph creation from relational data**: define graph structures over existing relational tables using SQL.
- **Vector search support**: use vector types and indexes including HNSW, Vamana, IVF, and Flat indexes.
- **AI application integrations**: build applications with the AkasicDB Python library, Psycopg3, SQLAlchemy, Django, and LangChain integration.

## Documentation

Published documentation:

<https://graphai-repository.github.io/akasicdb-docs/>

Useful starting points:

- [Overview](https://graphai-repository.github.io/akasicdb-docs/latest/en/getting-started/overview/)
- [Quick Start](https://graphai-repository.github.io/akasicdb-docs/latest/en/getting-started/quick-start/)
- [Installation](https://graphai-repository.github.io/akasicdb-docs/latest/en/installation/installation/)
- [Client Packages](https://graphai-repository.github.io/akasicdb-docs/latest/en/client-packages/)
- [Examples and Tutorials](https://graphai-repository.github.io/akasicdb-docs/latest/en/examples/)
- [Usage](https://graphai-repository.github.io/akasicdb-docs/latest/en/usage/)
- [Release Notes](https://graphai-repository.github.io/akasicdb-docs/latest/en/release-note/)
- [License Information](https://graphai-repository.github.io/akasicdb-docs/latest/en/license/)

## Getting AkasicDB

There are two edition options for getting started with AkasicDB:

- **AkasicDB Community Edition**: a free version for evaluation, learning, and testing. It includes core graph, vector, and relational features with some limitations on scale.

  Available for download at [Docker Hub](https://hub.docker.com/r/graphai/akasicdb-community), but a license file is required to run the container.
  For now, request a license at <akasicdb@graphai.io> manually.

- **AkasicDB Enterprise Edition**: a commercial version with full features, optimizations, and support for production use. Contact us at <akasicdb@graphai.io> for licensing and access.

For complete installation instructions, see [Installation](https://graphai-repository.github.io/akasicdb-docs/latest/en/installation/installation/).

## Support and Feedback

Issue reports, feature requests, and documentation feedback are handled through this repository:

When reporting an issue, include:

- Operating system and AkasicDB version
- Steps to reproduce the issue
- Expected behavior and actual behavior
- SQL examples, logs, or error messages when available

For partnership, sales, licensing, or collaboration inquiries, contact:

<akasicdb@graphai.io>

## License

AkasicDB software is proprietary commercial software. AkasicDB Community Edition is provided for evaluation, learning, and testing under the applicable license terms.

See [License Information](https://graphai-repository.github.io/akasicdb-docs/latest/en/license/index/) for details.
