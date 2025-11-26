# Learn the basics

```
                                  (1) Query
                                ┌──────────┐
                                │  Query   │
                                └────┬─────┘
                                     │
                                     │──────────────────────────────────────────────────────┐
                                     ▼                                                      │
                         (2) Embedding Model                                                │
                   ┌──────────────────────┐                                                 │
                   │   Embedding Model    │                                                 │
                   └──────────┬──────────┘                                                 │
                              │                                                            │
                              ▼                                                            │
                     (3) Query Embedding                                                   │
                ┌──────────────────────────┐                                               │
                │     Query Embedding      │                                               │
                └──────────┬───────────────┘                                               │
                           │                                                               │
                           ▼                                                               │
                     (4) Embedding Store                                                   │
              ┌──────────────────────────────┐                                             │
              │       Embedding Store        │                                             │
              └───────────┬──────────────────┘                                             │
                          │                                                                │
                          ▼                                                                │
                   (5) Relevant Segments                                                   │
              ┌──────────────────────────────┐                                             │
              │      Relevant Segments       │                                             │
              └───────────┬──────────────────┘                                             │
                          │                                                                │
                          ▼                                                                │
        (6) Augmented Prompt (Query + Relevant Segments)                                   │
┌───────────────────────────────────────────────────────────────────────┐                  │
│      Query + Relevant Segments (Augmented Prompt)                     │◄──────────────────┘
└────────────────────────────┬───────────────────────────────────────────┘
                             │
                             ▼
                      (7) Language Model
                ┌──────────────────────────┐
                │     Language Model       │
                └──────────────────────────┘
```

1\. Query: The user asks a question or gives a prompt.

_Example: “What did the 2024 business strategy include?”_

***

2\. Embedding Model: The model converts the query into a numerical vector (an embedding) that captures its meaning.

_It turns language into math so similarity search can work._

***

3\. Query Embedding

This is the vector representation of the query.

_It’s what gets compared against your knowledge base._

***

4\. Embedding Store: A vector database that stores embeddings of all indexed documents.

_The system searches this for the closest matches to the user query._

***

5\. Relevant Segments" The chunks of text (docs, notes, PDFs, emails, wiki pages) that are most similar to the query.

_These are retrieved and form the “context” for the model._

***

6\. Augmented Prompt" The original query plus the retrieved segments are combined into a single prompt.

_This gives the LLM the external knowledge it needs before answering._<br>
