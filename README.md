## Analyzing_Wikipedia_Pages

# Goals
In this guided project, we'll work with data scraped from Wikipedia. Volunteer content contributors and editors maintain Wikipedia by continuously improving content.

We'll implement a simplified version of the grep command-line utility to search for data in 54 megabytes worth of articles. If you're not familiar with the grep command, the grep utility essentially allows searching for textual data in all files from a given directory.

- Search for all occurrences of a string in all of the files.
- Provide a case-insensitive option to the search.
- Refine the result by providing the specific locations of the files.

# Data
Articles were saved using the last component of their URLs. For example, a page on Wikipedia has the URL structure https://en.wikipedia.org/wiki/Yarkant_County. If we were saving the article with the previous URL, we'd save it to the file Yarkant_County.html. All the data files are in the wiki folder. Note that the files are raw HTML — We don't need to understand HTML for this guided project. We're going to treat those files like plain-text and we won't rely on any of the specific structure of those files.


# Learn

Locating data from text files is a very common and time-consuming operation when many files are involved. By using MapReduce, we can significantly reduce the time required to locate that data.

In this guided project we've implemented a MapReduce grep algorithm that locates all matches of a given string within all files in a given folder.

![alt text](https://github.com/Kevin858/Analyzing_Wikipedia_Pages/blob/master/pictures/result_dataframe.png?raw=true)
