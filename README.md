# twitter data

How to deal with situations where you need to process a very large file

Processing a very large file can sometimes crash the system as entire file may not fit in memory, causing crashes

Sometimes, the data we have to process reaches a size that is too much for a computer's memory to handle.
This is a common problem faced by data scientists. A solution to this is to process an entire data source chunk by chunk, instead of a single go all at once.

You will process a large csv file of Twitter data in the same way that you processed 'tweets.csv'
