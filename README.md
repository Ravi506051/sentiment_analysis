# Sentiment Analysis Using Machine Learning

A natural-language-processing project that explores how text can be prepared and classified by sentiment using machine-learning techniques.

## Objectives
- Explore and understand a labelled text dataset.
- Clean and normalize raw text.
- Convert text into numerical features.
- Train a text-classification model.
- Evaluate and interpret model predictions.

## Workflow
1. Load the dataset and inspect label distribution.
2. Preprocess text consistently.
3. Create train/test splits before fitting transformations.
4. Vectorize text using the method implemented in the notebook.
5. Train the selected classifier.
6. Review precision, recall, F1-score and the confusion matrix.

## Technology
Python · NLP · Pandas · NumPy · Scikit-learn · Matplotlib · Jupyter Notebook

## Getting started
```bash
git clone https://github.com/Ravi506051/sentiment_analysis.git
cd sentiment_analysis
python -m venv .venv
# Windows: .venv\\Scripts\\activate
pip install pandas numpy scikit-learn matplotlib jupyter
jupyter notebook
```

## Evaluation notes
Use a held-out test set and report actual measured results. Check class imbalance and inspect errors by sentiment category. Avoid fitting text preprocessing or vectorization on the test data.

## Future improvements
Compare multiple classifiers, add error analysis for ambiguous text and evaluate robustness to spelling variations and unseen vocabulary.

## Maintainer
**Ravi Kumar Rao** · [GitHub](https://github.com/Ravi506051)
