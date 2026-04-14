# Replication of Coan et al. (2021)
## Computer-assisted classification of contrarian claims about climate change

### Paper
Coan, T.G., Boussalis, C., Cook, J. and Nanko, M.O., 2021. Computer-assisted classification of contrarian claims about climate change. Scientific Reports, 11, 22320.
https://www.nature.com/articles/s41598-021-01714-4

### Original Code
https://github.com/traviscoan/cards

### Data
Download the data from:
https://drive.google.com/uc?export=download&id=14exmlYCT3-K2byYHFFrShAIYiemJQroi

After downloading, unzip the file and place the data/ folder in the same directory as replicate.ipynb.

### How to Run
1. Clone this repository
2. Download the data from the link above and place the data/ folder in the cloned repository folder
3. Open terminal and navigate to the repository folder
4. Type: jupyter notebook
5. Open replicate.ipynb
6. Click Kernel → Restart and Run All

### What is Replicated
This replication reproduces Table 2 from the paper (shallow classifier rows):
- Logistic (unweighted)
- Logistic (weighted)
- SVM (unweighted)
- SVM (weighted)

Note: ULMFiT and RoBERTa rows were not replicated as they require GPU hardware and the authors' 3.5GB pre-trained model weights.
