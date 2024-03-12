# MedSpaCy Dutch

This repository contains the resources for extracting concepts and their context using MedSpaCy.

For more information on MedSpaCy and installation instructions, please visit the [MedSpaCy Github page](https://github.com/medspacy/medspacy).

## Concept Extraction
To extract concepts from Dutch biomedical or clinical text, a reference dataset is required containing all the concepts and their terms that need to be extracted. Please note that we cannot directly provide the reference dataset as it includes the UMLS vocabularies and the Dutch SNOMED CT vocabulary. 

Before downloading the UMLS, you will need to obtain a [license](https://uts.nlm.nih.gov/license.html) from the National Library of Medicine. Similarly, for access to the Dutch SNOMED CT vocabulary, you will need to obtain a [license](https://nictiz.nl/wat-we-doen/activiteiten/terminologie/snomed/licenties-en-downloads/) from NICTIZ and follow their instructions.

The "QuickUMLS_resources" folder contains a jupyter notebook, that takes the UMLS and Dutch SNOMED CT files as input to build a concept reference database.

## Context Detection
The Dutch rules for detecting context information about a concept are listed in the "Concept_resources" folder.

## Setting up the MedSpaCy Dutch Pipeline
The pipeline can be set up in a similar manner to the English pipeline, but with links to the language-specific resources. You can find an example notebook [here](https://github.com/mi-erasmusmc/medspacy_dutch/blob/main/Example_medspacy_dutch.ipynb).


## Studies using the Dutch MetSpaCy pipeline:
- [The added value of text from Dutch general practitioner notes in predictive modeling - JAMIA 2023](https://academic.oup.com/jamia/article/30/12/1973/7243430)
