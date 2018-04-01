# Stanford Sentiment Treebank

This is re-fined dataset based on [Stanford Sentiment Treebank][origin] used in [Yoon Kim (2014).][yoon-kim]

- `stsa.fine.*`: Stanford Sentiment Treebank—an extension of MR but with train/dev/test splits provided and fine-grained labels (very positive, positive, neutral, negative, very negative). It is called SST-1 in paper.
- `stsa.binary.*`: It splits to train/test/dev and re-labels to binary labels (1=positive, 0=negative) with neutral reviews removed. It is called SST-2 in paper.

[origin]: http://nlp.stanford.edu/sentiment/
[yoon-kim]: http://www.aclweb.org/anthology/D14-1181