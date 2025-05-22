# Named-Entity-Recognition

This is a lightweight and easy-to-use Named Entity Recognition (NER) project using spaCy and Pandas that extracts entities like names, organizations, locations, and dates from input text using spaCy's pre-trained model.

## Features

- Uses spaCy's en_core_web_md for balanced performance and accuracy.
- Extracts entities (PERSON, ORG, GPE, DATE, etc.) from user input.
- Saves extracted results to a CSV file using pandas.
- Easily extendable with rule-based matchers or Hugging Face models.

## Example
Input: 
Sylvia Plath was an American Poet
Output:
Entities found:
-Sylvia Plath (PERSON)
-American (NORP)
