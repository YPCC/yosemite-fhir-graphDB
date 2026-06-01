# Yosemite FHIR RDF + GraphDB

GraphDB version of the Yosemite Project FHIR RDF tutorial using OWL 2 RL reasoning.

## Setup

1. Clone this repo
2. Create GraphDB repository `yosemite-combined` with `owl2-rl` ruleset
3. Import the TTL files in this order:
   - fhir.ttl
   - w5.ttl
   - codesystem-diagnostic-report-status.ttl
   - snomed_cancer_subset.ttl
   - snomed_thyroid_subset.ttl
   - diagnosticreport-example-f201-brainct.ttl
   - diagnosticreport-example-dxreport117-thyroidtumor.ttl
   - combined-inference.ttl

## Queries
See the `queries/` folder for verification and decision tree queries.

## Original Data
Clone https://github.com/yosemiteproject/Tutorial-FHIR-RDF-as-a-Bridge.git for the base TTL files.