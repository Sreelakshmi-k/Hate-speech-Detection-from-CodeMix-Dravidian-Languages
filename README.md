# Hate-speech-Detection-from-CodeMix-Dravidian-Languages
## Short description 
### What's the problem?
This work is to hate speech from three CodeMix Dravidian languages. The languages considered are Tamil-English, Malayalam-English and Kannada-English. The task of hate speech detection is challenging due to the CodeMix nature of the content in social media platforms. In this paper we try to address this. We also introduce a new set of annotated Malayalam-English dataset.
### How can technology help?
The existing transformer models especially multilingual transformer models help in getting embeddings for the CodeMix data. We explore the multilingual transformer models : BERT, DistilBERT, XLM-RoBERTa, LaBSE, MuRIL, FNet,and IndicBERT through this work. For this we used the Sentence Transformers package.
## Dataset Description
Here six openly available datasets falling in three CodeMIx languages namely Tamil-English, Malayalam-English and Kannada-English are used. In addition we also have introduced a new set of annoated Malayalam-English data.
### Dataset Sources
Chakravarthi, Bharathi Raja, et al. "Findings of the shared task on offensive language identification in Tamil, Malayalam, and Kannada." Proceedings of the First Workshop on Speech and Language Technologies for Dravidian Languages. 2021.

Mandl, Thomas, et al. "Overview of the hasoc track at fire 2020: Hate speech and offensive language identification in tamil, malayalam, hindi, english and german." Forum for Information Retrieval Evaluation. 2020.

B. R. Chakravarthi, P. K. Kumaresan, R. Sakuntharaj, Madasamy, A. Kumar, S. Thavareesan, P. B, K. Sreelakshmi,S. Chinnaudayar Navaneethakrishnan, J. P. McCrae, T. Mandl, Overview of the HASOC-DravidianCodeMix Shared Taskon Offensive Language Detection in Tamil and Malayalam, in: Working Notes of FIRE 2021 - Forum for InformationRetrieval Evaluation, CEUR, 2021.

### In-house data
It has 1000 youtube commets labelled to two classes "Hate" and "Non-hate"

## Built with
Python

Sentence Transformers

SKlearn
