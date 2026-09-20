# AI/ML Research Technical Assessment

Repository containing data and problem statements for the BioVision AI/ML technical assessment.

---

## Repository Structure

```text
.
├── ASSIGNMENT 1/
│   ├── ASSIGNMENT 1.md    # Text & Emotion Analytics problem statement
│   └── DATASET/
│       ├── data01.csv     # 28 fine-grained emotion multi-hot labels
│       └── data02.csv     # 6 basic emotion multiclass labels
├── ASSIGNMENT 2/
│   ├── ASSIGNMENT 2.md    # Medical Image Processing (MGD severity) problem statement
│   └── DATASET/           # Meibography images and severity scores
└── README.md
```

---

## Overview

### [Assignment 1: Applied Text & Emotion Analytics Challenge](ASSIGNMENT%201/ASSIGNMENT%201.md)

- **Domain**: NLP / Text Classification.
- **Goal**: Formulate, train, and evaluate an emotion classification pipeline using fine-grained (28 classes) and/or broad (6 classes) datasets.
- **Key aspects**: Exploration, multi-label/multiclass handling, embeddings/representations, evaluation metrics (F1, PR-AUC), error diagnostics.

### [Assignment 2: Meibography Image Processing Challenge](ASSIGNMENT%202/ASSIGNMENT%202.md)

- **Domain**: Computer Vision / Medical Imaging.
- **Goal**: Build an ML/DL pipeline predicting expert-assigned Meibomian Gland Dysfunction (MGD) severity scores (grades 1–4).
- **Key aspects**: Formulation choice (regression, ordinal, multiclass), preprocessing, model architecture, interpretability, error analysis.

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/angelmacwan/biovision-ml-assessment.git
```

Or download via **Code -> Download ZIP** on GitHub.

### Environment & Compute

- Run experiments locally or via cloud environments ([Google Colab](https://colab.research.google.com), [Kaggle Notebooks](https://www.kaggle.com/code)).
- If cloud notebooks are used, provide accessible view/run links or export runnable `.ipynb` files.

---

## Submission Instructions

Submit your solution as a **ZIP archive via email**.

### 1. Package Structure

Include your code, reports, and environment configs in your submission:

```text
submission_<your_name>.zip
├── ASSIGNMENT 1/
│   ├── report.md (or technical summary)
│   ├── notebook_or_scripts/
│   └── requirements.txt
└── ASSIGNMENT 2/
    ├── report.md (or technical summary)
    ├── notebook_or_scripts/
    └── requirements.txt
```

> **Note**: Do **not** include raw image/CSV dataset files in your ZIP upload to keep file size reasonable.

### 2. Deliverables Checklist

For each completed assignment, provide:

- **Code**: Clean, reproducible Jupyter notebook(s) or Python scripts with random seeds set.
- **Environment**: `requirements.txt` or `environment.yml` with dependencies.
- **Technical Report**: Summary explaining problem formulation, key decisions, baseline comparisons, evaluation results, failure analysis, and limitations.
- **AI Disclosure**: Explicit statement of any AI-assisted tools (ChatGPT, Claude, Cursor, Copilot, etc.) used during development.

### 3. Sending the Submission

- Compress your submission directory into a `.zip` file.
- Email the `.zip` file (or a secure cloud download link such as Google Drive / Dropbox if file exceeds email limits) to the recruiter / hiring contact.
- Use the email subject line: `AI/ML Assessment Submission - [Your Full Name]`.
