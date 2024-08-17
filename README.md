# bert-model
from hugging face analyzing a pretrained bert model.BERT is a very effective tool for text categorisation because of its capacity to comprehend the relationships and context inside text. Through task-specific tweaking of BERT, practitioners may take use of cutting-edge NLP capabilities to get excellent classification accuracy for text data.
for this we installs transformer, pytorch and datasets 
i choosing the text classification.The process of giving a text a name or category is known as text categorisation. Sentiment analysis, spam detection, and topic classification are typical instances. By including a straightforward classifier layer into its design, BERT may be optimised for text classification applications.

BERT is fine-tuned by training it on a labelled dataset, which teaches the model to identify and link particular textual patterns to matching labels. Compared to training a model from start, fine-tuning BERT on a new task takes comparatively less data and training time since it has a good understanding of language from its pre-training phase.
here is the step by process
first load the data and tokenize the dataset into tokens called as inputs 
define the metrics like accuracy to evaluate the model
setup training arguments and training by intialising the trainer
train and evaluate its perfomance by train() and evaluate() methods 
making prediction to find the accuracy
