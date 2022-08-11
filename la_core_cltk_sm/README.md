<!-- SPACY PROJECT: AUTO-GENERATED DOCS START (do not remove) -->

# 🪐 spaCy Project: CLTK Latin Pipeline for spaCy

Latin pipeline with POS tagger, morphologizer, lemmatizer, and dependency parser trained on all available Latin UD treebanks, i.e. Perseus, PROIEL, ITTB, UDante, and LLCT (see below). This project is based on the spaCy [`tagger_parser_ud` project template](https://spacy.io/usage/projects) with the following modifications: 1. uses Latin language-specific spaCy module, available now at https://github.com/diyclassics/spaCy/tree/latin-dev; 2. combines multiple treebanks for train, dev, and test sets; 3. uses a custom Latin `senter` sentence segmenter; and 4. normalizes u/v and i/j in lemmas as a pretraining step (beta!). Written by diyclassics in August 2022.

### 📒 Notes

Install the Latin language-specific spaCy module with:

`python -m pip install git+https://github.com/diyclassics/spaCy.git@latin-dev#egg=spacy`

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

<!-- SPACY PROJECT: AUTO-GENERATED DOCS END (do not remove) -->
