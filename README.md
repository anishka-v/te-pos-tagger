# POS Tagger for Transliterated Telugu 

The goal of this project is to develop a POS tagger for transliterated Telugu using the [Universal Dependencies Telugu MTG Dataset](https://github.com/UniversalDependencies/UD_Telugu-MTG). 

**crf.py**: 
- Iterate over the file to retrieve the transliterated word and corresponding POS tag
- Extract important features for each word 
- Train a conditional random fields model on an English dataset

**crf-te.py**: 
- Iterate over the file to retrieve the transliterated word and corresponding POS tag
- Extract important features for each word 
- Train a conditional random fields model on a Telugu dataset
  
**roberta-te-transliterate.py**:
- Iterating and collecting the transliterated tokens from the dataset
- Training the xlm-roberta-base model 

