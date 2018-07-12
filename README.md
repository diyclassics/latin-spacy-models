# spaCy Model for Latin
version 0.0.1

Preliminary spaCy model for Latin based on word frequencies from the works of Cicero in the Classical Language Toolkit Latin Library corpus: https://github.com/cltk/latin_text_latin_library.

## Installation with pip
- pip install dist/la_model-0.0.1.tar.gz

See https://spacy.io/usage/training for more information on working with this model.

## Usage

```
import spacy
nlp = spacy.load('la_model')
docs = nlp(u'arma virumque cano')
for token in docs:
    print(token.text)

>>> arma
>>> virumque
>>> cano
```

## Development
This is part of my larger work on adding Latin as a language to spaCy. Please see: https://github.com/diyclassics/spaCy/tree/latin/spacy/lang/la.
