# PDF2Keywords
This Jupyter Notebook shows the conversion of a PDF to 5 Keywords per page by NLP Rake algorithm.
 
 # Install
 
 Tested with Anaconda on Windows -> see environment.yml. 
 
 In Anaconda-Terminal use:
 
 ```
 conda env create -f environment.yml
 conda activate RAKE_TextSummarizer
 ```
  
 What also will work w/o Anaconda: 
 
 Install Rake and PyPDF2.
 
 ```
 pip3 install nlp_rake
 pip3 install PyPDF2
 ```
 
 #Usage
 A file dialogs opens for PDF selection and the 5 top rated keywords per page from Rake are printed to console. 
