# Amazon ElastiCache (amazon-elasticache)
Amazon ElastiCache is a fully managed in-memory caching service supporting Redis and Memcached. ElastiCache makes it easy to deploy, operate, and scale popular open-source compatible in-memory data stores, improving the performance of web applications.

**URL:** [https://aws.amazon.com/elasticache/](https://aws.amazon.com/elasticache/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon Web Services, AWS, Caching, Database, ElastiCache, In-Memory, Memcached, Redis

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon ElastiCache API
API for managing Amazon ElastiCache clusters, replication groups, parameter groups, and related caching infrastructure resources.

**Human URL:** [https://aws.amazon.com/elasticache/](https://aws.amazon.com/elasticache/)

#### Tags:

 - Caching, Database, In-Memory, Redis

#### Properties

- [Documentation](https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/)
- [OpenAPI](openapi/amazon-elasticache-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/AmazonElastiCache/latest/APIReference/)
- [GettingStarted](https://aws.amazon.com/elasticache/getting-started/)
- [Pricing](https://aws.amazon.com/elasticache/pricing/)
- [FAQ](https://aws.amazon.com/elasticache/faqs/)
- [JSONSchema](json-schema/amazon-elasticache-cache-cluster-schema.json)
- [JSONSchema](json-schema/amazon-elasticache-cachecluster-schema.json)
- [JSONSchema](json-schema/amazon-elasticache-create-cache-cluster-result-schema.json)
- [JSONLD](json-ld/amazon-elasticache-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/elasticache/)
- [Documentation](https://docs.aws.amazon.com/elasticache/)
- [Blog](https://aws.amazon.com/blogs/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/elasticache/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/support/)
- [FAQ](https://aws.amazon.com/elasticache/faqs/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Compliance](https://aws.amazon.com/compliance/)
- [Security](https://aws.amazon.com/security/)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/elasticache)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Redis Support | Fully managed Redis with replication, clustering, and persistence |
| Memcached Support | Fully managed Memcached for simple distributed caching |
| Multi-AZ Replication | Automatic failover with Multi-AZ replication groups |
| Encryption | Encryption at-rest and in-transit for compliance requirements |
| Automatic Backups | Scheduled automatic backups with point-in-time recovery |

## Use Cases

| Name | Description |
|------|-------------|
| Session Management | Store and manage user session data for web applications |
| Database Query Caching | Cache expensive database queries to reduce latency |
| Real-Time Analytics | Process and cache real-time data streams for analytics dashboards |
| Leaderboards and Gaming | Build real-time leaderboards and gaming backends with Redis sorted sets |

## Integrations

| Name | Description |
|------|-------------|
| Amazon EC2 | Connect ElastiCache clusters to EC2-hosted applications |
| Amazon RDS | Cache RDS query results to reduce database load |
| Amazon Lambda | Access ElastiCache from serverless Lambda functions |
| Amazon EKS | Use ElastiCache as shared cache for Kubernetes workloads |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-elasticache](openapi/amazon-elasticache-openapi.yml)

### JSON Schema

- [amazon-elasticache-cache-cluster](json-schema/amazon-elasticache-cache-cluster-schema.json)
- [amazon-elasticache-cachecluster](json-schema/amazon-elasticache-cachecluster-schema.json)
- [amazon-elasticache-create-cache-cluster-result](json-schema/amazon-elasticache-create-cache-cluster-result-schema.json)
- [amazon-elasticache-describe-cache-clusters-result](json-schema/amazon-elasticache-describe-cache-clusters-result-schema.json)

### JSON Structure

- [amazon-elasticache-cache-cluster](json-structure/amazon-elasticache-cache-cluster-structure.json)
- [amazon-elasticache-cachecluster](json-structure/amazon-elasticache-cachecluster-structure.json)
- [amazon-elasticache-create-cache-cluster-result](json-structure/amazon-elasticache-create-cache-cluster-result-structure.json)
- [amazon-elasticache-describe-cache-clusters-result](json-structure/amazon-elasticache-describe-cache-clusters-result-structure.json)

### JSON-LD

- [amazon-elasticache](json-ld/amazon-elasticache-context.jsonld)

### Examples

- [amazon-elasticache-cache-cluster](examples/amazon-elasticache-cache-cluster-example.json)
- [amazon-elasticache-cachecluster](examples/amazon-elasticache-cachecluster-example.json)
- [amazon-elasticache-create-cache-cluster-result](examples/amazon-elasticache-create-cache-cluster-result-example.json)
- [amazon-elasticache-describe-cache-clusters-result](examples/amazon-elasticache-describe-cache-clusters-result-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [ElastiCache](capabilities/shared/api.yaml) — 5 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Amazon ElastiCache Management](capabilities/amazon-elasticache-capability.yaml) | 5 | Cloud Architect |

## Vocabulary

- [Amazon ElastiCache Vocabulary](vocabulary/amazon-elasticache-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 3 actions, 1 workflows, and 2 personas

## Rules

- [amazon-elasticache-spectral-rules.yml](rules/amazon-elasticache-spectral-rules.yml) — 0 rules enforcing Amazon ElastiCache API conventions

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
