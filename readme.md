Empirical logic to find summary of news articles.


Document Summary

Split the sentence and use the first top 3 sentence with maximum no of words among the rest.


 - preprocessor.py
  Class ProcessDoc
  functions
   - special character
   - token
   - stopword removal
  
 - summarizer.py
 Class SummarizeDoc
 functions
  - splitter
  - findSenExtractor
  - findNumWords
  - findTop3Sentences
  - sentenceCombiner