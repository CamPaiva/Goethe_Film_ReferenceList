# Goethe_Film_ReferenceList

## Context
The film department of the Goethe University Frankfurt makes a [Reference List](https://www.uni-frankfurt.de/83387917/ReferenzlisteFilm_Nov2019.pdf)
available to its students which contains 433 films. I thought it might be interesting to analyze the list to discover, for instance, what countries are the most represented
and what percentage of films were directed by women.

## Data
Before I could do any of this analysis I first had to clean up the list of films, which was quite messy in the original PDF. 
Though each line is supposed to contain the film title, director, country, and year (separated by commas), there were many inconsistensies which had to be fixed. 
Missing data which was not surrounded by commas created problems when shifting each characteristic into a column. 
Inconsistent writing of countries and director's names were also an issue. To clean up this data, I used the software OpenRefine. 
With OpenRefine, I could also reconcile each film with their respective pages on Wikidata and OMDb, and with that I could add new columns 
that were not present in the original data. It is the result of this process that is present here as "Reconciled_RefList.tsv".
