# neural-search-tutorials
Additional Notebooks for the Building NLP Applications course.

The notebooks require `gensim` to be installed.
One of the notebooks also assumes that the `word2vec-google-news-300.gz` is available in the shared folder.
This file can be downloaded with the Gensim downloader:

```
import gensim.downloader as api
wv = api.load('word2vec-google-news-300')
```

The file will be stored in `~/gensim-data/` and can be moved wherever necessary.
