<!-- SPACY PROJECT: AUTO-GENERATED DOCS START (do not remove) -->

# 🪐 spaCy Project: CLTK Latin Pipeline for spaCy

Latin pipeline with POS tagger, morphologizer, lemmatizer, and dependency parser trained on all available Latin UD treebanks, i.e. Perseus, PROIEL, ITTB, UDante, and LLCT (see below). This project is based on the spaCy [`tagger_parser_ud` project template](https://spacy.io/usage/projects) with the following modifications: 1. uses Latin language-specific spaCy module, available now at https://github.com/diyclassics/spaCy/tree/latin-dev; 2. combines multiple treebanks for train, dev, and test sets; 3. uses a custom Latin `senter` sentence segmenter; and 4. normalizes u/v and i/j in lemmas as a pretraining step (beta!). Written by diyclassics in August 2022.

### 📒 Notes

Install the Latin language-specific spaCy module with:

`python -m pip install git+https://github.com/diyclassics/spaCy.git@latin-dev#egg=spacy`

Install this model by downloading the tar.gz file to your virtual environment, site packages, etc. and running:

`python -m pip install https://github.com/diyclassics/latin-spacy-models/blob/main/la_core_cltk_sm/la_core_cltk_sm-0.1.0.tar.gz\?raw\=true`

### 🗂 Assets

The following assets are defined by the project. They can
be fetched by running [`spacy project assets`](https://spacy.io/api/cli#project-assets)
in the project directory.

| File | Source | Link |
| --- | --- | --- |
| `assets/UD_Latin-PROIEL` | Git | [link](https://github.com/UniversalDependencies/UD_Latin-PROIEL) |
| `assets/UD_Latin-LLCT` | Git | [link](https://github.com/UniversalDependencies/UD_Latin-LLCT) |
| `assets/UD_Latin-Perseus` | Git | [link](https://github.com/UniversalDependencies/UD_Latin-Perseus) |
| `assets/UD_Latin-ITTB` | Git | [link](https://github.com/UniversalDependencies/UD_Latin-ITTB) |
| `assets/UD_Latin-UDante` | Git | [link](https://github.com/UniversalDependencies/UD_Latin-UDante) |

### 🎯 Accuracy

| Type | Score |
| --- | --- |
| `SENTS_F` | 69.32 |
| `SENTS_P` | 75.15 |
| `SENTS_R` | 64.33 |
| `TAG_ACC` | 82.30 |
| `POS_ACC` | 95.97 |
| `MORPH_ACC` | 84.60 |
| `LEMMA_ACC` | 92.25 |
| `DEP_UAS` | 77.78 |
| `DEP_LAS` | 71.95 |
| `TOK2VEC_LOSS` | 10806146.15 |
| `TAGGER_LOSS` | 2737170.19 |
| `MORPHOLOGIZER_LOSS` | 2782373.86 |
| `TRAINABLE_LEMMATIZER_LOSS` | 1012842.41 |
| `PARSER_LOSS` | 7525410.66 |

<!-- SPACY PROJECT: AUTO-GENERATED DOCS END (do not remove) -->
