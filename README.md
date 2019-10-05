# article_summariser_model
includes files for an article summariser
it requires gensim version 3.3.0, wget version 3.2, nltk version 3.2.5, Python version 3 and Tensorflow version 1.8.0
it  implements seq2seq using tensorflow text summarization. it uses decoder-encoder model uses attention mechanism 
it uses glove pre trained vectors for word embedding from stanford 
 
 -for Preparation of the  dataset, Dataset is available at [harvardnlp/sent-summary](https://github.com/harvardnlp/sent-summary). 
  Locate the summary.tar.gz file in project root directory. Then, download it using glove and preparing the data.  
  using the commandline 'python prep_data.py --glove'

- to train the data use the command line command 'python train.py' and  then 'python train.py' --glove to use Glove pre-trained vectors as initial embedding

- to test the model,use 'python test.py'.
