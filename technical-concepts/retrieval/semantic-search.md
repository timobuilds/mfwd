---
description: How to retrieve embedded data?
---

# Semantic Search

Similar search in vector databases works by comparing embeddings to find the most semantically similar iteam.&#x20;

Semantic similarity = how close two things mean, not how close they _look_.

* _car_ and _automobile_ → high semantic similarity
* _car_ and _banana_ → low semantic similarity

Semantic similarity measures how similar the meanings of two texts or concepts are, even if the wording is different.



How is this measure?

Cosine similarity measures the angle between two vectors, not their magnitude.

What it means:

* Two vectors pointing in the same direction → cosine = 1 (most similar)
* Two vectors pointing in opposite directions → cosine = -1 (most dissimilar)
* Two vectors at 90° → cosine = 0 (orthogonal, unrelated)

Why it's useful for embeddings:

* Focuses on direction (semantic meaning), not magnitude
* Normalizes out document length differences
* Range: -1 to 1 (often treated as 0 to 1 for similarity)

Example:

* "I love dogs" and "I adore canines" → high cosine similarity (similar meaning, different words)
* "I love dogs" and "The weather is sunny" → low cosine similarity (different topics)



*
* Embeddings & Semantic Search: high-dimensional vectors, similarity, powering RAG and search
* Vector Databases: storing embeddings, distance metrics, in-memory vs persistent setups
* ChromaDB Basics: install, client setup, collections management, pagination
* CRUD & Queries: add/update/upsert points, top-k similarity search, metadata for RAG
* Best Practices: persisting to disk, remote/cloud connections, isolating data per user
