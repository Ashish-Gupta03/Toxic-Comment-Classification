# Toxic-Comment-Classification
Challenge is to build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate. Data comprises of comments from Wikipedia’s talk page edits.

Approach:-
Markup : * Preprocess data
              * Remove null column values by any textual data as I did by using "fillna" in my code.                  
         * Select number of features, max length and embedding to use
              * num_features = 100000, maxlen = 150, embedding used = Glove
         * Use Tokenizer to tokenize text, convert them to sequences and pad the comments so that each one becomes = maxlen of 150 words.

For more details click the link https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge
