# goethe-reference-list

## Context
The film department of the Goethe University Frankfurt makes a [Reference List](https://www.uni-frankfurt.de/83387917/ReferenzlisteFilm_Nov2019.pdf)
available to its students which contains 433 films. I thought it might be interesting to analyze the list to discover, for instance, what countries are the most represented
and what percentage of films were directed by women.

## Data
Before I could do any of this analysis I first had to clean up the list of films, which was quite messy in the original PDF (ReferenzlisteFilm_Nov2019.pdf). 
Though each line is supposed to contain the film title, director, country, and year (separated by commas), there were many inconsistensies which had to be fixed. 
To clean up this data, I used the software OpenRefine, which I also used to add additional information about each film from Wikidata and OMDb. 
It is the result of this process that is present here as "Reconciled_RefList.tsv".
