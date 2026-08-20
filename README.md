# Hindi-SEPSIS Balanced Dataset

## Overview

This repository contains a balanced dataset developed for **Hindi Septic and Pure sentence classification**.

The dataset consists of Hindi news sentences categorized into two classes:

* **Septic**
* **Pure**

It is intended to support research in **Hindi Natural Language Processing (NLP)**, **text classification**, **news analysis**, and **machine learning-based classification**.

---

## Dataset Statistics

| Category        | Number of Sentences |
| --------------- | ------------------: |
| Total Sentences |                 100 |
| Septic          |                  50 |
| Pure            |                  50 |

The dataset is balanced, with an equal number of sentences in both classes.

---

## Dataset Columns

The dataset contains the following columns:

| Column                 | Description                                 |
| ---------------------- | ------------------------------------------- |
| `Hindi News Sentences` | Hindi news sentence used for classification |
| `Label`                | Classification label: `Septic` or `Pure`    |
| `Domain`               | News category or domain                     |

---

## Domains

The dataset includes sentences from the following domains:

* Political
* Disputes
* Business
* Sports
* International Affairs
* Entertainment
* Technology

This domain diversity allows the dataset to include Hindi news sentences from different contexts and topics.

---

## Classification Task

The primary task supported by this dataset is **binary text classification**.

### Input

A Hindi news sentence.

### Output

The model should classify the sentence into one of the following categories:

* `Septic`
* `Pure`

---

## Dataset File

The dataset is available in the following file:

`Balanced_Sepsis_Categorized.xlsx`

The file can be loaded using Python and Pandas:

```python
import pandas as pd

df = pd.read_excel("Balanced_Sepsis_Categorized.xlsx")

print(df.head())
```

---

## Intended Use

This dataset can be used for:

* Hindi NLP research
* Text classification
* Machine learning experiments
* Deep learning experiments
* Linguistic analysis
* News analysis
* Bias detection research
* Septic/Pure sentence classification
* Feature engineering
* Hybrid machine learning approaches

---

## Possible Machine Learning Models

The dataset can be used to experiment with different machine learning and deep learning models, such as:

* Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* XGBoost
* Multilayer Perceptron (MLP)
* LSTM
* Transformer-based models
* Ensemble and Hybrid Models

---

## Recommended Evaluation Metrics

Models trained on this dataset can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Since the dataset is balanced, accuracy and F1-score can be useful metrics for comparing classification performance.

---

## Limitations

This dataset contains **100 sentences** and is primarily intended for research and experimental purposes.

Some limitations include:

* The dataset size is relatively small.
* Domain distribution is not equal across all categories.
* Results may not generalize to all Hindi news sources.
* Larger datasets may be required for training complex deep learning or transformer models.

Researchers may use cross-validation or additional datasets for more comprehensive evaluation.

---

## Ethical and Copyright Considerations

This dataset is intended for **academic and research purposes**.

Users should:

* Respect the copyright and terms of use of original news sources.
* Use the dataset responsibly.
* Avoid harmful or misleading applications.
* Properly acknowledge the dataset and associated research where applicable.

---

## Contact

**Dr. Soma Das**
Department of Computer Science and Engineering
Institute of Engineering & Management, Kolkata
