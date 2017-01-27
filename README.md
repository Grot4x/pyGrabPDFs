# pyGrabPDFs
given a url grabs all pdf's in a html page and saves them to a local dir


Forked from https://gist.github.com/elssar/5160757

Changes:
* work with python3
* fixed some errors
* add md5 hash to file name

Download all the pdfs linked on a given webpage

Usage -

    python3 grab_pdfs.py url <path/to/directory>
        url is required
        path is optional. Path needs to be absolute
        will save in the current directory if no path is given
        will save in the current directory if given path does not exist

Requires - 
    
    requests >= 1.0.4
    beautifulsoup >= 4.0.0

Download and install using

    pip3 install requests
    pip3 install beautifulsoup4
