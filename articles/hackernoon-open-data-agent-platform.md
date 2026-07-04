# Open Data Agent Platform: The Missing Category Between Text-to-SQL and BI

## TL;DR

An **Open Data Agent Platform (ODAP)** is a governed layer where humans and AI
agents can ask questions over open data, generate SQL, validate execution,
reuse semantic definitions, remember corrections, and leave an audit trail.

It is the missing category between text-to-SQL demos and enterprise BI systems.

## The Problem With "Chat With Your Data"

"Chat with your data" sounds simple until you put it inside a real company.

Real companies have:

- conflicting metric definitions
- messy schemas
- restricted columns
- expensive queries
- duplicated dashboards
- undocumented joins
- business terms that do not appear in table names
- compliance requirements
- analysts who must review important numbers before they reach leadership

So the hard problem is not generating one SQL query. The hard problem is making
AI-generated analysis trustworthy enough to use.

## Text-to-SQL Is Not Enough

Text-to-SQL answers one question:

> Can a model turn natural language into SQL?

ODAP asks a broader question:

> Can a platform turn natural language into a governed, explainable,
> cost-aware, auditable data workflow?

That difference matters.

## The ODAP Stack

### 1. Data Gateway

The platform must connect to where data already lives: warehouses, databases,
S3, Azure Blob, MinIO, APIs, Iceberg, Delta Lake, Hudi, and other open formats.

### 2. Semantic Layer

The platform must know what the business means. "Active user" and "net revenue"
are not just column names. They are governed definitions.

### 3. Multi-Agent SQL Engine

Instead of one prompt producing one query, the platform should break the job
into roles:

- planner
- SQL generator
- validator
- cost estimator
- security reviewer
- repair agent
- answer explainer

### 4. Memory

Every correction is training signal. If a user fixes a join, changes a metric,
or rejects an answer, the system should remember that pattern.

### 5. Governance

The platform needs audit logs, permissions, lineage, quality checks, sandbox
runs, budget limits, and human approval gates.

## Why Open Data Matters

The rise of open table formats changed the center of gravity in analytics.
Apache Iceberg, Delta Lake, and Apache Hudi made the lakehouse more practical.
Trino, Spark, DuckDB, and other engines made execution more portable.

An ODAP should be able to operate across that open substrate instead of locking
every analytical workflow into one proprietary warehouse.

## What Belongs In The Ecosystem?

The ODAP landscape includes:

- open table formats: Apache Iceberg, Delta Lake, Apache Hudi
- query engines: Trino, Presto, Spark, DuckDB
- metadata and catalog systems: OpenMetadata, DataHub
- semantic layers: dbt Semantic Layer, Cube, MetricFlow
- agent frameworks: LangGraph, CrewAI, LlamaIndex, AutoGen
- vector memory: Qdrant, Weaviate, Milvus, pgvector
- GenBI and conversational analytics: Wren AI, Databricks Genie Agents, Looker
  Conversational Analytics, Tableau Next, Snowflake Cortex AI
- observability and governance: OpenTelemetry, Prometheus, Grafana, Great
  Expectations, OpenLineage

## The Category Test

Here is the simple test:

1. Can it connect to open and enterprise data?
2. Can it use governed semantics?
3. Can it generate and validate SQL?
4. Can it remember corrections?
5. Can it enforce permissions and audit the result?
6. Can it explain why the answer should be trusted?

If yes, it is probably part of the ODAP category.

## Why This Term Will Matter

AI agents are going to query data. That is unavoidable.

The question is whether they will do it through brittle prompts and hidden
credentials, or through a governed platform with semantics, memory, validation,
and observability.

Open Data Agent Platform is the name for the second path.

## Further Reading

- Awesome ODAP: https://github.com/bestchatgpt8/awesome-odap
- Open Data Agent Platform: https://googlesql.com/
