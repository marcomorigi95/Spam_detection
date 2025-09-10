# Spam Detection

## ▶️ Run the Notebook in Google Colab

Click below to open the notebook:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1W-owP2t7sQAt1k9QU7yPMKCQkxleQQ7D?usp=sharing)


---

# Spam Email Classification & Content Analysis

**Objective:**
This project aims to **identify and analyze spam emails**, with the ultimate goal of enhancing the **security of corporate communications** and improving **anti-spam filters** through deep semantic and topic analysis.

---

## Project Overview

Spam emails are a persistent threat to business operations. This project provides a complete pipeline for:

* Classifying emails as **spam** or **legitimate**.
* Performing **topic modeling** and **semantic analysis** on spam content.
* Extracting valuable entities (e.g., organizations) from legitimate emails to support **business intelligence** and improve communication workflows.

---

## Key Outcomes

### Improved Anti-Spam Filtering

An efficient classifier significantly reduces the number of unwanted emails reaching inboxes, leading to more secure and productive corporate communication.

### In-Depth Content Analysis

Through **topic modeling**, the system identifies recurring spam content trends, improving understanding of attacker strategies and enhancing cybersecurity readiness.

### Heterogeneity Assessment

Using **semantic distance metrics**, the model evaluates the diversity of spam topics — a critical step for defending against varied attack vectors.

### Organization Extraction

By applying **Named Entity Recognition (NER)** to legitimate emails, the system extracts organization names to support CRM systems, customer segmentation, and partner management.

---

## Project Workflow

The project follows a modular workflow:

1. **EDA of Raw Emails**

   * Initial exploration of email structure, metadata, and common spam markers.

2. **EDA of Preprocessed Emails**

   * Tokenization, stopword removal, lemmatization, and vectorization.

3. **Email Classification**

   * Training and evaluation of models to distinguish spam from ham (legitimate emails).

4. **Topic Modeling (LDA)**

   * Extraction of latent topics from spam emails using **Latent Dirichlet Allocation**.

5. **Topic Distance Analysis**

   * Semantic comparison of topics to understand content diversity.

6. **Named Entity Recognition (NER)**

   * Extraction of named entities (like organizations) from non-spam emails using NLP techniques.

7. **Testing & Evaluation**

   * Final validation of model performance and topic coherence.

8. **Conclusion**

   * Key findings and future directions.

