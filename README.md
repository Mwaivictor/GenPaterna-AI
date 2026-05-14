# Machine Learning-Assisted Decision Support System for DNA-Based Paternity Analysis

## Project Overview

This project is a **data engineering, machine learning, and research-driven decision support system** designed to assist forensic and clinical laboratories in analyzing DNA **Short Tandem Repeat (STR)** profiles for biological relationship inference, particularly paternity determination.

The system applies modern **machine learning and statistical learning techniques** to improve the **accuracy, efficiency, scalability, and interpretability** of DNA-based relationship analysis while maintaining alignment with forensic science principles.

It is designed as an experimental and educational platform exploring how AI can augment traditional forensic genetics workflows.


## Project Objectives

* Develop a machine learning-based system for DNA paternity prediction
* Compare multiple supervised learning algorithms for biological relationship classification
* Design a scalable data pipeline for DNA STR processing and feature engineering
* Build a decision support system for forensic and clinical use cases
* Conduct a research-driven evaluation of ML effectiveness in forensic genetics

---

## Data Sources

DNA STR profile datasets can be obtained or generated from:

* Kaggle — [https://www.kaggle.com](https://www.kaggle.com)
* UCI Machine Learning Repository — [https://archive.ics.uci.edu/ml](https://archive.ics.uci.edu/ml)
* 1000 Genomes Project — [https://www.internationalgenomes.org](https://www.internationalgenomes.org)
* NCBI GenBank — [https://www.ncbi.nlm.nih.gov/genbank](https://www.ncbi.nlm.nih.gov/genbank)
* Programmatically generated synthetic STR inheritance datasets

## Data Engineering Pipeline

The system implements an end-to-end forensic data processing workflow:

* DNA STR data extraction or synthetic generation
* Structured storage using PostgreSQL / MySQL / SQLite
* Data cleaning and preprocessing
* Handling missing or incomplete genetic markers
* Normalization of STR allele values
* Encoding DNA profiles into ML-ready numerical representations

## System Features

The platform provides tools for forensic and clinical decision support:

* Upload or input DNA STR profiles
* Compare child and alleged parent genetic markers
* Predict probability of biological parenthood
* Identify matching and non-matching loci
* Generate confidence scores for predictions
* Visualize inheritance patterns and genetic similarity distributions
* Support interpretability of predictions for forensic review

## Machine Learning Models

The system evaluates multiple supervised learning models:

* Logistic Regression
* Decision Trees
* Random Forest
* Support Vector Machines (SVM)
* XGBoost
* Neural Networks

Each model is benchmarked to determine suitability for structured genetic relationship inference.

## Feature Engineering

Genetic features extracted from STR profiles include:

* STR marker similarity scores
* Allele frequency comparisons
* Count of matching loci between profiles
* Genetic distance metrics
* Mutation probability adjustments
* Weighted inheritance consistency scores


## Evaluation Metrics

Model performance is assessed using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC

Additional forensic-focused evaluation may include:

* False match rate (FMR)
* False exclusion rate (FER)


## Research & Experimental Analysis

This project includes a formal research component exploring the intersection of **machine learning and forensic genetics**.

Key research questions include:

* Which ML models perform best for STR-based paternity inference?
* How does feature engineering affect predictive accuracy?
* Can ML improve or complement traditional statistical paternity indices?
* What are the limitations of applying ML to forensic genetic data?
* How can bias, uncertainty, and data quality be handled effectively?

The study also examines:

* Data preprocessing challenges in forensic genetics
* Model interpretability and explainability requirements
* Ethical, legal, and privacy considerations in genetic data systems
* Practical integration of AI tools into laboratory workflows

## Expected Findings

* Identification of the most effective ML model for paternity prediction
* Quantified impact of feature selection on model performance
* Comparison between classical statistical methods and ML approaches
* Insights into limitations of ML in forensic DNA analysis
* Practical use cases in clinical and forensic environments
* Recommendations for hybrid (statistical + ML) decision systems


## Final Deliverables

* Structured DNA STR database
* Cleaned and processed datasets
* Data generation and simulation scripts
* Full preprocessing and feature engineering pipeline
* Machine learning training and evaluation framework
* Paternity prediction engine (API or backend service)
* Visualization dashboard / web application
* Model comparison and evaluation report
* Full research paper / technical documentation
* Ethical, legal, and privacy impact assessment
* Final presentation and demonstration


## Project Impact

This project has significant potential impact across **forensic science, clinical genetics, and artificial intelligence research**.

### 1. Advancement of Forensic Genetics Through AI

This system demonstrates how machine learning can augment traditional DNA analysis workflows by introducing:

* Pattern recognition beyond manual statistical comparison
* Automated STR profile matching
* Predictive modeling for relationship inference
* Improved consistency in forensic interpretation

It contributes to the evolving field of **computational forensic genetics**.


### 2. Improved Efficiency in Laboratory Workflows

By automating key steps in DNA STR analysis, the system can:

* Reduce manual workload in forensic laboratories
* Speed up case processing times
* Improve scalability for high-volume testing environments
* Reduce human computational errors

This makes forensic workflows more efficient and standardized.


### 3. Enhanced Interpretability and Decision Support

Unlike black-box predictions, the system is designed to provide:

* Locus-level explanation of matches and mismatches
* Confidence scoring with transparency
* Feature-based reasoning for predictions
* Visual interpretation of genetic similarity

This supports **human-in-the-loop forensic decision-making** rather than replacing expert judgment.

### 4. Accessibility for Resource-Constrained Regions

The platform can be particularly valuable in regions with limited forensic infrastructure by:

* Reducing dependence on expensive proprietary systems
* Supporting open research and education in forensic genetics
* Providing a low-cost decision support alternative for laboratories
* Enabling training in computational biology and forensic AI


### 5. Research Contribution to Computational Biology

This project contributes to scientific understanding of:

* Machine learning performance on structured genetic data
* Comparison of statistical vs ML-based genetic inference
* Feature engineering strategies for STR datasets
* Limitations and risks of AI in forensic genetics

It can serve as a foundation for academic publication or advanced research.


### 6. Ethical and Responsible AI in Genetics

The system emphasizes:

* Data privacy and responsible handling of genetic information
* Transparency and explainability in predictions
* Clear separation between research tools and certified forensic systems
* Ethical awareness in AI-assisted biological decision-making

### Overall Impact Statement

> This project demonstrates how machine learning can act as a **decision-support layer on top of classical forensic genetics**, improving efficiency, interpretability, and scalability while preserving scientific rigor and ethical responsibility.


## Contact

For inquiries, collaboration, or research discussions:

📧 Email: [mwaivictorbrian68@gmail.com](mailto:mwaivictorbrian68@gmail.com)


## ⚠️ Disclaimer

This project is intended strictly for **educational and research purposes only**.
It is **not certified for legal, forensic, or clinical diagnostic use**.

This project is intended for **educational and research purposes only** and is not designed for certified forensic or legal use.
