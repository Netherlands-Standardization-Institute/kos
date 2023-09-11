# NEN Knowledge Organization System

The NEN Knowledge Organization System describes a data model for standardisation bodies based on SKOS. It consists of:

- the [International Classification for Standards](https://www.iso.org/publication/PUB100033.html),
- a catalog with standard documents,
- and a controlled vocabulary with terms and definitions.

It aims to create a datamodel for normalized terms and definitions that can be easily published using [Skosmos](https://skosmos.org). 

**URI**: http://purl.org/nen/kos

**Documentation**: https://data.nen.nl/kos/docs/

**Creator(s):** Robert Matousek

**License:** [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode)


### Publishing terms and definitions as Linked Open Data
Below we list a number of resources to help other standard bodies publish their terms and definitions as Linked Open Data.

### Dataflow
The following diagram is a visual representation of how information flows through the system. 
![](https://raw.githubusercontent.com/Netherlands-Standardization-Institute/kos/main/docs/img/system-diagram.svg)

### Workflow automation and tooling
The following open source projects can execute and automate parts based of the workflow.
  - [Excel2RDF](https://github.com/fair-data-collective/excel2rdf-template): Convert an Excel template to RDF
  - [XML2CSV](https://github.com/Netherlands-Standardization-Institute/xml2csv): Extract terms and definitions from XML using the NISO STS
  - [Github Actions](https://docs.github.com/en/actions): Automate, customize, and execute your workflows in your repository
  - [Skosmos](https://skosmos.org): View terms using an open source web-based SKOS browser and publishing tool

### Example
Examples from the [NEN](https://nen.nl).
- [NEN Thesaurus](https://data.nen.nl/skosmos/vocab/): Search terms and definitions in the browser.
- [NEN controlled vocabulary](https://github.com/Netherlands-Standardization-Institute/controlled-vocabulary): View the controlled vocabulary in RDF.
- [NEN Vocabulary API](https://github.com/Netherlands-Standardization-Institute/openapi)
