# Linguistic_Hierarchy
In the report, we show that large language models represent multilingual categorical concepts as simplices and hierarchical relations as orthogonality.

We confirm our theory with Gemma-7B representations and this repo provides the code for the experiments.

## Data
[`Germanic_full_nouns.json`](data/Germanic_full_nouns.json) and [`Romance_full_nouns.json`](data/Romance_full_nouns.json) are sets nouns taken from the most used nouns in each sampled language.
Germanic includes English, German, Dutch and Swedish. Romance includes French, Spanish, Portuguese and Italian.


## Requirement
You need to install Python packages `transformers`, `networkx`, `scikit-learn`, `nltk`, `inflect`, `torch`, `numpy`, `seaborn`, `matplotlib`, `json`, and `tqdm` to run the codes. Also, some GPUs would be helpful to implement the codes efficiently.

Run `store_matrices_bm.ipynb` first to store the unembedding vectors, before you run other jupyter notebooks.

## Experiments
- [**`1.1_Germanic_nouns.ipynb`**](1_Germanic_nouns.ipynb) and [**`1.2_Romance_nouns.ipynb`**](1.2_Romance_nouns.ipynb): Experiments based on sampled nouns, these are part of the results in the final report.
- [**`2.1_Germanic_verbs.ipynb`**](2.1_Germanic_verbs.ipynb) and [**`2.2_Romance_verbs.ipynb`**](2.2_Romance_verbs.ipynb): Experiments based on sampled verbs, not part of final report.
- [**`3.1_Germanic_adjectives.ipynb`**](2.1_Germanic_verbs.ipynb) and [**`3.2_Romance_adjectives.ipynb`**](2.2_Romance_verbs.ipynb): Experiments based on sampled adjectives, not part of final report.
