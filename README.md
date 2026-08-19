# Awesome-Entity-Resolution

## Top Entity Resolution Tools Ecosystem

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

- **[Senzing](https://senzing.com/)**  
  Real-time entity resolution and identity intelligence platform focused on resolving people, organizations, and relationships across disparate data sources. Designed to run within an organization's own infrastructure as well as cloud environments.

- **[Tamr](https://www.tamr.com/)**  
  AI-native entity resolution and data mastering platform for matching, deduplicating, clustering, scoring, and creating trusted golden records across enterprise datasets.

- **[Quantexa](https://www.quantexa.com/)**  
  Data and decision intelligence platform centered around dynamic entity resolution, contextual data integration, and knowledge-graph-driven analysis for customers, organizations, transactions, and other entities.

- **[Relativity](https://www.relativity.com/)**  
  Legal and investigative data platform with entity-oriented capabilities for identifying and organizing people, organizations, communications, and other entities across large volumes of case data.

- **[IBM InfoSphere Master Data Management](https://www.ibm.com/products/ibm-infosphere-master-data-management)**  
  Enterprise MDM platform providing matching, reconciliation, governance, and golden-record capabilities across critical master-data domains.

- **[Ataccama ONE](https://www.ataccama.com/)**  
  Enterprise data management platform combining data quality, MDM, governance, integration, and matching capabilities for creating trusted master records.

- **[Reltio](https://www.reltio.com/)**  
  Cloud-native master data and context intelligence platform with AI-powered entity resolution, match-and-merge, survivorship, and real-time golden-record capabilities.

- **[Precisely](https://www.precisely.com/)**  
  Data integrity platform offering automated data matching and entity resolution for customers, suppliers, assets, locations, and other enterprise entities.

- **[Informatica MDM](https://www.informatica.com/products/master-data-management.html)**  
  Enterprise master data management platform with identity resolution, matching, survivorship, hierarchy management, and golden-record capabilities.

- **[DataWalk](https://datawalk.com/)**  
  Investigative analytics and decision-intelligence platform combining entity resolution with knowledge graphs, data integration, risk analysis, fraud detection, and investigation workflows.

- **[SAP Master Data Governance](https://www.sap.com/products/technology-platform/master-data-governance.html)**  
  Enterprise master-data governance platform supporting centralized management, matching, validation, consolidation, and governance of business entities.

- **[Oracle Customer Data Management](https://www.oracle.com/cx/customer-data-management/)**  
  Oracle's customer data and master-data capabilities for consolidating customer information, identifying duplicates, and maintaining trusted customer records.

- **[Salesforce Data Cloud](https://www.salesforce.com/data/)**  
  Customer data platform with identity resolution capabilities for unifying customer records and creating a consolidated customer profile across data sources.

- **[Microsoft Dynamics 365 Customer Insights](https://www.microsoft.com/dynamics-365/products/customer-insights)**  
  Customer data platform with data unification and identity-resolution capabilities for combining customer records across enterprise systems.

- **[Semarchy xDM](https://www.semarchy.com/)**  
  Model-driven master data management platform providing matching, merging, survivorship, governance, and golden-record management.

- **[Stibo Systems STEP](https://www.stibosystems.com/)**  
  Enterprise master data platform for managing and harmonizing product, customer, supplier, and other business entities across complex data landscapes.

- **[Profisee](https://profisee.com/)**  
  Master data management platform focused on data quality, matching, governance, and trusted golden records.

- **[Riversand / Syndigo](https://syndigo.com/)**  
  Enterprise product and master data platform supporting data consolidation, matching, enrichment, and entity-centric management.

- **[Uniserv](https://www.uniserv.com/)**  
  Data quality and identity matching platform offering address verification, duplicate detection, customer matching, and data cleansing.

- **[Melissa](https://www.melissa.com/)**  
  Data quality platform providing identity resolution, address matching, deduplication, enrichment, and customer-data cleansing.

- **[Dun & Bradstreet](https://www.dnb.com/)**  
  Enterprise data platform providing company identification, business matching, hierarchy resolution, and organization master-data capabilities.

- **[Acxiom](https://www.acxiom.com/)**  
  Customer intelligence and identity-data platform supporting identity resolution, audience matching, enrichment, and customer data unification.

- **[LiveRamp](https://liveramp.com/)**  
  Identity and data collaboration platform focused on identity resolution, identity graphs, data matching, and privacy-conscious customer connectivity.

- **[Neustar](https://www.transunion.com/solution/neustar)**  
  Identity and data-resolution technology supporting customer identity, marketing identity, fraud, and analytics use cases.

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
