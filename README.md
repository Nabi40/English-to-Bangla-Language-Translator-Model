#﻿# English-to-Bangla-Language-Translator-Model  

I used Helsinki-NLP/opus-mt-en-hi API from hugging face to train kaggle English to Bangla dataset with 1 epoch. Helsinki-NLP/opus-mt-en-hi is a pre-trained model for English-to-Hindi translation. It's only for testing if it's training well or not. It works but the learning rate is very low for the epoch size. For good results, we need 500-1000 epochs.  

---

There are codes for downloading the file locally. it will contain:  
- saved_model.pb → The main model architecture and metadata.  
- variables/ → Contains the model weights.  
- assets/ → Extra files (empty).  
- keras_metadata.pb → Metadata for Keras models.  
- fingerprint.pb → Stores model integrity information.  
