## PubMedBERT (abstracts + full text)

Pretraining large neural language models, such as BERT, has led to impressive gains on many natural language processing (NLP) tasks. However, most pretraining efforts focus on general domain corpora, such as newswire and Web. A prevailing assumption is that even domain-specific pretraining can benefit by starting from general-domain language models. [Recent work](https://arxiv.org/abs/2007.15779) shows that for domains with abundant unlabeled text, such as biomedicine, pretraining language models from scratch results in substantial gains over continual pretraining of general-domain language models.

PubMedBERT is pretrained from scratch using _abstracts_ from [PubMed](https://pubmed.ncbi.nlm.nih.gov/) and _full text_ articles from [PubMedCentral](https://www.ncbi.nlm.nih.gov/pmc/). This model achieves state-of-the-art performance on many biomedical NLP tasks, and currently holds the top score on the [Biomedical Language Understanding and Reasoning Benchmark](https://aka.ms/BLURB).

## Citation

If you find PubMedBERT useful in your research, please cite the following paper:

```latex
@misc{pubmedbert,
  author = {Yu Gu and Robert Tinn and Hao Cheng and Michael Lucas and Naoto Usuyama and Xiaodong Liu and Tristan Naumann and Jianfeng Gao and Hoifung Poon},
  title = {Domain-Specific Language Model Pretraining for Biomedical Natural Language Processing},
  year = {2020},
  eprint = {arXiv:2007.15779},
}
```
