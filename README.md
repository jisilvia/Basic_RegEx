# Basic Regular Expressions

A regular expression is a sequence of characters that define a search pattern. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation.

# Project Description

This project uses basic regular expressions to find and extract information from datasets.

The first part of the project extracts information Federal Aviation Administration (FAA) airport closures, specifically the closed towers' IDs and their corresponding state.

The second part of the project extracts information about a given user's reputation on [Stack Overflow](https://stackoverflow.com/). The code finds and extracts information about the date, change in upvotes, and total upvotes.

## Steps

 1. Examining the data
 2. Extracting information
 3. Presenting the data

## Requirements

**Python.** Python is an interpreted, high-level and general-purpose programming language.

**Integrated Development Environment (IDE).** Any IDE that can be used to view, edit, and run Python code, such as:
- [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true)
- [Jupyter Notebook](https://jupyter.org/).

### Packages 
Install the following packages in Python prior to running the code.
```python
import pandas as pd
import re
```
## Launch
Download and import the text files *faa.txt* and *reputation.txt* and import them in your IDE.

## Authors

[Silvia Ji](https://www.linkedin.com/in/silviaji/) - [GitHub](github.com/jisilvia)

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.

## Acknowledgements
The project template and datasets were provided by Nohel Zaman at Loyola Marymount University.
