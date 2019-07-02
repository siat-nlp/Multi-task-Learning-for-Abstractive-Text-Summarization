# 2019-AAAI-Multitask-Sum
A Multi-task Learning Framework for Abstractive Text Summarization

## Abstract
We propose a Multi-task learning approach for Abstractive Text Summarization (MATS), motivated by the fact that humans have no difficulty performing such task because they have the capabilities of multiple domains. Specifically, MATS consists of three components: (i) a text categorization model that learns rich category-specific text representations using a bi-LSTM encoder; (ii) a syntax labeling model that learns
to improve the syntax-aware LSTM decoder; and (iii) an abstractive text summarization model that shares its encoder and decoder with the text categorization and the syntax labeling tasks, respectively. In particular, the abstractive text summarization model enjoys significant benefit from the additional text categorization and syntax knowledge. Our experimental results show that MATS outperforms the competitors.1
