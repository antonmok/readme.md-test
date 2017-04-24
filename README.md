# Project Name

pdfParser

## Installation

1) Download and build [PDFWriter project](https://github.com/galkahana/PDF-Writer).
Build instructions [here](https://github.com/galkahana/PDF-Writer/wiki/Building-and-running-samples).

2) Download and extract [TCLAP project](http://sourceforge.net/project/showfiles.php?group_id=76645)

3) Download pdfParser.

Project directory structure should look like this:

SomeFolder
	|--pdfParser
	|
	|--PDFWriter
	|
	|--tclap-1.2.1

4) Go to pdfParser directory and run this commands:
    cmake -G "Unix Makefiles"
    make

pdfParser executable will be generated in 'build' folder.

## Usage

To extract all text
    ./pdfParser -c extract -p path/to/file.pdf -o out/put/dir

To insert links
    ./pdfParser -c insert -p path/to/file.pdf -o out/put/dir

To show detailed info about command line arguments
    ./pdfParser --help

