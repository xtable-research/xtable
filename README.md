# XTable

**XTable: Hybrid-Grained Indexing Meets Efficient LLM Embeddings for End-to-End Tabular Data Representation and Retrieval**

Supplementary repository for the XTable paper prepared for IEEE ICDE 2027.

XTable is a table discovery system that retrieves relevant tables from heterogeneous collections in response to natural-language queries. It combines three techniques:

- **Hybrid-grained indexing** clusters related column headers across tables so they can share generated summaries.
- **Early-exit embeddings** reduce encoding cost by stopping at an intermediate layer when the model is sufficiently confident.
- **Progressive retrieval** makes newly registered tables searchable through a lightweight schema index and generates missing summaries on demand.

## Artifact availability

This repository currently contains the project overview. The implementation, evaluation queries, ground-truth annotations, and reproduction instructions are not yet available here.
