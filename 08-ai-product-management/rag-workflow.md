# Retrieval-Augmented Generation (RAG) Product Workflow

## User problem
[What question or task requires grounded answers from an approved knowledge base?]

## Conceptual flow
1. Ingest approved source documents.
2. Parse, clean and chunk content.
3. Generate embeddings and index permitted content.
4. Retrieve relevant passages for a user query.
5. Apply access-control filtering.
6. Generate an answer grounded in retrieved passages.
7. Present citations / source references and uncertainty.
8. Collect feedback and monitor quality.

## Product decisions
- Approved sources:
- Freshness / re-indexing:
- Access control:
- Citation expectations:
- No-answer behaviour:
- Data deletion propagation:

## Evaluation
Retrieval precision / recall, answer groundedness, citation correctness, task success, latency and cost.