# GitLas :Git Log Statistics 
The minimalist Git Log Statistics library

## Meta Data of Git
Often times we have a ton of Meta Data ,but we really don't have much of tools to make useful
analysis from it.
Git Logs are one of the best sources from which we can actually understand and analyse some of the trends in our Project workings.

The commits and merges can be tracked easily with git , but to make useful charts and analysis we need to convert these data into a useful data type.

GitLas is a simple Library that filters out gitlogs with regular expression pattern matching and applies useful analytic filters to get more out of the data. JSON data type is highly preferred and widely used, hence the library convert the git log into a simple JSON format which can be exported as well. 

These statistics can be useful or not really useful at all depending on the size of your project and the collaborators associated with it.
## Getting GitLog as text
To get the git log in a text format
   
```
$ git log > gitlog.txt
```

or copy it to the clipboard and later paste it in a new file.  

```
$ git log > clip
```
## Requirements
### Python 3  
## Installing gitlas 
using pip

```
$ pip install gitlas
``` 
or pip3 in some systems  

```
$ pip3 install gitlas
```
## Bugs and Inconsistencies
As a developer, i understand the needs of another developer; however there are always certain situations for which you might have to fine tune the source code to get the library working with your scenario.
If you find bugs report them  [here](https://github.com/Abhi-1U/GitLas/issues) and i will fix them ASAP if possible.

## Contributions 
If you want to contribute by adding or extending the functionality of GitLas then you can issue a pull request.

Do note that :   
1. code must be well commented.  
2. the structure of code should remain consistent.  
3. docstrings are a must with every change.  