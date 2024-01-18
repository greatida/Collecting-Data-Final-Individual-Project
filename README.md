# Yellow Submarine
This repository contains two csv files, one csv file contains corpus data and annotations of 15 songs' lyrics from the **Yellow Submarine** album and the other contains metadata of the lyrics, and a Jupiter Notebook recording the procedures of text preprocessing and annotating. The target audience could be the fans of The Beatles or the researchers who is interested in corpus analysis on lyrics.
## Data Collection Process
The unstructured data - lyrics are found online and simply copied into text files.
## Annotations and Tools
Pandas and spaCy are used as tools to do tokenization, lemmatization, part of speech and named entity recognition.
## Format of Files in Corpus
Files in corpus are in txt format.
## Description of Columns in csv
Description of Columns in csv:
|   **Header**   |             **Description**             | **Data Type** |
|:--------------:|:---------------------------------------:|:-------------:|
|     Song ID    |         Song ID in this csv file        |     number    |
|    Filename    |                Song Name                |      text     |
|      Genre     |                Song Genre               |      text     |
|     Writer     | Names of the person who writes the song |      text     |
|  Song Duration |         How long the song lasts         |     number    |
|      Text      |               Song lyrics               |      text     |
|     Tokens     |  Preprocessed lyrics that are tokenized |     string    |
|     Lemmas     |                Root words               |     string    |
|       POS      |             Parts of speech             |     string    |
|  Proper_Nouns  |        Words for specific things        |     string    |
| Named_Entities |          Types of named entites         |     string    |
|    NE_Words    |           named entities words          |     string    |

