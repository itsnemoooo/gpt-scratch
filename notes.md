
# Notes
walkthrough.ipynb explains everything up to the transformer.

Attention is all you need implementation.
1. Scaled dot product attention
2. Multi-head attention
3. Positional encoding 
4. Feed forward # simple mlp. gives the self attention layer a chance to process the information in a different way.
5. Add & Norm
6. Residual connections
7. Layer normalization

Main concept: 
1. attention is a communication mechanism between nodes. Think of it like a directed graph. Every node has a vector of information and it aggregates information as a weighted sum of the (all previous) nodes it is connected to.
2. how do the nodes know space? Give them anchors to position of the nodes.

GPT - Generatively Pre-trained Transformer (the transformer does the havvy lifting)
Language model models the sequence of words / tokens and it learns how words follow each other. It completes the sequence.

Flashcards: 

- Why is the output of a prompt not deterministic? 
- GPT is a probabilistic model.

- Describe how we pass text into a transformer model.
- We sample a chunk of text from the dataset and pass it into the model.

- When training transformer models, we sample a chunk of 9 characters, how many examples are there?
- There are 8 examples in a chunk of 9 characters. 

- What is the minimum number of context the transformer needs to predict the next character?
- The minimum number of context the transformer needs to predict the next character is 1.

- What is the maximum number of context the transformer needs to predict the next character?
- The maximum number of context the transformer needs to predict the next character is block_size. Everything larger will get truncated.
