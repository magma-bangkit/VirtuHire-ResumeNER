# VirtuHire-ResumeNER

[![GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-lightgrey.svg)](https://github.com/magma-bangkit/VirtuHire-ResumeNER)

Named Entity Recognition (NER) using SpaCy machine learning is an advanced natural language processing technique that identifies and classifies named entities in text. SpaCy, a popular open-source library, provides a comprehensive framework for developing NER models with machine learning algorithms. By leveraging the power of deep learning and statistical models, SpaCy enables accurate and efficient extraction of named entities, such as person names, locations, organizations, dates, and more, from unstructured text data.

The usage of this repo is to get skills entity texts from images. So in our application, VirtuHire, we need an text extraction from CV upload, and we use this OCR Model to extract text from CV images. The result is not quite good, because of the resource limitation. In normal, we need 36 hours to run the training, so for this capstone we simplified the model and resulting the accuracy is decrease.

## Table of Contents

- [Getting Started](#getting-started)
- [Installation](#installation)
- [Result](#result)
- [Acknowledgements](#acknowledgements)

## Getting Started
Here is what you need to be able to run this repo

- Spacy
- TQDM
- Locale
- JSON

## Installation
How to install :
1. Download the repo
```
$ git clone https://github.com/magma-bangkit/VirtuHire-ResumeNER.git
```
2. Upload the notebook to jupyter notebook cloud or google colab. Or you can use your local jupyter notebook.
3. Open the notebook using jupyter notebook or google colab
4. Set the dataset folder
5. Run each cells (make sure already install the packages and libraries)

## Result
![resume ner](https://github.com/magma-bangkit/VirtuHire-ResumeNER/assets/70988407/9b286841-bfe1-4a04-bdf9-237e2f9dd78d)


## Acknowledgements

We would like to express our gratitude to the following individuals for their valuable contributions and support in the development of this project:

- [Akhmad Thoriq](https://github.com/itstor)

Thank you all for your dedication, expertise, and continuous support!
