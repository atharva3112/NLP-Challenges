# NLP-Challenges
**Stage 3 (Data Scientist)**
# Project Name
Tagging System of Questions using Transfer Learning
## Overview
In this project, we first explore and understand the data which we are using. 
During the Pre-processing of the data we need to convert the raw data into a format that our model can use during training and inference. We will accomplish this by parsing the HTML, then creating two NumPy arrays for each topic: data and labels. The data array will be comprised of the words from the title and cleansed content, and the labels will be the words from the tags. Array elements will be words themselves.
Embedding of words implementation is based on the Skip-gram model. 

## Reference 
[Skip-gram Model](https://www.tensorflow.org/tutorials/representation/word2vec#the_skip-gram_model)

[Distributed Representations of Words and Phrases
and their Compositionality](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)


