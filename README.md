# Wikipedia
This is a simple assignment to learn Spark transformations and actions in real life scenarios.

The assignment uses full-text data from Wikipedia to produce a rudimentary metric of how popular a programming language is, 
in an effort to see if these Wikipedia-based rankings bear any relation to the popular Red Monk rankings. The data can be downloaded 
from http://alaska.epfl.ch/~dockermoocs/bigdata/wikipedia.dat .
The assignment uses a simple metric for determining the popularity of a programming language: the number of Wikipedia articles 
that mention the language at least once.

It is done in 3 ways:
1) Computing rank based on occurrencesOfLang in Wikipedia articles (compute directly)
2) Computing rank using inverted index
3) Computing rank using reduceByKey (compute directly)
The assignment also compares the time taken in each approach.
