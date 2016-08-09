# PDFsuite
Python scripts for MacOS (OS X) that create, manipulate, and query PDF files

These scripts provide 'front ends' to MacOS's Core Graphics APIs, thereby allowing the automation of a variety of tasks, such as creating bookets, applying Quartz Filters and querying page count of input PDFs.

1. Booklet Imposition
This script is set to work as a PDF Service. However, it could easily be adjusted to work as an Automator workflow. It takes the input PDF file and lays out the pages on a larger sheet, in booklet spread page order.

2. Apply Quartz Filter
This replaces Apple's own quartzfilter command, which was removed from OS X (in Lion?). It has three inputs: input file, quartz filter, and output file. If no output file is set, it will overwrite the input file.

3. Count pages in PDF
This again uses Core Graphics objects and methods to count the number of pages in one or more PDF files passed to it. It provides a cumulative count for multiple files.

Other scripts are planned: such as one for the rotation of pages within a PDF.

Ben Byram-Wigfield
