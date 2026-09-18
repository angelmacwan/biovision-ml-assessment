# ML Assessment: Image Processing

## Setup

To download the data , clone this repo using git clone

```bash
git clone https://github.com/angelmacwan/biovision-ml-assessment.git
```

or download it by clicking the "code" button and selecting "Download ZIP" option

## Background

Meibography provides an imaging-based method for visualizing these glands and assessing the extent of gland loss or damage.

In this assessment, you will work with meibography images and corresponding expert-assigned severity scores.

The goal is to investigate whether machine learning can be used to automatically estimate MGD severity from an image.

## Problem Statement

You are provided with a dataset of meibography images along with expert-assigned MGD severity scores ranging from **1 to 4**, where higher scores represent greater disease severity.

Your task is to develop a machine-learning pipeline that takes a meibography image as input and predicts its corresponding **severity score**.

You are free to choose the machine-learning formulation and model architecture. For example, you may consider classification, ordinal classification, regression, or another approach that you believe is appropriate.

You must **justify your choice of problem formulation, preprocessing, model, training strategy, and evaluation methodology.**

The objective is not simply to obtain the highest numerical score. We are interested in your ability to design, implement, evaluate, and critically analyze an ML solution to a real-world medical imaging problem.

## Dataset

The provided dataset contains:

- Meibography images
- Corresponding expert severity scores

Only the original images and scoring information are provided.

You should treat the dataset as a real-world dataset and investigate its characteristics before designing your model.

## Tasks

Your submission should address the following:

1. Data Analysis
2. Data Preprocessing
3. Model Development
4. Evaluation
5. Error and Failure Analysis
6. Model Interpretation
7. Critical Analysis

## Submission Requirements

Please submit:

1. **Source code / Jupyter notebook**
2. **ASSIGNMENT.md** explaining your methodology and results
3. **Requirements file** such as `requirements.txt` or `environment.yml`

The code should be reproducible and should include instructions for running the complete pipeline.

## Use of AI Tools

The use of AI-assisted development tools is permitted.

However:

- Candidates must disclose which AI tools they used.
- Candidates must be able to explain their submitted solution.
- Candidates are responsible for verifying and understanding all generated code.
- Any external pretrained models, datasets, or significant external resources used must be clearly documented.

Model performance will be evaluated using metrics appropriate for the problem. Performance will not be judged solely on accuracy.

## Expected Effort

Candidates are not expected to build a production-ready system. The objective is to demonstrate their approach to solving and analyzing an ML problem.

Candidates are free to run training and inference **locally or on cloud platforms** such as [Kaggle Notebooks](https://www.kaggle.com/code) or [Google Colab](https://colab.research.google.com). If using a cloud environment, please include the notebook link or export it and submit it as part of your solution.

## Important

There is no single prescribed solution.

We are interested in **how you approach the problem and why you make your decisions**, rather than whether you use a particular model or framework.
