# Kevin Zhang

Maintainer of [Semantica](https://github.com/semantica-agi/semantica) and its enterprise edition, a graph-native context and accountability layer for AI systems. I work on turning messy enterprise data into context an agent can actually use and later defend. The enterprise edition is built for regulated industries including finance, healthcare, and law.

[![GitHub stars](https://img.shields.io/github/stars/semantica-agi/semantica?style=flat-square&label=stars&color=FFD700&logo=github)](https://github.com/semantica-agi/semantica/stargazers) [![Forks](https://img.shields.io/github/forks/semantica-agi/semantica?style=flat-square&logo=github)](https://github.com/semantica-agi/semantica/network/members) [![License](https://img.shields.io/github/license/semantica-agi/semantica?style=flat-square)](https://github.com/semantica-agi/semantica/blob/main/LICENSE)

## Impact

Across both repositories I have landed 124 merged changes, 58 in the open-source engine and 66 in the enterprise edition, touching more than 1,500 files. The work covers the full path from data ingestion and OWL/SHACL ontology modeling to retrieval, citation, and the policy and audit layer that decides what an agent is allowed to do.

## Focus

- Ontology lifecycle: bootstrapping domain schemas from extracted data, the draft-to-version flow, SHACL constraint generation and validation, and W3C PROV-O provenance wrappers.
- Trust modeling: gold / silver / bronze / quarantine tiers with citation checks, so a retrieved fact carries its own evidence.
- Graph analytics and retrieval: PageRank and label propagation on the context graph, and semantic retrieval tools exposed over MCP.
- Enterprise governance (closed source): fail-closed Rego/OPA policy gates, fine-grained scopes with no admin wildcard, tenant isolation, retention and legal hold, and auditable erasures recorded on a hash-chained decision log.

## Work

[semantica-agi/semantica](https://github.com/semantica-agi/semantica) | [commits](https://github.com/semantica-agi/semantica/commits?author=pkupt) | [issues I opened](https://github.com/semantica-agi/semantica/issues?q=is%3Aissue+author%3Apkupt)
