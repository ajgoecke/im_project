# Conception of a Discourse Glossary 
IM project for the MSc Cognitive Systems at the Universität Potsdam, summer semester 2022, taught by Prof. Dr. Manfred Stede. 

Developed by Anna-Janina Goecke (goecke@uni-potsdam.de).

**Project Description**: The projects seeks to create and enrich a discourse glossary of German climate change compounds. 

### Notebook Files

The folder `notebooks` contains R notebook files for:
- `im_project.Rmd`: Code and documentation for project report
- `im_add_compounds.Rmd`: Add new glossary entries and save to JSON file
- `im_add_corpus.Rmd`: Add new data to corpus

Furthermore, you can find the project report and the corpus files within the repository.  

### Corpus Files
The folder `corpus_data`contains all corpus files and rare text files from the websites which we used to generate the corpora. 

- contains the corpora (new and old version)
- `text_files.zip` (all text files which are contained in the corpora)

### Glossary Files
The folder `files` contains a table and list of the compound words which we use in the glossary.
-`compounds.csv`: Data frame with the compound words and its associated word forms
- `wordlist.txt`: List of compound words

### How to run:
We recommend running the notebooks using RStudio. The following libraries are required: 
`quanteda`, `quanteda.textplots`, `quanteda.textstats`, `readtext`, `tidyverse`, `spacyr`, `stringr`, `textcat`, `data.table`, `jsonlite`, `dplyr`, `purrr`
