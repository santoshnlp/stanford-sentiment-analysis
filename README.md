# stanford-sentiment-analysis

This repoitory has 2 files. 
1. stanford-sentiment-analysis.ipyb
   This is a jupyter notebook.  It contains the Data pre-processing. ( Scroll down to the very bottom. Entire text got printed )
   
   df_sentences  contains :  sentence_index  and sentence,  sentente_index will be useful for train/test/val split as provided in datasetsplit.txt.
   I have not used this split.
   
2. _Sentiment_Analysis_using.LSTMRNN
    This is the google colab file as used in the course with modifications. 
    
    


Text Augmentation used:

random deletion and swapping were to augment the stanford dataset.

back translation was also used. The only issue here is some translations were noisy. The API works for first few sentences.
It seems there is usage limit of this API.
