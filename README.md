# Google's Universal Sentence Encoders

```bash
git clone https://github.pinnacol.com/washburp/universal-sentence-embeddings.git
```

**Universal Sentence Embedding** is a state-of-the-art practice that emerged in 2018 as an effective practice in natural language machine learning tasks.

Both word & sentence embeddings are transfer learning techniques that convert variable-length text sequences into fixed-length dense vectors of real numbers that represent the original data in a more [contextually aware manner](https://aclweb.org/aclwiki/Distributional_Hypothesis).  Universal embeddings are of interest to the community due to the fact that machine learning algorithms in general, and in particular neural networks, play nicely with the dense numeric vectors produced by the embedding process.  The approach also supplies context when larger volumes of data are unavailable, helping ease the burden of data collection and data labeling.  Embeddings also have the unique quality of associating data points that a human would also associate (*e.g. there were 5 counts of the word "dog" and 2 counts of the word "canine", but traditional techniques would treat them as completely independent*).  

Over the last couple of years there has been a movement towards **Universal Embeddings** as opposed to context-specific embeddings.  Most notably, Google has published two encoders for this purpose.  These encoders are pre-trained and ready-for-use in downstream machine learning workflows.  Transforming sentences with these encoders often confers a qualitative improvement in NLP classification (and similar) tasks due to the fact that they are derived from a large corpus of examples.
