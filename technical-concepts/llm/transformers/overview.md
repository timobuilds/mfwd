---
description: Model architecture
---

# Overview

A transformer has 5 main parts:

1. **Tokenization**: Turns words into **tokens**.
2. **Embedding**: Turns tokens into strings of numbers (**vectors**)
3. **Positional encoding**: Adds **order** to the words in the text.
4. **Transformer block** (several of these in series): Guesses the next word. It is formed by an **attention** block(adds context to the text) and a **feedforward** block (guesses the next word).
5. **Softmax:** Turns the scores into probabilities in order to sample the next word.

These are explained in detail below…

<figure><img src="../../../.gitbook/assets/Untitled (2).png" alt=""><figcaption></figcaption></figure>

Example: If you type `“Hello, how are”,` into a phone, a transformer may suggest words such as “you”, or “your” as the next word.



Of course, if you continue selecting the suggested word in your phone, you’ll quickly find that the message formed by these words makes no sense. If you look at each set of 3 or 4 consecutive words, it may make sense, but these words don’t combine to anything with any meaning.

This is because the model used in the phone doesn’t carry the **overall context** of the message, it simply predicts which word is more likely to come up after the last few. **Transformers, on the other hand, keep track of the context of what is being written, and this is why the text that they write makes sense.**
