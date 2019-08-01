# slowText

Welcome to `slowText`.

Ever wanted a version of `fastText` that was not as fast? Yes? Well, you've reached the right place.

This is my attempt to see how far I can push Python code, 
inspired by [Gensim's word2vec](https://rare-technologies.com/word2vec-in-python-part-two-optimizing/) port in `Python` which is faster than the OG `C` implementation.

## Progress Log
[2019-08-01]
- Sticking to the "supervised" part of fastText for now.
- v0.9.1 will be the base reference repository -- MASTER sometimes contains bleeding/breaking changes.
- First step is finding a decent dataset and benchmark the fastText code.
- Also sticking to single process (no parallelism) for now.

