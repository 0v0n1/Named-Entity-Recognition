# Named-Entity-Recognition

This is a lightweight, easy-to-use and a simple interactive command-line tool for extracting named entities from user-input sentences using spaCy's pre-trained NER model (en_core_web_md).


## Features

- Uses spaCy's en_core_web_md for balanced performance and accuracy.
- Extracts entities (PERSON, ORG, GPE, DATE, etc.) from user input.
- Saves extracted results to a CSV file using pandas.


## Dependencies

- spaCy
- Pandas
- en_core_web_md


## Example
Input: 
Sylvia Plath was an American Poet
Output:
Entities found:
-Sylvia Plath (PERSON)
-American (NORP)


## Model Info

Model: en_core_web_md - spaCy model for English Language Processing
Type: Pretrained spaCy model with support for NER, POS tagging, and word vectors
Trade-off: Better accuracy than 'en_core_web_sm', faster than 'en_core_web_lg'
