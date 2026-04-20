# Apache HBase (apache-hbase)
Apache HBase is an open-source, distributed, versioned, non-relational database modeled after Google's Bigtable. It provides random, real-time read/write access to big data and runs on top of Apache Hadoop HDFS, offering a REST API (Stargate), Thrift API, and Java client API for table and cell-level operations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-hbase/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Apache, Big Data, Bigtable, Database, Hadoop, NoSQL, Open Source, Wide Column

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache HBase REST API
REST API (Stargate) for Apache HBase distributed NoSQL database, providing table management, row and cell operations, and table scanning via HTTP with JSON or XML encoding.

**Human URL:** [https://hbase.apache.org/book.html#_rest](https://hbase.apache.org/book.html#_rest)

#### Tags:

 - Cells, NoSQL, REST, Rows, Tables

#### Properties

- [Documentation](https://hbase.apache.org/book.html#_rest)
- [OpenAPI](openapi/apache-hbase-rest-openapi.yml)
- [JSONSchema](json-schema/hbase-rest-tableschema-schema.json)
- [JSON-LD](json-ld/apache-hbase-rest-context.jsonld)

### Apache HBase Java Client API
Java client API for all HBase data operations including table administration, filters, coprocessors, batch operations, and async client for high-throughput workloads.

**Human URL:** [https://hbase.apache.org/apidocs/](https://hbase.apache.org/apidocs/)

#### Tags:

 - Java, NoSQL, SDK

#### Properties

- [Documentation](https://hbase.apache.org/apidocs/)
- [Java SDK (Maven Central)](https://search.maven.org/artifact/org.apache.hbase/hbase-client)

## Common Properties

- [Documentation](https://hbase.apache.org/book.html)
- [GettingStarted](https://hbase.apache.org/book.html#quickstart)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/hbase)

## Features

| Name | Description |
|------|-------------|
| Wide-Column NoSQL Storage | Store sparse, semi-structured data in a distributed wide-column table model inspired by Google Bigtable. |
| REST API (Stargate) | HTTP REST gateway for language-agnostic table and row operations using JSON or XML. |
| Thrift API | High-performance Thrift interface for cross-language HBase access with compact binary encoding. |
| Row-Level Consistency | Strong consistency guarantees for single-row get, put, and delete operations. |
| Coprocessors | Server-side coprocessor framework for custom observers and endpoints analogous to stored procedures. |
| HBase Shell | JRuby-based interactive shell for administrative and data manipulation operations. |
| Scanner API | Flexible server-side scan API with filters, time ranges, and column family projections. |
| Replication | Asynchronous multi-cluster replication for disaster recovery and geographic distribution. |

## Use Cases

| Name | Description |
|------|-------------|
| Time-Series Data Storage | Store high-velocity time-series sensor or log data with row keys designed for time range scans. |
| Event Logging | Persist event streams from web applications or IoT devices for analytics and audit. |
| User Profile Storage | Store sparse user profile attributes at scale with efficient random access by user ID. |
| Graph Storage Backend | Use HBase as a backend storage engine for graph databases like Apache TinkerPop/JanusGraph. |
| Machine Learning Feature Store | Store and serve pre-computed ML features at low latency for online prediction. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hadoop HDFS | HBase uses HDFS as its underlying distributed file system for WAL and HFile storage. |
| Apache Phoenix | SQL skin over HBase providing JDBC access, secondary indexes, and query optimization. |
| Apache Spark | Spark-HBase connector for reading and writing HBase tables as Spark DataFrames. |
| Apache Hive | HBase storage handler for using HBase tables as external Hive tables. |
| Apache Flink | Flink HBase connector for reading and writing HBase tables in streaming pipelines. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache HBase REST API](openapi/apache-hbase-rest-openapi.yml)

### JSON Schema

- 8 schema files in [json-schema/](json-schema/)

### JSON Structure

- 8 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Apache HBase REST Context](json-ld/apache-hbase-rest-context.jsonld)

### Examples

- 8 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache HBase REST API](capabilities/shared/hbase-rest.yaml) — 5 operations for table and row management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache HBase Data Access](capabilities/hbase-data-access.yaml) | hbase-rest | 5 | Data Engineer |

## Vocabulary

- [Apache HBase Vocabulary](vocabulary/apache-hbase-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 5 actions, 1 workflow, and 1 persona across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache HBase Spectral Rules](rules/apache-hbase-spectral-rules.yml) — 9 rules across 4 categories enforcing Apache HBase API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
