# CLEF2025-CheckThat Competition

## Group 6: TruthTrackers

This repository has been cloned from the original [CLEF 2025 CheckThat Task 4 repository](https://gitlab.com/checkthat_lab/clef2025-checkthat-lab/-/tree/main/task4)

It contains the _dataset_, _format checker, scorer and baselines_ for each task of the [CLEF2025-CheckThat! Lab](https://checkthat.gitlab.io/).

To run the notebooks, use a Python version 3.9 and higher and install the required libraries with:

```bash
pip install -r requirements.txt
```

The repository is structured into three directories categorized by the assigned approaches.
1. Traditional information retrieval
2. Representation learning
3. Neural reranking

In every directory there are several notebooks, which are executable out of the box except for two notebooks
- `embedding_gpt.ipynb` and `reranking_gpt.ipynb` require an OPENAI_KEY


