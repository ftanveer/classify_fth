# classify_fth

Follow link below for deployed website:

https://ftanveer-classify-fth-main-waf9sl.streamlit.app/

**Data Collection File from  local directory**:

DATA COLLECTION.ipynb

**Data Processing:**

DATA PROCESSING.ipynb

**Web Scraper:**

web_scraper/ Bing_Image_Scrape.py


## GOAL OF PROJECT:
Make a classifier that can detect any type of facial hair and catagorize them. Some catagories include chevron moustache, horseshoe moustache etc. Currently classifier 
identifies moustaches , but soon will be able to identify more varities of facial hair. 


## HOW TO RUN:
All the files can be downloaded and hosted via streamlit. 

## METHOD USED:
All images are greyscaled and then filtered using a Haar wavelet transform and stacked on top of the original image, the resulting matrix is the training data used for the 
algorithm. I used Support vector machines as the model to classify images. 

## CONCLUSION:
Given the image fed to the model falls into chevron, horseshoe, pencil, handlebar and toothbrush moustache catagories then the model is able to preidct with 83% accuracy.

The model needs to be improved to handle multiple faces in one picture, label faces with no facial hair, detect more variety of facial hairs. 


