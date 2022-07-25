# hunspell-tr

[Hunspell](http://hunspell.github.io/) dictionary for Turkish language developed by Turkish Data Depository group.

This dictionary was constructed based on word lists that were extracted from Turkish text corpora and dictionaries. You can find details about the performance of this spell checker [here](https://github.com/tdd-ai/spell-checking-and-correction/blob/main/README.md#turkish-spell-checker-benchmark).

## Evaluation

When compared to other spellcheckers on the [trspell-10](https://data.tdd.ai/#/3477863a-9a7d-4b96-b13f-7afac1490ce0) dataset, Hunspell-tr performs much better in terms error correction accuracy.

| Spell Checker | Error detection Precision | Error detection Recall | Error detection F1-Score | Correction accuracy |
| --- | --- | --- | --- | --- |
| [zemberek-python](https://github.com/Loodos/zemberek-python)                                            | **99.94** | 94.21 | 96.99 | 93.05 |
| Hunspell-based |||||
| [hunspell-tr](https://github.com/hrzafer/hunspell-tr) (hrzafer)                                         | 99.63 | **99.36** | **99.50** | 79.61 |
| [TDD hunspell-tr](https://github.com/tdd-ai/hunspell-tr) (ours)                                         | 99.90 | 97.30 | 98.58 | **94.67** |

**Contributors** (alphabetically):

- Ali Safaya
- Arda Göktoğan 
- Deniz Yuret
- Emirhan Kurtuluş
- Taner Sezer

## Citation

```
@inproceedings{safaya-etal-2022-mukayese,
    title = "Mukayese: {T}urkish {NLP} Strikes Back",
    author = "Safaya, Ali  and
      Kurtulu{\c{s}}, Emirhan  and
      Goktogan, Arda  and
      Yuret, Deniz",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2022",
    month = may,
    year = "2022",
    address = "Dublin, Ireland",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.findings-acl.69",
    doi = "10.18653/v1/2022.findings-acl.69",
    pages = "846--863",
    abstract = "Having sufficient resources for language X lifts it from the under-resourced languages class, but not necessarily from the under-researched class. In this paper, we address the problem of the absence of organized benchmarks in the Turkish language. We demonstrate that languages such as Turkish are left behind the state-of-the-art in NLP applications. As a solution, we present Mukayese, a set of NLP benchmarks for the Turkish language that contains several NLP tasks. We work on one or more datasets for each benchmark and present two or more baselines. Moreover, we present four new benchmarking datasets in Turkish for language modeling, sentence segmentation, and spell checking. All datasets and baselines are available under: https://github.com/alisafaya/mukayese",
}
```
