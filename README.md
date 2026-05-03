# Sigma-Aldrich (sigma-aldrich)
Sigma-Aldrich was a leading life science and high technology company whose biochemical and organic chemical products, kits, and services are used in scientific research, including genomics, proteomics, and drug discovery. Acquired by Merck KGaA in 2015, Sigma-Aldrich now operates as part of MilliporeSigma in North America, continuing to provide the world's largest catalog of research chemicals, biochemicals, and laboratory supplies to researchers globally.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/sigma-aldrich/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Life Science, Chemistry, Biochemistry, Laboratory, Research, Chemical Catalog

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## APIs

### Sigma-Aldrich Product Search API
The Sigma-Aldrich Product Search API provides programmatic access to the Sigma-Aldrich product catalog containing hundreds of thousands of research chemicals, biochemicals, reagents, and laboratory supplies. Researchers and LIMS systems can query products by catalog number, CAS number, or keyword and retrieve product details, safety data, pricing, and availability.

**Human URL:** [https://www.sigmaaldrich.com/US/en/technical-documents/technical-article/chemistry/labware/sigma-aldrich-developer-portal](https://www.sigmaaldrich.com/US/en/technical-documents/technical-article/chemistry/labware/sigma-aldrich-developer-portal)

**Base URL:** https://api.sigmaaldrich.com/v1

#### Tags:

 - Life Science, Chemistry, Products, Search

#### Properties

- [Documentation](https://www.sigmaaldrich.com/US/en/technical-documents/technical-article/chemistry/labware/sigma-aldrich-developer-portal)
- [OpenAPI](openapi/sigma-aldrich-product-openapi.yml)
- [SpectralRules](rules/sigma-aldrich-rules.yml)
- [Capabilities](capabilities/chemical-research.yaml)
- [JSONSchema](json-schema/sigma-aldrich-product-schema.json)
- [JSONLD](json-ld/sigma-aldrich-context.jsonld)
- [Vocabulary](vocabulary/sigma-aldrich-vocabulary.yml)

### Sigma-Aldrich Chemical Structure Search API
Search the Sigma-Aldrich catalog by chemical structure using SMILES or InChI notation with exact, substructure, and similarity search modes.

**Human URL:** [https://www.sigmaaldrich.com/US/en/support/contact-us](https://www.sigmaaldrich.com/US/en/support/contact-us)

#### Tags:

 - Chemistry, Cheminformatics, Structure Search, SMILES

### Sigma-Aldrich Safety Data Sheet API
Retrieve GHS-compliant Safety Data Sheets for regulatory compliance and laboratory safety management in multiple languages.

**Human URL:** [https://www.sigmaaldrich.com/US/en/support/sds-portal](https://www.sigmaaldrich.com/US/en/support/sds-portal)

#### Tags:

 - Safety, SDS, GHS, Compliance

## Common Properties

- [Website](https://www.sigmaaldrich.com/)
- [ProductCatalog](https://www.sigmaaldrich.com/US/en/catalog)
- [SDS Portal](https://www.sigmaaldrich.com/US/en/support/sds-portal)
- [Developer Portal](https://www.sigmaaldrich.com/US/en/technical-documents/technical-article/chemistry/labware/sigma-aldrich-developer-portal)
- [Parent Company](https://www.merckgroup.com/)

## Capabilities

### Workflow Capabilities

- [Chemical Research](capabilities/chemical-research.yaml) — Unified workflow for chemical research and procurement: catalog search, CAS lookup, structure search, safety data sheets, and pricing.

### Shared API Definitions

- [Sigma-Aldrich Products](capabilities/shared/sigma-aldrich-products.yaml) — Per-API shared definition for the Sigma-Aldrich Product Search API

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
