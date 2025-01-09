# Support Vector Machine (SVM) Document Classifier

This project demonstrates the implementation of a **Support Vector Machine (SVM)** from scratch to classify news articles into 20 predefined categories using the **20 Newsgroups dataset**. The project focuses on understanding SVM fundamentals by implementing both **linear soft-margin SVM** and **polynomial kernel SVM** for multi-class classification tasks.

---

## Features
- **Custom Implementation**: 
  - Linear soft-margin SVM for high-dimensional linear classification tasks.
  - Polynomial kernel SVM for non-linear decision boundaries.
- **Preprocessing Pipeline**: 
  - Cleaned metadata (e.g., `From`, `Subject`).
  - Tokenized and vectorized text using **TF-IDF**.
  - Removed the top 300 most frequent words (stop words).
- **Multi-Class Classification**: Implemented the **One-vs-All strategy** to handle multi-class datasets efficiently.
- **Performance Evaluation**: 
  - Evaluated using classification accuracy, confusion matrices, and kernel comparisons.

---

## Dataset
The dataset consists of 20,000 articles categorized into 20 different groups (e.g., politics, sports, technology). It is a widely used dataset for text classification tasks.

- **Dataset Preprocessing**:
  1. Metadata Removal: Removed headers like `From` and `Subject` from the dataset.
  2. Tokenization: Split the articles into tokens for analysis.
  3. Stop Words: Excluded the top 300 most frequent words to reduce noise.
  4. Splitting: Each class was divided equally into training (50%) and testing (50%) datasets.

You can access the dataset here: [20 Newsgroups Data](http://www.cs.cmu.edu/afs/cs/project/theo-11/www/naive-bayes.html).

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - NumPy: Matrix operations and numerical computations.
  - pandas: Data manipulation and analysis.
  - matplotlib: Visualizations (e.g., confusion matrices).
  - `qpsolvers`: For solving quadratic programming problems in SVM optimization.

---

