# RAPTOR RAG With Knowledge-Graph Enhancement

Notebook and video companion for exploring tree-based long-context RAG and knowledge-graph enhancement.

Watch the walkthrough: [RAPTOR RAG + Knowledge Graphs](https://youtu.be/g1TzbKDNr7M)

## Project Question

Long-context models changed how developers think about retrieval. Instead of retrieving only small chunks, methods such as RAPTOR cluster and summarize documents into a tree so the model can access both high-level summaries and granular details.

This project asks:

> Can a RAPTOR-style retrieval tree reduce lost-in-the-middle failures, and where can a knowledge graph improve answer quality?

## What This Demonstrates

- How recursive abstractive summarization can create a tree-organized retrieval structure.
- Why long-context RAG still needs careful retrieval and evaluation.
- How knowledge graphs can add relationship-aware context on top of document chunks.
- How to turn a research-inspired retrieval pattern into a runnable notebook explanation.

## Files

- `raptor-rag-kg-enhanced.ipynb` - main exploratory notebook.
- `README.md` - project overview and video link.

## How To Use

Open the notebook and run it top to bottom:

```bash
jupyter notebook raptor-rag-kg-enhanced.ipynb
```

The notebook loads knowledge about Hayao Miyazaki from Wikipedia and uses it as the working retrieval corpus.

## Portfolio Note

This repo fits with my broader AI education work on RAG, hybrid retrieval, knowledge graphs, and model-evaluation pitfalls.
