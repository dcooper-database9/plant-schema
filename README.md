## Plant Schema (`.plant`)

An open-source, standardized data format designed to solve the fragmentation and regional subjectivity of consumer gardening data across the web. Moving away from flat, static databases, the `.plant` format treats every plant profile as an authoritative observation tied to a specific geographical scope, taxonomic rank, and author provenance.

### Core Architectural Features
* **Provenance & Author Tracking:** Explicitly records who created the profile and their organization to enable trust grading across applications.
* **Rigorous Taxonomic Scope:** Decomposes plant identity from genus down to cultivar level, complete with botanical author citations and optional mapping to global registries like World Flora Online (WFO) or IPNI via `taxonId`.
* **Geographic & Climate Scoping:** Anchors care requirements to specific regions, countries, postal codes, and USDA hardiness zones.
* **Lightweight Semantic Codes:** Replaces ambiguous display strings with strict XSD enumerations for sunlight (`FSUN`, `PSHD`, etc.) and moisture/soil conditions (`WDRN`, `SOGG`, `BOGG`, etc.) to streamline database filtering and multi-language translation.

