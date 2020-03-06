# LegalFileNoteGenerator
A simple and fast interface to generate file notes that are built from a word template, without needing to go into word. 


Very early, barely working model of an app that I am using to teach myself. 

The idea is that it provides a very quick way to generate file notes, without having wait for word to open, write in the names of the clients etc. 

If you want to run it yourself, you will need to change the references to specific word document file names and locations. 

Currently it is set up to build on an existing word document. It takes that word document, which is effectively a template but is not a .dotx file. 

It opens it, resaves it with the current date and time as the file name, and appends the entered text into the file. 

I am just learning so the code is obviously ugly. 

You will need to install the python-docx module (pip install --user python-docx==0.8.10 (install python-docx, not docx))