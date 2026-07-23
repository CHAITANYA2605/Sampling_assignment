# Sampling Techniques and Model Comparison

A Jupyter notebook that studies how different sampling strategies affect
classification performance on an imbalanced dataset.

## Techniques covered

- Random oversampling
- Simple random sampling
- Systematic sampling
- Stratified sampling
- Cluster sampling
- Bootstrap sampling

The sampled datasets are evaluated with several scikit-learn classifiers,
including logistic regression, decision trees, random forests, support vector
machines, and Naive Bayes.

## Run locally

```bash
git clone https://github.com/CHAITANYA2605/Sampling_assignment.git
cd Sampling_assignment
python -m venv .venv
source .venv/bin/activate
pip install jupyter pandas numpy scipy seaborn matplotlib scikit-learn imbalanced-learn
jupyter notebook Sampling_assignment.ipynb
```

## Workflow

1. Load and inspect the dataset.
2. Balance the target classes.
3. Calculate samples with multiple strategies.
4. Train the same model set on each sample.
5. Compare the resulting accuracy scores.

## Reproducibility

Notebook outputs capture the original experiment. Re-running with newer
library versions or a different random seed may produce different values.
