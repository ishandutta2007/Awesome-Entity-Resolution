# Awesome-Entity-Resolution

### Top Entity Resolution Tools Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Entity Resolution, Record Linkage, Identity Resolution, Deduplication & Master Data Management*  
**Last updated: August 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Entity Resolution (ER)**. These tools identify when records from different datasets, databases, applications, or documents refer to the same real-world entity — including people, companies, organizations, addresses, products, accounts, suppliers, and assets.

**Examples** include Senzing, Tamr, Quantexa, Relativity, IBM InfoSphere MDM, Ataccama, Reltio, Precisely, Informatica MDM, DataWalk, and other enterprise identity-resolution and master-data platforms.

Entity resolution is also known as **record linkage, entity matching, identity resolution, data matching, deduplication, fuzzy matching, customer matching, master data matching, and identity intelligence**.

**Open-source emphasis**: This repository heavily emphasizes open-source implementations, libraries, frameworks, and research projects that can be self-hosted and integrated into custom data pipelines. The open-source section includes probabilistic linkage, ML-based matching, blocking, clustering, fuzzy matching, reconciliation, knowledge-graph-based entity resolution, and large-scale data linkage.

The goal is to provide a practical ecosystem map ranging from **enterprise MDM/identity platforms** to **developer-oriented open-source ER libraries**.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Open-Source & Research Projects](#additional-open-source--research-projects)
- [Building a Custom Open-Source Entity Resolution Stack](#building-a-custom-open-source-entity-resolution-stack)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform / Product | Description | Starting Tier Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Senzing](https://senzing.com/)** | Real-time entity resolution and identity intelligence platform focused on resolving people, organizations, and relationships across disparate data sources. Designed to run within an organization's own infrastructure as well as cloud environments. | $58,560/year (for up to 10M Data Source Records) | Free forever SDK license up to 500 records; Free 1-day PoC up to 1,000,000 records; Azure Marketplace trial up to 250,000 records |
| **[Tamr](https://www.tamr.com/)** | AI-native entity resolution and data mastering platform for matching, deduplicating, clustering, scoring, and creating trusted golden records across enterprise datasets. | ~$50,000/year (~$4,166/month, output-based golden record tiers) | 14 to 30-day guided Proof of Concept (PoC) / sandbox evaluation upon sales request (no self-service free tier) |
| **[Quantexa](https://www.quantexa.com/)** | Data and decision intelligence platform centered around dynamic entity resolution, contextual data integration, and knowledge-graph-driven analysis for customers, organizations, transactions, and other entities. | ~$100,000/year (scaled by entity volume and network complexity) | 30-day custom Proof of Value (PoV) / guided sandbox trial upon enterprise engagement (no self-service free tier) |
| **[Relativity](https://www.relativity.com/)** | Legal and investigative data platform with entity-oriented capabilities for identifying and organizing people, organizations, communications, and other entities across large volumes of case data. | RelativityOne starts at ~$30–$40/GB per month with ~$5,000/month platform minimum | 14 to 30-day guided evaluation sandbox upon enterprise inquiry (no self-service free tier) |
| **[IBM InfoSphere Master Data Management](https://www.ibm.com/products/ibm-infosphere-master-data-management)** | Enterprise MDM platform providing matching, reconciliation, governance, and golden-record capabilities across critical master-data domains. | ~$3,500/month (~$42,000/year on IBM Cloud / software license) | 30-day free trial on IBM Cloud with $200 free trial credits across cloud services |
| **[Ataccama ONE](https://www.ataccama.com/)** | Enterprise data management platform combining data quality, MDM, governance, integration, and matching capabilities for creating trusted master records. | ~$30,000/year (~$2,500/month based on named users and managed data objects) | 30-day free trial of Ataccama ONE Cloud platform with sample datasets and data quality checks |
| **[Reltio](https://www.reltio.com/)** | Cloud-native master data and context intelligence platform with AI-powered entity resolution, match-and-merge, survivorship, and real-time golden-record capabilities. | ~$60,000/year (~$5,000/month for Connected Data Platform / Multidomain MDM) | 30-day guided trial / sandbox on AWS/Azure Marketplace upon request (no self-service free tier) |
| **[Precisely](https://www.precisely.com/)** | Data integrity platform offering automated data matching and entity resolution for customers, suppliers, assets, locations, and other enterprise entities. | ~$20,000–$35,000/year for Data Integrity Suite / Spectrum modules | 30-day free trial / interactive developer sandbox for Data Integrity Suite APIs |
| **[Informatica MDM](https://www.informatica.com/products/master-data-management.html)** | Enterprise master data management platform with identity resolution, matching, survivorship, hierarchy management, and golden-record capabilities. | ~$1,250/month ($15,000/year for base IDMC IPU consumption packs); Core licenses from $70,000/year | 30-day free trial on Informatica IDMC with 500 compute hours and up to 10,000 processed rows |
| **[DataWalk](https://datawalk.com/)** | Investigative analytics and decision-intelligence platform combining entity resolution with knowledge graphs, data integration, risk analysis, fraud detection, and investigation workflows. | ~$3,000/month (~$36,000/year) or $50,000 base package deployment | 30-day Proof of Concept (PoC) evaluation environment upon request (no self-service free tier) |
| **[SAP Master Data Governance](https://www.sap.com/products/technology-platform/master-data-governance.html)** | Enterprise master-data governance platform supporting centralized management, matching, validation, consolidation, and governance of business entities. | ~$6,250/month (~$75,000/year for Cloud Edition up to 5,000 master data objects) | 30-day free trial via SAP Business Technology Platform (BTP) / 90-day guided evaluation |
| **[Oracle Customer Data Management](https://www.oracle.com/cx/customer-data-management/)** | Oracle's customer data and master-data capabilities for consolidating customer information, identifying duplicates, and maintaining trusted customer records. | $300 per 1,000 records/month (or $100 per user/month) | 30-day free trial with $300 in Oracle Cloud credits plus access to Oracle Cloud Always Free services |
| **[Salesforce Data Cloud](https://www.salesforce.com/data/)** | Customer data platform with identity resolution capabilities for unifying customer records and creating a consolidated customer profile across data sources. | $60,000/year for Starter Edition (or add-on credit packs from $500 for 100,000 credits) | Free Provisioning SKU for Enterprise/Unlimited Edition customers (includes 250,000 Data Cloud credits and 1 TB storage) |
| **[Microsoft Dynamics 365 Customer Insights](https://www.microsoft.com/dynamics-365/products/customer-insights)** | Customer data platform with data unification and identity-resolution capabilities for combining customer records across enterprise systems. | $1,700/tenant/month (or $1,000/tenant/month attach license for existing Dynamics 365 customers) | 30-day free trial with full access to Customer Insights Data & Journeys (no credit card required) |
| **[Semarchy xDM](https://www.semarchy.com/)** | Model-driven master data management platform providing matching, merging, survivorship, governance, and golden-record management. | ~£40,000/year (~$50,000/year or ~$4,166/month for entry tier up to 50,000 base objects) | 30-day free trial (full-featured downloadable license or cloud marketplace sandbox) |
| **[Stibo Systems STEP](https://www.stibosystems.com/)** | Enterprise master data platform for managing and harmonizing product, customer, supplier, and other business entities across complex data landscapes. | ~$50,000–$75,000/year for Enterprise SaaS tier | 30-day structured Proof of Concept (PoC) / sandbox on request (no self-service free tier) |
| **[Profisee](https://profisee.com/)** | Master data management platform focused on data quality, matching, governance, and trusted golden records. | ~$35,000–$48,000/year (~$3,000/month for MDM Cloud base tier) | 30-day free trial / Fast Track Proof of Concept via Microsoft Azure Marketplace |
| **[Riversand / Syndigo](https://syndigo.com/)** | Enterprise product and master data platform supporting data consolidation, matching, enrichment, and entity-centric management. | ~$25,000–$40,000/year for Multidomain MDM base tier | 14 to 30-day guided interactive demo / sandbox upon request (no self-service free tier) |
| **[Uniserv](https://www.uniserv.com/)** | Data quality and identity matching platform offering address verification, duplicate detection, customer matching, and data cleansing. | ~€500/month (~$540/month or €0.01 per record lookup in batch) | 30-day free trial with up to 500 free test record validation/matching requests |
| **[Melissa](https://www.melissa.com/)** | Data quality platform providing identity resolution, address matching, deduplication, enrichment, and customer-data cleansing. | $30 (for 10,000 credits) or $1,025/year for Web APIs direct packages; Data Quality Suite at ~$12,300/year | 1,000 free credits forever via Developer Portal; 30-day free trial for on-premise Data Quality Suite |
| **[Dun & Bradstreet](https://www.dnb.com/)** | Enterprise data platform providing company identification, business matching, hierarchy resolution, and organization master-data capabilities. | ~$2,500/year (~$208/month) for D&B Hoovers / D&B Direct+ entry API package | 30-day free trial with 1,000 free test API calls via D&B Direct+ Developer Portal |
| **[Acxiom](https://www.acxiom.com/)** | Customer intelligence and identity-data platform supporting identity resolution, audience matching, enrichment, and customer data unification. | ~$1,500/month (~$18,000/year for Real Identity / identity hygiene APIs) | 30-day evaluation sandbox / sample batch match of up to 5,000 records upon sales consultation |
| **[LiveRamp](https://liveramp.com/)** | Identity and data collaboration platform focused on identity resolution, identity graphs, data matching, and privacy-conscious customer connectivity. | ~$2,500/month (~$30,000/year for RampID / Identity Resolution base tier) | 14-day trial / developer sandbox with up to 10,000 test identity graph records |
| **[Neustar](https://www.transunion.com/solution/neustar)** | Identity and data-resolution technology supporting customer identity, marketing identity, fraud, and analytics use cases. | ~$1,000–$2,000/month (~$12,000/year for OneID API packages) | 30-day test environment / evaluation sandbox upon developer inquiry |


## Open-Source GitHub Projects

- **[Splink](https://github.com/moj-analytical-services/splink)**  
  One of the strongest open-source probabilistic record-linkage frameworks. Python-based and designed for scalable entity resolution using SQL engines such as DuckDB, Spark, and cloud query engines.

- **[Zingg](https://github.com/zinggAI/zingg)**  
  Open-source machine-learning-based entity resolution, identity resolution, deduplication, and data-mastering framework designed for large-scale datasets.

- **[Dedupe](https://github.com/dedupeio/dedupe)**  
  Popular Python library for machine-learning-based fuzzy matching, record deduplication, and entity resolution. Uses human-labeled examples and active learning to learn matching rules.

- **[Python Record Linkage Toolkit](https://github.com/J535D165/recordlinkage)**  
  Modular Python framework for record linkage and duplicate detection with indexing/blocking, field comparison, classifiers, and evaluation functionality.

- **[pyJedAI](https://github.com/AI-team-UoA/pyJedAI)**  
  Python entity-resolution and link-discovery framework providing blocking, matching, clustering, and machine-learning techniques for structured and semi-structured data.

- **[JedAI](https://github.com/scify/JedAIToolkit)**  
  Open-source Java toolkit for entity resolution, record linkage, data integration, and link discovery with scalable blocking and matching algorithms.

- **[RLTK — Record Linkage ToolKit](https://github.com/usc-isi-i2/rltk)**  
  Python toolkit for finding and linking entities across datasets, providing components for record linkage and entity matching workflows.

- **[OpenRefine](https://github.com/OpenRefine/OpenRefine)**  
  Open-source data cleaning and reconciliation platform with clustering and reconciliation capabilities that can be used as part of entity-matching workflows.

- **[Zingg Examples / Vikas](https://github.com/zinggAI/zingg-vikas)**  
  Example and supporting repository associated with Zingg's ML-based identity resolution, entity resolution, deduplication, and data mastering workflows.

- **[RecordLinkage — R Package](https://github.com/cran/RecordLinkage)**  
  R implementation providing statistical and machine-learning tools for probabilistic record linkage and duplicate detection.

- **[fastLink](https://github.com/kosukeimai/fastLink)**  
  R package implementing fast probabilistic record linkage using Fellegi-Sunter-style methods for linking records across datasets.

- **[FEBRL](https://sourceforge.net/projects/febrl/)**  
  Freely Extensible Biomedical Record Linkage project providing classical record-linkage algorithms, data cleaning, comparison, and matching capabilities.

- **[Duke](https://github.com/larsga/Duke)**  
  Java-based open-source entity-resolution framework for identifying matching entities across datasets using configurable properties and probabilistic matching.

- **[RLTK / USC ISI-I2](https://github.com/usc-isi-i2/rltk)**  
  Research-oriented toolkit for record linkage and entity discovery developed within the USC Information Sciences Institute ecosystem.

- **[OpenSanctions](https://github.com/opensanctions/opensanctions)**  
  Open data project for sanctions, politically exposed persons, and related entities. Useful as an entity-data and matching/enrichment component in compliance-oriented ER pipelines.

- **[Amundsen](https://github.com/amundsen-io/amundsen)**  
  Open-source data discovery platform that can complement entity-resolution pipelines by providing metadata discovery and data lineage across enterprise datasets.

- **[Apache Spark](https://github.com/apache/spark)**  
  Large-scale distributed data-processing framework commonly used to build scalable blocking, candidate generation, feature engineering, and matching pipelines around ER algorithms.

- **[Apache Flink](https://github.com/apache/flink)**  
  Distributed stream-processing framework useful for real-time entity resolution, incremental matching, event-driven identity resolution, and streaming deduplication.

- **[Apache Beam](https://github.com/apache/beam)**  
  Unified batch and streaming processing framework that can be used to implement large-scale entity matching and record-linkage pipelines.

- **[DuckDB](https://github.com/duckdb/duckdb)**  
  Embedded analytical SQL database particularly useful for local and analytical entity-resolution workloads and for scalable linkage workflows such as those implemented by Splink.

- **[Apache Lucene](https://github.com/apache/lucene)**  
  Open-source search engine library useful for candidate generation, approximate retrieval, fuzzy search, and blocking stages in custom entity-resolution systems.

- **[Elasticsearch](https://github.com/elastic/elasticsearch)**  
  Distributed search engine that can serve as a candidate-generation and fuzzy-search layer for large-scale entity matching architectures.

- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**  
  Open-source search and analytics engine that can be used for fuzzy retrieval, candidate generation, similarity search, and entity-resolution pipelines.

- **[Apache Jena](https://github.com/apache/jena)**  
  Open-source RDF and semantic-web framework useful for ontology-driven entity resolution, knowledge graphs, identity relationships, and semantic reconciliation.

- **[Neo4j Community Edition](https://github.com/neo4j/neo4j)**  
  Graph database that can be used to construct entity graphs and relationship networks around resolved identities.

- **[Kùzu](https://github.com/kuzudb/kuzu)**  
  Embedded open-source graph database useful for building local knowledge-graph-based identity and entity-resolution systems.

## Additional Open-Source & Research Projects

The following projects and ecosystems are also useful when building custom entity-resolution systems.

### Record Linkage & Matching

- **[Splink](https://github.com/moj-analytical-services/splink)** — Probabilistic linkage at scale.
- **[Dedupe](https://github.com/dedupeio/dedupe)** — ML-based fuzzy matching and deduplication.
- **[RecordLinkage](https://github.com/J535D165/recordlinkage)** — Modular Python record-linkage toolkit.
- **[pyJedAI](https://github.com/AI-team-UoA/pyJedAI)** — End-to-end entity-resolution workflows.
- **[JedAI](https://github.com/scify/JedAIToolkit)** — Java entity-resolution and link-discovery toolkit.
- **[RLTK](https://github.com/usc-isi-i2/rltk)** — Python record-linkage toolkit.
- **[fastLink](https://github.com/kosukeimai/fastLink)** — Statistical probabilistic linkage in R.
- **[FEBRL](https://sourceforge.net/projects/febrl/)** — Classical record-linkage research toolkit.
- **[Duke](https://github.com/larsga/Duke)** — Java entity-resolution framework.

### Data Cleaning & Reconciliation

- **[OpenRefine](https://github.com/OpenRefine/OpenRefine)** — Data cleaning, clustering, and reconciliation.
- **[Great Expectations](https://github.com/great-expectations/great_expectations)** — Data-quality validation useful before entity matching.
- **[Pandera](https://github.com/unionai-oss/pandera)** — Data validation framework for Python data pipelines.
- **[Frictionless Data](https://github.com/frictionlessdata/frictionless-py)** — Data-quality and tabular-data tooling.

### Search, Blocking & Candidate Generation

- **[Apache Lucene](https://github.com/apache/lucene)** — Full-text and fuzzy search.
- **[Elasticsearch](https://github.com/elastic/elasticsearch)** — Distributed fuzzy search and candidate retrieval.
- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)** — Open-source search and similarity infrastructure.
- **[FAISS](https://github.com/facebookresearch/faiss)** — High-performance vector similarity search.
- **[Annoy](https://github.com/spotify/annoy)** — Approximate nearest-neighbor search.
- **[HNSWlib](https://github.com/nmslib/hnswlib)** — Fast approximate nearest-neighbor search.

### NLP & Semantic Matching

- **[Sentence Transformers](https://github.com/UKPLab/sentence-transformers)** — Sentence and text embeddings useful for semantic entity matching.
- **[spaCy](https://github.com/explosion/spaCy)** — NLP framework useful for names, organizations, addresses, and entity extraction.
- **[RapidFuzz](https://github.com/rapidfuzz/RapidFuzz)** — High-performance fuzzy string matching.
- **[scikit-learn](https://github.com/scikit-learn/scikit-learn)** — Classical ML algorithms useful for match classification and clustering.
- **[Hugging Face Transformers](https://github.com/huggingface/transformers)** — Transformer models useful for semantic similarity and learned entity-matching systems.

### Knowledge Graph & Relationship Resolution

- **[Apache Jena](https://github.com/apache/jena)** — RDF, SPARQL, and semantic data processing.
- **[Neo4j](https://github.com/neo4j/neo4j)** — Graph-based entity and relationship modeling.
- **[Kùzu](https://github.com/kuzudb/kuzu)** — Embedded graph database.
- **[NetworkX](https://github.com/networkx/networkx)** — Graph analysis for entity and relationship networks.
- **[RDFLib](https://github.com/RDFLib/rdflib)** — Python RDF processing library.
- **[KGTK](https://github.com/usc-isi-i2/kgtk)** — Knowledge Graph Toolkit for large-scale knowledge graph processing.

## Building a Custom Open-Source Entity Resolution Stack

A production-grade open-source Entity Resolution system can be assembled from several layers:

```text
                    ┌─────────────────────────────┐
                    │        Source Systems       │
                    │ CRM / ERP / CSV / APIs / DB │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │       Data Cleaning         │
                    │ OpenRefine / Pandera /      │
                    │ Great Expectations / Spark  │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │     Normalization & NLP     │
                    │ spaCy / RapidFuzz /         │
                    │ Sentence Transformers       │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │ Blocking / Candidate Gen.   │
                    │ Lucene / Elasticsearch /    │
                    │ FAISS / HNSW / DuckDB       │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │       Entity Matching       │
                    │ Splink / Dedupe / Zingg /   │
                    │ pyJedAI / JedAI / RLTK      │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │     Clustering & Merging    │
                    │ Connected Components /      │
                    │ Graph Algorithms / ML       │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │       Golden Records        │
                    │ Customer / Company / Product│
                    │ Supplier / Location / Asset │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │   Knowledge Graph / MDM     │
                    │ Neo4j / Kùzu / Jena /       │
                    │ PostgreSQL / Spark          │
                    └─────────────────────────────┘

```
