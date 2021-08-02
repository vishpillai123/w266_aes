# W266 Automated Essay Scoring Final Project
## Group Members: Sharon Wu, Candice Sener, Vish Pillai

### Abstract: 

Our project aims to develop AES by using BERT base and BERT-LSTM models in order to assess whether an RNN layer is needed for an effective two-stage learning framework. We found that our BERT base model is competitive to the original TSLF-1 (https://arxiv.org/pdf/1901.07744v2.pdf). On another note, our implementation of clique-based coherence based on BERT’s sentence pairing feature was ineffective in capturing coherence of longer passages. Overall, we found that TSLF-ALL demonstrated robustness with small sample sizes and adversarial samples.

**Dataset:** Kaggle ASAP Dataset by The Hewlett Foundation

### GitHub Repo Organization:

Each folder includes a .ipynb notebook that corresponds to the name of the folder. 

### Folders:
* EDA 
* Semantic Score
* Prompt-Relevance Score
* Coherence Score
* Second Stage 
