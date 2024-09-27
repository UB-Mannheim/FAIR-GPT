# FAIR GPT

A documentation for [FAIR GPT](https://chat.openai.com/g/g-BkMR28wlV-fair), an AI assistant focused on guiding researchers and data stewards in making their datasets compliant with the FAIR (Findable, Accessible, Interoperable, and Reusable) principles.

## Features

FAIR GPT offers the following features:

- **Metadata Review and Recommendations:** Analyzes dataset metadata for compliance with international standards (DataCite, Dublin Core, Schema.org) and offers enhancements to ensure datasets are easily findable and identifiable.
- **Data Structure Guidance:** Provides advice on data organization, including naming conventions and file structures, to enhance data accessibility and usability.
- **Documentation Assistance:** Helps in creating detailed documentation that covers data collection, processing, anonymization, and usage, including exemplary readme files to accompany datasets.
- **Repository Recommendations:** Identifies appropriate data repositories for long-term storage, taking into account the subject area and specific data types, to ensure datasets are preserved in accessible and citable forms.
- **FAIR Principles Evaluation:** Employs advanced algorithms and external APIs to assess and score datasets' adherence to FAIR principles, offering a clear pathway toward improvement.
- **Customized Training and Education:** Provides tailored training sessions and educational resources on data management best practices, specific to the user's field or data type, promoting a deeper understanding of FAIR principles.
- **Knowledge Graph Integration:** Advises on linking dataset metadata with knowledge graphs like Wikidata, enhancing interoperability and the semantic enrichment of data.
- **Legal and Ethical Guidance:** Offers recommendations on licensing, data protection, and ethical considerations to ensure data sharing complies with legal standards and respects privacy.
- **Data Policy Consultation:** Assists organizations in developing or refining their data policies to support FAIR data management and sharing practices.
- **Data Paper Publication Support:** Recommends suitable data journals for publishing data papers, increasing the visibility and citation of datasets.
- **Interactive FAIRness Assessment Tool:** Includes an interactive tool for users to self-assess their datasets' FAIRness, providing instant feedback and actionable advice for each FAIR principle.
- **Data management planning:** Creates a data management plan using the metadata of data.

## Getting Started
To get started with FAIR GPT, follow these steps:
1. **Open [FAIR GPT](https://chat.openai.com/g/g-BkMR28wlV-fair)**
2. **Usage scenarios:**
   * Upload you metadata or part of data. Ask for help.
   * Copy and paste your metadata or data into a prompt. Ask for help.
   * Add a link to your data. Ask for assessment.
   * Ask whatever you want about FAIR data.
   * Ask "create data and code availability statements for my data and codes".
   * Ask "create an RDM part for my research project proposal".

## The uploaded knowledge

* [H2020 Programme Guidelines on FAIR Data Management in Horizon 2020](https://ec.europa.eu/research/participants/data/ref/h2020/grants_manual/hi/oa_pilot/h2020-hi-oa-data-mgt_en.pdf)
* ["Turning FAIR into reality" Final report and action plan from the European Commission expert group on FAIR data](https://data.europa.eu/doi/10.2777/1524)
* [Awesome-RDM GitHub Repo](https://github.com/UB-Mannheim/awesome-RDM)

## Actions (External APIs)

* [re3data Repositories API](https://www.re3data.org/api/beta): This API provides access to repository data from re3data.org
* [FAIR Enough API](https://api.fair-enough.semanticscience.org): API for evaluating resources with FAIR Enough service
* [Wikidata API](https://www.wikidata.org/w/api.php): Gets Wikidata QIDs for a given label (`wbgetentities`)
* [TIB Central Terminology Service Search API](https://service.tib.eu/ts4tib/api): API for free text search over the ontologies
* [FAIR-Checker](https://fair-checker.france-bioinformatique.fr): FAIR-assessment tool with API. Paper: Gaignard, A., Rosnet, T., de Lamotte, F., Lefort, V., & Devignes, M. (2023). FAIR-Checker: supporting digital resource findability and reuse with Knowledge Graphs and Semantic Web standards. Journal of Biomedical Semantics, 14. https://doi.org/10.1186/s13326-023-00289-5

## How to Contribute
If you're interested in improving FAIR GPT, please open an issue or make a pull request.

## License
The documentation for FAIR GPT is available under the [CC0](https://creativecommons.org/public-domain/cc0) license.

## Presentations

* Shigapov, R. (2023, December 15). Optimizing FAIR data sharing with ChatGPT. ENGAGE.EU Webinar on FAIR data, Online. Zenodo. https://doi.org/10.5281/zenodo.10378143
* Shigapov, R. (2024, February 15). ChatGPT for FAIR Research Data. Research Data Management Seminars at the University of Mannheim, Online. Zenodo. https://doi.org/10.5281/zenodo.10664554
