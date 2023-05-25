# Zero-Shot Recommendation with Language Modeling
Resources accompanying the "Zero-Shot Recommendation as Language Modeling" paper published at ECIR2022, where we show that pretrained large language models can act as a recommender system, and compare few-shot learning results to matrix factorization baselines.

# Huggingface dataset
We provide a version of our dataset on Huggingface datasets 🤗:
```python
from datasets import load_dataset

dataset = load_dataset("sileod/movie_recommendation")
```
A version of this dataset was also included in BIG-Bench.

# Citation
```bibtex
@InProceedings{sileo-lmrec-2022,
  author="Sileo, Damien
  and Vossen, Wout
  and Raymaekers, Robbe",
  editor="Hagen, Matthias
  and Verberne, Suzan
  and Macdonald, Craig
  and Seifert, Christin
  and Balog, Krisztian
  and N{\o}rv{\aa}g, Kjetil
  and Setty, Vinay",
  title="Zero-Shot Recommendation as Language Modeling",
  booktitle="Advances in Information Retrieval",
  year="2022",
  publisher="Springer International Publishing",
  address="Cham",
  pages="223--230",
  isbn="978-3-030-99739-7"
}


```
