# SoilHive Ontology Details

This document outlines the key ontologies used within the SoilHive system, as well as any missing concepts and custom ontologies that will be developed.

## External Ontologies

| **Sub-domain**               | **Description**                                              | **Standards**                 | **Ontologies**                         |
|------------------------------|--------------------------------------------------------------|-------------------------------|--------------------------------------------------|
| **Upper Ontology**            | Basic formal ontology                                        | [ISO 21838-2](https://www.iso.org/standard/74572.html)   | [Basic formal ontology](https://basic-formal-ontology.org/)                           |
| **Observations and Measurements** | Standards for observations and measurements                    | [ISO 19156:2023](https://varda.atlassian.net/wiki/spaces/GSP/pages/13573259323)                 | [Semantic Sensor Network (SSN)](https://www.w3.org/TR/vocab-ssn/), [Extensions to the Semantic Sensor Network Ontology](https://w3c.github.io/sdw-sosa-ssn/ssn-extensions/), [Observations, Measurements, and Samples](https://www.ogc.org/standard/om/) |
| **Provenance**                | Tracking the origin and history of data                      |                   | [PROV Ontology](https://www.w3.org/TR/prov-o/)                                    |
| **Location**                  | Geographical referencing                                     | [ISO 19112:2019](https://www.iso.org/standard/70742.html)                 |                                         |
| **Citation**                  | Guidelines for citations                                     | [ISO 690:2021](https://www.iso.org/standard/72642.html)                   | [CiTO (Citation Typing Ontology)](https://sparontologies.github.io/cito/current/cito.html)                  |
| **Quantities and Units**      | Units and measurements for soil data                         |               | [QUDT](https://www.qudt.org/)         |
| **Soil Functions and Properties** | Soil quality and functions                               | [ISO 28258:2013](https://www.iso.org/standard/44595.html)                 | [GloSIS](https://glosis-ld.github.io/glosis/)                                     |
| **Data Catalog**              | Cataloging and organizing datasets                           |                        | [DataCite Ontology](https://sparontologies.github.io/datacite/current/datacite.html)                                |
| **Land Use**                  | Classification of land use                                   |                          | [CORINE](https://land.copernicus.eu/content/corine-land-cover-nomenclature-guidelines/html/index.html)                                           |
| **Plant Information**         | Information about plant biology and taxonomy                 |                    | [PO](https://bioportal.bioontology.org/ontologies/PO/?p=classes&conceptid=root), [Crop Ontology](https://www.cropontology.org/)                                |
| **Agronomic Practices**       | Practices and techniques for managing land and crops         |                    | [AGRO](https://www.ebi.ac.uk/ols4/ontologies/agro), [DEMETER](https://github.com/rapw3k/DEMETER)                                    |
| **Fertilizers and Chemicals** | Chemicals used in agriculture                                |                    | [ChEBI](https://www.ebi.ac.uk/chebi/aboutChebiForward.do)                                            |
| **Roles in Agronomy**         | Roles and activities in agronomy                             |                    | [AGRO](https://www.ebi.ac.uk/ols4/ontologies/agro), [DEMETER](https://github.com/rapw3k/DEMETER)|
| **Weather and Climate**       | Information about weather and climate                        |                    | [ENVO](https://sites.google.com/site/environmentontology/home)                                       |
| **Water Management**          | Systems and practices for water resource management          |                    |                                 |
| **Biodiversity**              | Biodiversity data standards                                  |                    |                                      |

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
- [PROV Ontology](https://www.w3.org/TR/prov-o/)ß
- [GeoSPARQL](https://www.ogc.org/standard/geosparql/)

