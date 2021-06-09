1) These programs are designed to create groups of similar news.
2) Initially, complete dataset is cleaned using nltk libarary. The code is given in Cleaning.ipynb file. 
3) Then subset of first 1230 news is taken and duplecate titles are dropped from the same. 
4) Finally 1189 unique news titles were taken into consideration which are grouped into 22 clusters according dataset.
5) Then many embedding methods and two clustering techniques were tried on the cleaned subset. Code of best two of those trials are given in this folder.
6) First Embedding method:
   i) Combination of BagOfWord and TF*IDF embedding techniques is used to embed the news titles.
   ii)Embedded titles are then clustered using hierchical clustering technique.
   iii) Accuracy of this method is found to be around 68. 
   iv) Details of how accuracy is found out, are given in BOW_TFIDF_mapping.xlx and BOW_TFIDF_Hier_new.csv file. 
   v) The code of the same is given in BOW_TFIDF.ipynb file.
7) Second Embedding method:
   i) Univesal sentence Encoding technique(one of the BERT techniques) is used to embed the news titles.
   ii)Embedded titles are then clustered using hierchical clustering technique.
   iii) Accuracy of this method is found to be around 67. 
   iv) Details of how accuracy is found out, are given in USE_Hier_mapping.xlx and USE_Hier_new.csv file. 
   v) The code of the same is given in USE_Hier_Google_Colabs.ipynb file.
   vi) This code is actually done in Google Colabs due to various dependencies.
