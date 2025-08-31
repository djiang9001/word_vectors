# word_vectors

This repo contains the pre-trained word vectors from [GloVe](https://nlp.stanford.edu/projects/glove/), specifically the 2024 Dolma (220B tokens, 1.2M vocab, uncased, 300d vectors) vectors.

Each word is placed in its own .txt file. The file name is the word itself with any occurrences of forward slashes replaced by spaces. Long words > 255 bytes are split up with forward slashes every 255 bytes.

Each file contains the word followed by 300 decimal strings, all delimited by spaces.
