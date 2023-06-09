# Day 5

## Seminar: Decoding the language matrix
*Speaker: Pedro Jacobetty*

Artificial neural networks are a computational architexture loosely inspired by biological neural networks.
Connected nodes (neurons) connect signals.
Each node is weighted, and the weights modulate the signals.
Weights are adjusted during training.
The error is sent back in a feedback loop to correct the weights.
A lot of cognitive metaphors are used to describe artificial neural networks.

Distributional hypothesis: the meaning of a word is dependant on the context the word is used.
One of the first advancements in lanuage models was word2vec. 
This defines (encodes) words into a vectorised representation in some vector space (embeddings).
E.g. King - Man + Woman = Queen

However, word2vec lacks context, and fails to account for polysemic words.

Transformer models were first described in 2017.
They have multiple layers of attention, differentially weighting the significance of each input part.
It takes positional encoding information about the positions of tokens in the input sequence, which allows it to create outputs which are often coherent.

Traditional transformer models still operate on individual words or tokens so lack an accurate method for building sentence-level embeddings.

GPTs are generative pre-trained transformers, pretrained with public and third-party provider data to predict the next token. 

BERT (bidirectional encoder representations from transformers) was developed by Google in 2019. 
It requires context and understands subwords unlike word2vec.

Large language models have billions of weights and are trained on large quantities of unlabelled text.
They preform well at a variety of tasks, understand semantic relations, and retain knowledge.
Large language models claim to represent language, but what they produce are based on mathematical algorithms.

## Data visualisation
When making visualisations, you should consider:

- Will it be printed or online?
- How big will it be?
- How can I improve the understanding?

It's important to avoid overly complex graphics.

There are many different tpes of graphics.

- Histograms, density plots, and boxplots can be used to visualise distributions.
- Piecharts, stacked bar graphs, and treemaps can be used to visualise ratios.
- Scatterplots, heatmas, and network diagrams can be used to visualise relations.
- Line graphs and stream graphs can be used to visualise change.

## Practical

In the practical session, we made different graphs using various R packages.
