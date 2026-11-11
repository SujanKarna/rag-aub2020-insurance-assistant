# RAG System for the GDV AUB 2020

A Retrieval-Augmented Generation (RAG) prototype that answers natural-language questions about the **GDV Allgemeine Unfallversicherungsbedingungen (AUB 2020)**. Its answers are grounded in the document's own clauses.

## Project Overview

Insurance terms like the AUB 2020 are long, legally worded and organised in numbered sections and clauses. This project builds a system where users can ask questions in plain language and get answers that:

- are based only on the AUB 2020 document,
- cite the supporting section and clause numbers, and
- say clearly when the document does not contain enough information to answer.

**Provisional research question**

> How effectively can a RAG system answer questions about the GDV AUB 2020 document while grounding its answers in the relevant policy clauses?

## Objectives

1. **Document preparation:** extract the AUB 2020 text and keep its section and clause references.
2. **RAG pipeline:** implement document processing, chunking, embeddings, retrieval and answer generation.
3. **Grounded answers:** return answers with source references, and say so when the document has no answer.
4. **Evaluation:** test the prototype on a small set of questions with manually verified answers. Focus on:
   - answer correctness, and
   - whether the cited passages actually support the answer.

### Initial Scope

- Knowledge source: GDV AUB 2020 only.
- A basic, working RAG pipeline (no advanced optimisation yet).
- A small, manually verified evaluation set.

### Possible Future Extensions

These are not part of the initial objective. They depend on time and resources.

- Compare conventional RAG with GraphRAG.
- Evaluate different language models (different sizes, multilingual capabilities).
- Add further insurance policy documents.

## Team Members

## Technology Stack

## Setup Instructions

## Repository Structure

