---
description: A connection of many transformer blocks in series.
---

# Transformer block

This is done with a **really really really large neural network**, which is trained precisely with the goal to predict the next word in a sentence.

We can train such a large network, but we can vastly improve it by adding a key step: **the attention component.**

**\[image]**

The transformer is a connection of many transformer blocks. Each one of these blocks is composed of an attention component followed by a feedforward component (a neural network).

<figure><img src="../../.gitbook/assets/Screenshot 2023-06-20 at 1.03.03 PM.png" alt=""><figcaption><p>Transformers have impressive performance because they can generate new texts while ‘attending’ to all previous and contextually-relevant tokens that came before the one being generated</p></figcaption></figure>
