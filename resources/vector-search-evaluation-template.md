# AlloyDB Vector and Hybrid Search Evaluation

## Workload
- Use case:
- Data source:
- Embedding model and version:
- Embedding dimensions:
- Corpus size:
- Update frequency:
- Query profile:

## Retrieval design
- Vector index and distance metric:
- Filter attributes:
- Hybrid keyword/vector strategy:
- Reranking approach:
- Metadata stored with each vector:
- Freshness and deletion behavior:

## Evaluation set
| Query ID | Query | Relevant record IDs | Retrieved IDs | Recall@k | Precision@k | Latency | Notes |
|---|---|---|---|---:|---:|---:|---|
| | | | | | | | |

## Operational checks
- [ ] Embedding model and dimensionality are consistent.
- [ ] Index build and refresh time are measured.
- [ ] Filters are applied with correct tenant/security boundaries.
- [ ] Query latency and resource use are measured under representative load.
- [ ] Stale or deleted records are handled.
- [ ] Backup/restore behavior for vector indexes is understood.
- [ ] Results are compared with a non-vector baseline.

## Decision
- Quality target:
- Latency target:
- Cost target:
- Limitations:
- Go / revise / stop:
