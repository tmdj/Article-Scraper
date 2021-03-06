# Article-Scraper
The program can be used to scrape the content from an article from web by an input of a set of URLs in a text file. This project uses newspaper3k and python-docx libraries. The output of this program will give a neatly modified Word Document in '.docx' format. This makes our life a lot easier by saving a lot of time to obtain data from an article.

### THE ARTICLE SCRAPER V2

This program allows the user to scrape the content from an article in the internet using its URL alone and convert the content into <br/> a MS-Word Document. This program uses the ***newspaper3k*** and ***Python-docx*** library. Be sure to load the modules before using this program or run the ***pre-requisites*** code. This prorgam gives the 
following from an article in the Word Document, <br/>
1. The Title and the URL                                   
2. Content                                                 
3. Images from the Article in a neat table format                              
4. Summary of the Article                                
5. Keywords from the Article 

#### INSTRUCTIONS                                            

1. Collect the URLs of the articles you want to obtain and list them one URL per line in a Text file *(*.txt)*.
2. Now, initiate the program. Provide the location or the name of the text file that contains the URLs.                                      
3. Select a set of links to process or select all depending upon your need. Larger number of URLs *(i.e. >30)* <br/> might take longer. So, it is ideal to split and process.     
4. Provide a valid name for your Word Document with the *(*.docx)* extension.                                      
5. Once the process is completed, the title of all the articles processed will be listed, marking the end of the process.                                            

### THE ARTICLE SCRAPER URL

This program allows the user to scrape the content from an article from the given URL and the data will be saved in a word document in a well organised manner. Unlike the Article Scraper program, this program allows the user to process single URLs than a batch. 

#### INSTRUCTIONS

1. Run the program and enter the URL of the Article, you want to process.
2. Provide a valid name for your Word Document with the *(*.docx)* extension.
3. There will be completion message, marking the end of the process.

#### NOTE 
If you are running the program for the first time, run the ***prereqs.py*** file before executing the program, it will install all the necessary modules.
