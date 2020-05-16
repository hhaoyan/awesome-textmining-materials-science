# Awesome text mining ⛏️ for materials science
A collection of papers on text mining for materials science. **Note: this is a work in progress, I will constantly update this page.**

If you find an interesting paper and would like to add it here, please create a PR request.

## Tools and codes

### Plain text

- [spaCy](https://spacy.io): Fast NLP toolkit with pre-built deep learning models for tokenization, NER, POS, dependency parsing, word2vec, etc.
- [textacy](https://github.com/chartbeat-labs/textacy): Pre-/post- processing of text used in conjunction with spaCy, such as text normalization, garbage text cleaning, extraction of ngrams, entities, etc.
- [ChemDataExtractor](http://chemdataextractor.org/): A full-fledged toolkit for sentence segmentation, tokenization, chemical NER, and extracting chemical information.

### PDF files
- [PDFMiner](https://github.com/pdfminer/pdfminer.six): A pure Python implementation of PDF parser.
- [textract](https://textract.readthedocs.io/en/stable/): A bundle of markup-to-plain-text converters including PDF files.

### OCR tools

- [tesseract](https://github.com/tesseract-ocr/tesseract): An open source C++ OCR tool based on LSTM that supports many languages.
- [Google Cloud OCR](https://cloud.google.com/functions/docs/tutorials/ocr): Google Cloud OCR is highly accurate for books but may suffer from bad recognition accuracy for chemical/materials science symbols and equations.

## Datasets/databases

- [Machine-learned and codified synthesis parameters of oxide materials by Kim et al](https://doi.org/10.1038/sdata.2017.127): Dataset on synthesis of 30 oxide systems extracted from 76K articles.
- [Text-mined dataset of inorganic materials synthesis recipes by Kononova et al](https://doi.org/10.1038/s41597-019-0224-1): 20K balanced inorganic synthesis reactions and metadata including experimental conditions extracted from 53K articles.
- [Annotating and Extracting Synthesis Process of All-Solid-State Batteries from Scientific Literature by Kuniyoshi et al](https://arxiv.org/abs/2002.07339): NER and dependencies annotated/trained on 243 all-solid-state battery articles.

## NLP pipelines

### Named Entity Recognition

- [Named Entity Recognition and Normalization Applied to Large-Scale Information Extraction from the Materials Science Literature by Weston et al](https://doi.org/10.1021/acs.jcim.9b00470): Extract from summaries inorganic material mentions, sample descriptors, phase labels, material properties, applications, and synthesis/characterization methods.
- [Automated Extraction of Chemical Synthesis Actions from Experimental Procedures by Vaucher et al](https://doi.org/10.26434/chemrxiv.11448177.v2): Use rule-based/ML(Transformer) model to extract synthesis actions from experimental procedures.

### Text classification/categorization

- [Semi-supervised machine-learning classification of materials synthesis procedures by Huo et al](https://doi.org/10.1038/s41524-019-0204-1): Identify synthesis paragraphs using LDA and random forest.
