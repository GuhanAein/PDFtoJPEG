# PDFtoJPEG
PDF to JPEG Converter
This Python script allows users to convert each page of a PDF file to a JPEG image. It utilizes the fitz module from the PyMuPDF library to handle the PDF file and the PIL (Python Imaging Library) library to save the PDF pages as JPEG images.

#Features:
-Select a PDF file using the file manager dialog.
-Iterate over each page in the PDF and convert it to a JPEG image.
-Prompt the user to specify a file name and location for each image.
-Save the converted JPEG images with the chosen file names and locations.

#Prerequisites:
-PyMuPDF library: Install using pip install PyMuPDF.
-Pillow library: Install using pip install Pillow.

#Usage:
-Run the script using Python.
-The file manager dialog will open for you to select a PDF file.
-Each page of the PDF will be converted to a JPEG image.
-For each converted image, the script will prompt you to provide a file name and location.
-After selecting a file name and location for each image, the JPEG files will be saved accordingly.

#Note:
Make sure to have both PyMuPDF and Pillow installed before running the script.
The converted images will be saved with the chosen file names and locations specified by the user.
