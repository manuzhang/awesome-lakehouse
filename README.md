# awesome-lakehouse
a curated list of awesome [Lakehouse](https://www.databricks.com/sites/default/files/2020/12/cidr_lakehouse.pdf) frameworks, applications, etc

## Table of Contents

- [Table Format](#table-format)
- [Lakehouse System](#lakehouse-system)
- [Metadata Service](#metadata-service)
- [Machine Learning](#machine-learning)
- [Benchmark](#benchmark)

### Table Format

- [Apache Iceberg](https://github.com/apache/iceberg) [Java] - a high-performance format for huge analytic tables, bringing the reliability and simplicity of SQL tables to big data.
- [Apache Hudi](https://github.com/apache/hudi) [Java] - a transactional data lake platform that brings database and data warehouse capabilities to the data lake.
- [Apache Paimon (incubating)](https://github.com/apache/incubator-paimon) [Java] - a streaming data lake platform with high-speed data ingestion, changelog tracking and efficient real-time analytics.
- [Apache XTable (incubating)](https://github.com/apache/incubator-xtable) [Java] - a cross-table converter for table formats that facilitates omni-directional interoperability across data processing systems and query engines.
- [Delta](https://github.com/delta-io/delta/) [Scala] - an open-source storage framework that enables building a Lakehouse architecture with various compute engines and languages.

### Lakehouse System

- [Apache Amoro (incubating)](https://github.com/apache/amoro) [Java] - a management system built on open data lake formats, bringing pluggable and self-managed features for Lakehouse.
- [GeoLake](https://github.com/spatialx-project/geolake) [Java] - Universal solution for geospatial data tailored to data lakehouse systems.
- [LakeSoul](https://github.com/lakesoul-io/LakeSoul) [Rust] - a cloud-native Lakehouse framework that supports scalable metadata management, ACID transactions, efficient and flexible upsert operation, schema evolution, and unified streaming & batch processing.
- [Lakehouse Engine](https://github.com/adidas/lakehouse-engine) [Python] - a configuration driven Spark framework, written in Python, serving as a scalable and distributed engine for several lakehouse algorithms, data flows and utilities for Data Products.
- [Smart Data Lake](https://github.com/smart-data-lake/smart-data-lake) [Scala] - a data lake automation framework that makes loading and transforming data a breeze.
- [TrinityLake](https://github.com/trinitylake-io/trinitylake) [Java] - Open LakeHouse Format for Big Data Analytics, ML & AI.

### Metadata Service

- [Apache Gravitino](https://github.com/apache/gravitino) [Java] - a high-performance, geo-distributed, and federated metadata lake.
- [Apache Polaris (incubating)](https://github.com/apache/polaris) [Java] - The interoperable, open source catalog for Apache Iceberg
- [DeltaCAT](https://github.com/ray-project/deltacat) [Python] - a Pythonic Data Catalog powered by Ray.
- [lakeFS](https://github.com/treeverse/lakeFS) [Go] - data version control for data lake.
- [Lakekeeper](https://github.com/lakekeeper/lakekeeper) [Rust] - A Rust native Iceberg REST Catalog.
- [Metacat](https://github.com/Netflix/metacat) [Java] - a unified metadata exploration API service.
- [Nessie](https://github.com/projectnessie/nessie) [Java] - a Transactional Catalog for Data Lakes with Git-like semantics.
- [OpenHouse](https://github.com/linkedin/openhouse) [Java] - an open source control plane designed for efficient management of tables within open data lakehouse deployments.
- [UnityCatalog](https://github.com/unitycatalog/unitycatalog) [Java] - an open and interoperable catalog for data and AI

### Machine Learning

- [Space](https://github.com/google/space) [Python] - Unified storage framework for the entire machine learning lifecycle.

### Benchmark

- [LHBench](https://github.com/lhbench/lhbench) [Scala] - a benchmark for Lakehouse storage systems.
- [LST-Bench](https://github.com/microsoft/lst-bench) [Java] - a framework that allows users to run benchmarks specifically designed for evaluating the performance, efficiency, and stability of Log-Structured Tables (LSTs).
