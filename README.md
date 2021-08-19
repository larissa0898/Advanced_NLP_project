# Advanced NLP Project - Main Topic Extraction
This repository contains two methods for main topic extraction with Wikipedia articles. One with tf_idf and the other one is manual (most frequently words in text). 

#### Table of Contents
- [Installation](#installation)
- [Usage](#usage)

## Installation 
Download all the files on this GitHub repository.  
With 'pip install -r requirements.txt' all required libraries are installed. 

![Step1](/Projektarbeit/images/step1.PNG)


## Usage
### tf_idf method
If you want to use the tf_idf-method, you have to run the code in 'tf_idf_extraction.py'. While running the code, you will be asked, whether you want to use the existing json file with the pre-processed data ('corpus.json') or wether you want to preprocess the data again and create a new json file (this takes about 8 minutes).  
![Step2](/Projektarbeit/images/step2.PNG)  
In the end, the title of the Wikipedia articles will be printed together with the five keywords, that were generated by the tf_idf method. In the last line the accuracy will be printed. 
![Step3](/Projektarbeit/images/step3.PNG)  
  
  
### manual method
If you want to use the manual method, you have to run the code in 'manual_extraction.py'. You will be asked, if you want to extract the data with the manual method again or if you want to use the existing data in the json file 'manual_extraction.json'.  
If you press 'yes' a new json file 'manual_extraction.json' will be created with the titles of the Wikipedia articles and the five most frequently occuring words in the Wikipedia texts.   
After that you will be asked, if you want to calculate the accuracy for this method. If you press 'yes' the total accuracy will be printed.
![Step4](/Projektarbeit/images/step4.PNG)