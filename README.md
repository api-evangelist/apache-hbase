# Apache HBase (apache-hbase)

Apache HBase is an open-source, distributed, versioned, non-relational database modeled after Google's Bigtable. It provides random, real-time read/write access to big data and runs on top of Apache Hadoop HDFS, offering a REST API (Stargate), Thrift API, and Java client API for table and cell-level operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-hbase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-hbase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Apache
- Big Data
- Bigtable
- Database
- Hadoop
- NoSQL
- Open Source
- Wide Column

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache HBase REST API

REST API (Stargate) for Apache HBase distributed NoSQL database, providing table management, row and cell operations, and table scanning via HTTP with JSON or XML encoding.

- **Human URL:** [https://hbase.apache.org/book.html#_rest](https://hbase.apache.org/book.html#_rest)
- **Base URL:** `http://localhost:8080`

#### Tags

- Cells
- NoSQL
- REST
- Rows
- Tables

#### Properties

- [Documentation](https://hbase.apache.org/book.html#_rest)
- [OpenAPI](openapi/apache-hbase-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-hbase-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-hbase-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hbase-rest-tableschema-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/apache-hbase-rest-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Apache HBase Java Client API

Java client API for all HBase data operations including table administration, filters, coprocessors, batch operations, and async client for high-throughput workloads.

- **Human URL:** [https://hbase.apache.org/apidocs/](https://hbase.apache.org/apidocs/)

#### Tags

- Java
- NoSQL
- SDK

#### Properties

- [Documentation](https://hbase.apache.org/apidocs/)
- [SDK](https://search.maven.org/artifact/org.apache.hbase/hbase-client)
- [Postman Collection](collections/apache-hbase-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-hbase-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Documentation](https://hbase.apache.org/book.html)
- [Getting Started](https://hbase.apache.org/book.html#quickstart)
- [GitHub Organization](https://github.com/apache)
- [GitHub Repository](https://github.com/apache/hbase)
- [Spectral Rules](rules/apache-hbase-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-hbase-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
