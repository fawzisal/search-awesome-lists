Search Awesome
==============

A small bash script to search the full texts of awesome lists.


Requirements
------------
ripgrep, fd


Features
---------
- to perform a full-text search for 'query', enter:
  > awe query
- to only search the titles of awesome-lists, prepend with '/':
  > awe /query
- to open the first result result of a full-text search, use '//': 
  > awe //query
- to open all results of a full-text search, use '/@': 
  > awe /@query
- to open awesome lists related to the command line, use '/\_': 
  > awe /\_query
- to perform a whole word search, prepend '\_':
  > awe \_query
- to only return the number of results in each file: 
  > awe \\query

