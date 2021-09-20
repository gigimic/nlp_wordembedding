Word embedding layers for deep learning with Keras
--------------------------------------------------

Word embedding is represented as dense vectors as opposed to the sparse matrices in BOW.
These vectors are created using the context of the word appearing in a document.

Popular methods are:

word2vec & 
GloVe (Global vectors for word representation)

In data_text_keras the word embeddings were created using the given vocabulary.
steps:
1. Initially one hot encoding was done for every word.
2. Document padding was done so that they have equal length
3. Keras sequential model was created
4. Added embedding layer
5. sigmoid activation was done
6. compiled the model with 'adam' optimiser
7. Model was fit  and then evaluated to see the accuracy

GloVe is a pre-trained GloVe embedding. 
data_glove shows how it can used for our modelling purpose

In the word_embed_keras notebook, the word embedding is done and the embedded matrix of each word is shown to understand the concept.

Ref: 
1. https://machinelearningmastery.com/use-word-embedding-layers-deep-learning-keras/
2. https://www.youtube.com/watch?v=TsXR7_vtusQ


