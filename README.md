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
@misc{kazqad,
      title={KazQAD: Kazakh Open-Domain Question Answering Dataset}, 
      author={Rustem Yeshpanov and Pavel Efimov and Leonid Boytsov and Ardak Shalkarbayuli and Pavel Braslavski},
      year={2024},
      eprint={2404.04487},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

