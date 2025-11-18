---
description: Tokens into vectors.
---

# Embedding

A **vector** is a list of numbers.

An **embedding** is a way to associate words with a list of numbers (a vector) in such a way that similar words are associated with numbers that are close by, and dissimilar words with numbers that are far away from each other.

You can also think of embeddings as a way of compressing information.

<figure><img src="../../.gitbook/assets/embeddings.png" alt=""><figcaption><p>Embeddings: Turning words (tokens) into vectors (lists of numbers)</p></figcaption></figure>

Think of a word embedding as trying to [lay out words in a kind of “meaning space”](https://reference.wolfram.com/language/ref/FeatureSpacePlot.html) in which words that are somehow “nearby in meaning” appear nearby in the embedding space.

{% hint style="info" %}
One can think of an embedding as a way to try to represent the “essence” of something by an array of numbers—with the property that “nearby things” are represented by nearby numbers.
{% endhint %}





<figure><img src="../../.gitbook/assets/embedding_space.png" alt=""><figcaption><p>Similar words have embedded vectors that consist of similar numbers.</p></figcaption></figure>



Examples:&#x20;

<figure><img src="../../.gitbook/assets/Untitled (3).png" alt=""><figcaption><p>Embedding of words.</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/asdf (1).png" alt=""><figcaption><p>Embedding of numbers.</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Untitled (4).png" alt=""><figcaption><p>2D embedding of pet images. </p></figcaption></figure>
