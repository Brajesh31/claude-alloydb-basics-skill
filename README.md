# claude-alloydb-basics-skill

A Claude Code skill for working with AlloyDB for PostgreSQL, including cluster operations, client integration, infrastructure, IAM, and AI-oriented database capabilities.

## Overview

AlloyDB is a managed PostgreSQL-compatible database service. This skill helps developers understand its core architecture, provision and operate database resources, connect applications, configure access, and evaluate database features for AI applications.

## Main Capabilities

- Understand AlloyDB clusters, instances, and backups.
- Use command-line workflows for database administration.
- Connect applications through supported client libraries.
- Define infrastructure and configuration.
- Configure IAM and database security.
- Work with AlloyDB MCP integrations.
- Explore vector and hybrid search capabilities.
- Plan backups and operational recovery.
- Review performance and availability considerations.

## Installation

Install the skill in the Claude Code skills directory:

```bash
git clone https://github.com/Brajesh31/claude-alloydb-basics-skill.git ~/.claude/skills/alloydb-basics
```

Database administration commands require a configured cloud environment, suitable project permissions, and access to the target AlloyDB resources.

## Usage

Invoke the skill for AlloyDB tasks:

```text
/alloydb-basics
```

Provide the cloud project, region, cluster or instance identifier, intended operation, and relevant security or availability constraints. Do not include credentials in prompts.

## Reference Guide

| File | Focus |
|---|---|
| `references/core-concepts.md` | Clusters, instances, and database architecture |
| `references/cli-usage.md` | Command-line administration |
| `references/client-library-usage.md` | Application connectivity |
| `references/iac-usage.md` | Infrastructure as code |
| `references/iam-security.md` | Identity, permissions, and security |
| `references/mcp-usage.md` | MCP-based database workflows |

## Recommended Workflow

1. Confirm the cloud project and target environment.
2. Inspect existing clusters and instances before making changes.
3. Review networking, identity, and access requirements.
4. Choose a suitable client connection method.
5. Plan backups and recovery before modifying production resources.
6. Apply infrastructure changes through a repeatable process.
7. Validate connectivity and database behavior.
8. Monitor performance, availability, and operational events.

## Security Checklist

- Use least-privilege IAM roles.
- Keep credentials in secure secret storage.
- Restrict network access to approved clients.
- Separate development, staging, and production environments.
- Confirm backup and restore procedures.
- Audit privileged operations.
- Avoid exposing database connection strings in logs.

## Repository Contents

- `SKILL.md`: Main AlloyDB workflow and operating instructions.
- `references/`: Core concepts, CLI, client libraries, infrastructure, IAM, and MCP guidance.
- `README.md`: Setup, usage, and operational checklist.

## AI and Vector Workloads

For AI-oriented applications, assess vector search, hybrid retrieval, and model integration against the actual data and query requirements. Validate index design, retrieval quality, latency, and cost before adopting a production architecture.

## Operational Caution

Database changes can affect availability and data integrity. Confirm the target environment, understand the operation's impact, and ensure recovery options are available before making destructive changes.


## Supporting Resources

| File | Purpose |
|---|---|
| [Cluster production readiness checklist](resources/cluster-production-readiness-checklist.md) | Review environment, network, IAM, secrets, recovery, monitoring, and approval. |
| [Backup and restore drill](resources/backup-restore-drill-template.md) | Record a safe restore test, recovery objectives, evidence, and follow-up actions. |
| [Vector search evaluation template](resources/vector-search-evaluation-template.md) | Evaluate embedding consistency, retrieval quality, filters, latency, and operations. |

The six existing reference files under references/ are retained. They cover core concepts, CLI use, client libraries, infrastructure as code, IAM/security, and MCP. Use current Google Cloud documentation to verify command flags, supported regions, IAM roles, connector behavior, feature availability, and pricing before making changes.

## Upstream source and license

The unchanged SKILL.md metadata identifies Google skills as the source and Apache 2.0 as the upstream license. The single root LICENSE is retained as requested for this repository; it does not replace the upstream terms for copied skill content. Review the upstream source terms before redistributing that content.
