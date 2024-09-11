## Topic Modeling with Brown University Corpus

This repository contains code and resources for performing topic modeling using the Brown University corpus from the `nltk` library. The project explores various topic modeling techniques, including Non-Negative Matrix Factorization (NMF), Latent Dirichlet Allocation (LDA), and Latent Semantic Analysis (LSA). The goal of this work is to examine how each model identifies topics within the corpus and compare the resulting topic allocations.

### Overview

Topic modeling is a crucial text analysis technique aimed at answering the question: "What are these documents about?" This project leverages three popular methods to explore the topics in the Brown University corpus, which already has documents categorized into topics. This allows for direct comparison between model-generated topics and the official classifications.

### Methods Used

The project focuses on three different topic modeling techniques:

1. **Non-Negative Matrix Factorization (NMF)**: A matrix factorization method used to identify topics by breaking down the term-document matrix.
2. **Latent Semantic Analysis (LSA)**: A technique that applies singular value decomposition (SVD) to reveal patterns in the relationships between terms and documents.
3. **Latent Dirichlet Allocation (LDA)**: A generative statistical model that assigns documents to multiple topics based on word distributions.
