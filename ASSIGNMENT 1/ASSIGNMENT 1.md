# Technical Assessment: AI/ML Research Position

## Project Assessment 1: Applied Text & Emotion Analytics Challenge

### 1. Problem Statement

Design, implement, and evaluate an effective and robust emotion classification solution using the provided datasets.

Rather than following a predefined protocol, you must formulate your own end-to-end analytical and modelling approach. Independently explore the available data, understand the relationship between datasets and emotion labels, identify technical challenges, and build a sound, well-justified solution.

The goal is not simply chasing high metric scores. We evaluate your ability to formulate a clear approach, justify technical decisions, handle real-world text challenges, and critically interpret outcomes.

---

### 2. Datasets

The dataset files are located in `ASSIGNMENT 1/DATASET/`:

1. **`data01.csv`**:
    - Contains text samples with multi-hot encoded indicators across 28 fine-grained emotion categories (GoEmotions taxonomy).
    - Multi-label classification structure.
2. **`data02.csv`**:
    - Contains text sentences mapped to 6 broader basic emotion categories.
    - Single-label multiclass structure.

You are free to decide how these datasets are leveraged: independently, jointly, sequentially (pretraining/fine-tuning), or via hierarchical/transfer learning. State your choice and rationale clearly.

---

### 3. Key Technical Areas

Address the following areas in your solution:

- **Data Exploration & Diagnostics**: Label distributions, class imbalances, multi-label co-occurrence, text length profiles, noise/unclear samples.
- **Data Integrity**: Clean train/val/test splits, prevention of data leakage across preprocessing and evaluation.
- **Feature Representation**: Choice of text embeddings/representations (e.g., TF-IDF baselines, contextual transformer representations).
- **Modelling Strategy**: Baseline establishment, architecture choice, training dynamics, loss functions suited for imbalanced/multi-label tasks.
- **Evaluation Methodology**: Appropriate multi-label and multiclass metrics (Macro/Micro F1, Precision, Recall, PR-AUC). Do not rely solely on accuracy.
- **Error & Failure Analysis**: Systematic error inspection, confusion analysis across correlated emotion labels, model limitations.

---

### 4. Expected Deliverables

#### 4.1 Source Code / Notebook

- Clean, executable code or Jupyter notebook (`.ipynb` / `.py`).
- Reproducible pipeline with fixed seeds and explicit instructions.
- Environment specification (`requirements.txt` or `environment.yml`).

#### 4.2 Technical Summary Report

Submit a summary report (can be written directly into `ASSIGNMENT 1.md` or a separate `REPORT.md`) detailing:

- Problem formulation and core assumptions.
- Key findings from exploratory analysis.
- Pipeline design, modeling choices, and technical trade-offs.
- Experimental results and baseline comparisons.
- Error analysis, failure modes, and observed limitations.
- Concrete next steps for improvements.

---

### 5. Use of AI Tools

AI-assisted tools (ChatGPT, Copilot, Claude, Cursor, etc.) are permitted under these conditions:

- Disclose tool usage in your report.
- Fully understand and be ready to defend all submitted code and architectural choices.
- Document all pretrained model checkpoints and external resources utilized.
