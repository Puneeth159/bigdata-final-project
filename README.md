# bigdata-final-project
This project is about commands of process text data with Spark and Python

## Author
- [Puneeth Annam](https://github.com/Puneeth159)

## Text Data Resource
-[The Project Gutenberg EBook of The Kopje Garrison, by George Manville Fenn](https://www.gutenberg.org/cache/epub/27897/pg27897.txt)

## Databricks link

-[Bigdata Final Project link](https://community.cloud.databricks.com/?o=2193169200472804#notebook/1949933761650238/command/3798170560335304)

## Tools and Languages:
- Databricks Cloud Environment.
- Spark Processing Engine.
- PySpark.
- Python Programming Language.

### Processing the data

'''

import urllib.request
stringInURL = "https://www.gutenberg.org/cache/epub/27897/pg27897.txt"
urllib.request.urlretrieve(stringInURL, "/tmp/puneeth_bigdatafinalproject.txt")
'''
