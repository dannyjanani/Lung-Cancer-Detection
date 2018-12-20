# 4563 Final Project
####                  Abigail Rhue, Danny Janani
The goal of the project is to predict the type of cancer a person has based on images of a person's lungs. 
Although there are different types of cancer stages, the clincal T stage was the only one considered.
Clinical T stage values range from 1 to 5 and the accuracy of the training of the network is outputted.
The sample size of was quite small as there were only 422 patients given with the largest data set that could be found having around 1000, but that set had restricted access.

The results of the convolution were not accurate which can be attributed to a small data set and many parameters that are trying to be predicted.

The data is from NSCLC Radiomics which are found here:

  * [NSCLC Radiomics](https://wiki.cancerimagingarchive.net/display/Public/RIDER+Lung+PET-CT#feb29a5b6fcc43b89290329e5e09b138)
  is where the data was downloaded from.
  * The [Lung Clinical CSV File]( https://github.com/arhue1431/4563-Final-Proj/blob/master/Lung1.clinical.csv)
  contains infomration on each patient like their cancer diagnosis.
  * The [TCIA File](https://github.com/arhue1431/4563-Final-Proj/blob/master/doiJNLP-zohiLwie.tcia)
  has all of the images used.
  * The [Folder Access](https://github.com/arhue1431/4563-Final-Proj/blob/master/FolderAccess.csv) file was created from the folder names within the extracted data in order to be able to access all the files.

The jupyter notebook is found here:
[Jupyter Notbook](https://github.com/arhue1431/4563-Final-Proj/blob/master/Final.ipynb)

The following resources were used as references:
  * [Data Science Bowl 2017](https://www.kaggle.com/c/data-science-bowl-2017):  
  The data science bowl for 2017 on kaggle gave a large set of lung cancer images and asked competitors to work with it. 
  * [3D Imaging Example](https://www.kaggle.com/gzuidhof/full-preprocessing-tutorial):  
  Gives example of 3D imaging for the data set used in the data science bowl.
  * [3D Convolution Example](https://www.kaggle.com/sentdex/first-pass-through-data-w-3d-convnet?fbclid=IwAR0voIiPA6chiDa_rNsZHdd4479eDouj_FpBbDSA-IBvpJxQojKlNksFuXQ):  
  Gives example of how to perform 3D convolution of the data set from the data science bowl.

The final presentation presented in class is found here: [Final Presentation](https://github.com/arhue1431/4563-Final-Project/blob/master/Final.pptx) 
