This is my wordcount program written in pyspark.
Here by, I used 2 module
  1. One module is to cleanup the working environment to load new set of files and inserting into delta tables.
  2. Another module is to perform actual transformation (reading the text file from working directory and calculationg the word count and inserting into delta tables). 
