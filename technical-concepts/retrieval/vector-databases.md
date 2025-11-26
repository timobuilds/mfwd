---
description: How to store embeddings?
---

# Vector Databases

Vector databases are specialized database systems designed to store and manage high-dimensional vector data.

you don't use a traditional database because the storage would get very expensive, they're inefficient so quiries would become very expensive. Nightmare.&#x20;

Columnum types are not built for high-dimensional data.&#x20;

Embedding and vector are often you



| DB                                 | Speed     | Scaling   | Cost     | Best Use Case                  |
| ---------------------------------- | --------- | --------- | -------- | ------------------------------ |
| Postgres + pgvector (eg. Supabase) | Medium    | Medium    | Low-Med  | Apps already using Postgres    |
| Pinecone                           | High      | Excellent | Med-High | Enterprise/production RAG      |
| Weaviate                           | High      | Good      | Low-Med  | OSS-friendly, hybrid search    |
| Qdrant                             | Very High | Very Good | Low-Med  | On-prem or performance-focused |
| Chroma                             | Medium    | Low       | Free     | Local dev, small apps          |

Different problems require differnt tools.&#x20;

Different vector DB for different problem.&#x20;

Internal tools vs millions of users.&#x20;

Choose wisely.&#x20;



To build applications, you will create a database with all your reference data, this will be convered via your embedding model into, it will create a vector column that contains your embedding for each reference in your table.&#x20;



* [Chroma DB Crash Course](https://www.youtube.com/watch?v=god8Pox1laE)
* [Supabase AI & Vectors Guide](https://supabase.com/docs/guides/ai) (Gold)
* [Pinecone Quickstart](https://docs.pinecone.io/guides/get-started/quickstart)



