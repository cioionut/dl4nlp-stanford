# Deep Learning for NLP - Stanford
---
## Word2Vec - Skip-Gram - Negative Sampling
### Results Plot
![Word2Vec Plot](https://github.com/cioionut/dl4nlp-stanford/blob/master/Word2Vec_pset1/q3_word_vectors.png "Word2Vec Plot")

## Install Environment
```bash
cd Word2Vec_pset1
sudo pip install virtualenv      # This may already be installed
virtualenv .env                  # Create a virtual environment
source .env/bin/activate         # Activate the virtual environment
pip install -r requirements.txt  # Install dependencies
# Work on the assignment for a while ...
deactivate                       # Exit the virtual environment
```
## Download the Stanford Sentiment Treebank Dataset
```bash
cd cs224d/datasets
./get_datasets.sh
```
