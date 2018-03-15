# Overview
This project downloads results of the [2018 Queen City Classic Chess Tournament](https://ccpf.proscan.com/programs/queen-city-classic-chess-tournament/) then loads the results in dataframes and performs some rudimentary analysis and visualization.  The challenging part was extracting the data: the tournament posted the results in multiple PDF files.  I first tried to parse these files with [PyPDF2](https://pythonhosted.org/PyPDF2/), but the package was unsuccessful at parsing the files, so I then used the command line tools in [Xpdf tools](https://www.xpdfreader.com/index.html).  This worked, but I had to pull out a few other tricks to eventually get the data into a list and CSVs that I could then import into dataframes where I could do my analysis.

The code is implemented as a [Jupyter Notebook](http://jupyter.org/) and uses [pandas](https://pandas.pydata.org/) for the data manipulation part.

