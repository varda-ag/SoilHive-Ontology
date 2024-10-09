# SoilHive Ontology Details

This document outlines the key ontologies used within the SoilHive system, as well as any missing concepts and custom ontologies that will be developed.

## External Ontologies

| **Sub-domain**               | **Description**                                              | **Standards**                 | **Candidate Ontologies**                         |
|------------------------------|--------------------------------------------------------------|-------------------------------|--------------------------------------------------|
| **Upper Ontology**            | Basic formal ontology                                        | ISO 21838-2                    | Basic formal ontology                            |
| **Observations and Measurements** | Standards for observations and measurements                    | ISO 19156:2023                 | Semantic Sensor Network (SSN), OGC OM Extensions |
| **Provenance**                | Tracking the origin and history of data                      | PROV-O                         | PROV Ontology                                    |
| **Location**                  | Geographical referencing                                     | ISO 19112:2019                 | GeoSPARQL                                        |
| **Citation**                  | Guidelines for citations                                     | ISO 690:2021                   | CiTO (Citation Typing Ontology)                  |
| **Quantities and Units**      | Units and measurements for soil data                         | QUDT, UO, OM                   | QUDT, OM (Ontology of Units of Measure)          |
| **Soil Functions and Properties** | Soil quality and functions                                     | ISO 28258:2013                 | GloSIS, ENVO                                     |
| **Data Catalog**              | Cataloging and organizing datasets                           | DataCite                       | DataCite Ontology                                |
| **Land Use**                  | Classification of land use                                   | CORINE                         | CORINE                                           |
| **Plant Information**         | Information about plant biology and taxonomy                 | Plant Ontology, Crop Ontology  | PO, Crop Ontology                                |
| **Agronomic Practices**       | Practices and techniques for managing land and crops         | AGRO, DEMETER                  | AGRO, DEMETER                                    |
| **Fertilizers and Chemicals** | Chemicals used in agriculture                                | ChEBI                          | ChEBI                                            |
| **Roles in Agronomy**         | Roles and activities in agronomy                             | AGRO, DEMETER                  | AGRO, DEMETER                                    |
| **Weather and Climate**       | Information about weather and climate                        | ENVO                           | ENVO (TBD)                                       |
| **Water Management**          | Systems and practices for water resource management          | N/A                            | To be developed                                  |
| **Biodiversity**              | Biodiversity data standards                                  | N/A                            | TDWG, DWC                                        |

## Custom Ontologies

In addition to using existing ontologies, we will also create several custom snippets to fill specific gaps. This includes:

- **Global Field ID**: A custom ontology for tracking and managing global field identifiers.
- **Water Management**: Custom ontology extensions to capture water management practices relevant to soil data.
- **Other Soil-related Ontologies**: As we identify additional gaps in existing ontologies, we will create new components to fill these needs.

For more details on each external ontology, including links to relevant documentation and standards, see the list below:

- [GloSIS Soil Ontology](https://glosis-ld.github.io/glosis/)
- [AGROVOC Thesaurus](https://agrovoc.fao.org/browse/agrovoc/en/)
- [ISO Standards](https://www.iso.org/)
- [Semantic Sensor Network Ontology](https://www.w3.org/TR/vocab-ssn/)
- [PROV Ontology](https://www.w3.org/TR/prov-o/)
- [GeoSPARQL](https://www.ogc.org/standard/geosparql/)

