<h1 align="center">KazQAD:<br><small>Kazakh Open-Domain Question Answering Dataset</small></h1>


<p align="center">
  <a href="https://github.com/IS2AI/KazQAD/stargazers">
    <img src="https://img.shields.io/github/stars/IS2AI/KazQAD.svg?colorA=orange&colorB=orange&logo=github"
         alt="GitHub stars">
  </a>
  <a href="https://github.com/IS2AI/KazQAD/issues">
    <img src="https://img.shields.io/github/issues/IS2AI/KazQAD.svg"
         alt="GitHub issues">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/static/v1?label=license&amp;message=CC BY-SA 4.0&amp;color=red&amp"
         alt="CC BY-SA 4.0">
  </a>
  <a href="https://issai.nu.edu.kz">
    <img src="https://img.shields.io/static/v1?label=ISSAI&amp;message=official site&amp;color=blue&amp"
         alt="ISSAI Official Website">
  </a>
</p>



<h4 align="center">
    <p>
        <a href="https://arxiv.org/abs/2404.04487">Paper</a> |
        <a href="data">Data</a> |
        <a href="baselines">Baselines</a> |
        <a href="https://huggingface.co/datasets/issai/kazqad">HuggingFace</a>
    </p>
</h4>

**KazQAD** is a **Kaz**akh open-domain **Q**uestion **A**nswering **D**ataset
that can be used in both reading comprehension and full ODQA settings, as well as for information retrieval experiments.

## Data Sources
- [Kazakh Wikipedia (a dump of 01-Jan-2023)](https://dumps.wikimedia.org/kkwiki)
- [Google's Natural Questions (NQ)](https://github.com/google-research-datasets/natural-questions)
- [Unified National Testing (UNT) questions](https://egov.kz/cms/en/articles/about_ent) 


The questions come from two sources: translated items from the Natural Questions (NQ) dataset (only for training) and 
the original Kazakh Unified National Testing (UNT) exam (for development and testing).


## Citation 🎓
```bibtex
@inproceedings{yeshpanov-etal-2024-kazqad,
    title = "{K}az{QAD}: {K}azakh Open-Domain Question Answering Dataset",
    author = "Yeshpanov, Rustem  and
      Efimov, Pavel  and
      Boytsov, Leonid  and
      Shalkarbayuli, Ardak  and
      Braslavski, Pavel",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italia",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.843",
    pages = "9645--9656",
    abstract = "We introduce KazQAD{---}a Kazakh open-domain question answering (ODQA) dataset{---}that can be used in both reading comprehension and full ODQA settings, as well as for information retrieval experiments. KazQAD contains just under 6,000 unique questions with extracted short answers and nearly 12,000 passage-level relevance judgements. We use a combination of machine translation, Wikipedia search, and in-house manual annotation to ensure annotation efficiency and data quality. The questions come from two sources: translated items from the Natural Questions (NQ) dataset (only for training) and the original Kazakh Unified National Testing (UNT) exam (for development and testing). The accompanying text corpus contains more than 800,000 passages from the Kazakh Wikipedia. As a supplementary dataset, we release around 61,000 question-passage-answer triples from the NQ dataset that have been machine-translated into Kazakh. We develop baseline retrievers and readers that achieve reasonable scores in retrieval (NDCG10 = 0.389 MRR = 0.382), reading comprehension (EM = 38.5 F1 = 54.2), and full ODQA (EM = 17.8 F1 = 28.7) settings. Nevertheless, these results are substantially lower than state-of-the-art results for English QA collections, and we think that there should still be ample room for improvement. We also show that the current OpenAI{'}s ChatGPTv3.5 is not able to answer KazQAD test questions in the closed-book setting with acceptable quality. The dataset is freely available under the Creative Commons licence (CC BY-SA) at url https://github.com/IS2AI/KazQAD",
}
```

