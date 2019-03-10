# Crime Prediction From Street Images

Humans can intuitively understand what kind of crime is likely to happen in a street just by looking at it. In this hack project, I'm trying Deep Learning to predict crime level and crime category of a street just using the Google Street View images. Our hypothesis was that we could train a CNN to learn this “intuition”. I achieved an accuracy of **95%** in this process


**Order of notebooks:** 
- Hack Day Data Gen.ipynb
- Data Gen - Street View Images Pull.ipynb
- SF Crime.ipynb


**Methodlogy:**
- Collect Crime Data for a City like San Francisco frm SFPD data portal
- Get a metric of crime level for each street in San Francisco
  ![Crime in SF](https://github.com/athuly/Crime_Prediction_4m_Street_Images/blob/master/Images/download%20(1).png)
  ![Crime Metric](https://github.com/athuly/Crime_Prediction_4m_Street_Images/blob/master/Images/Screen%20Shot%202019-03-09%20at%204.48.02%20PM.png)
- Select random street center points and grab the Google Street View Images at each of those poits
  ![Google Street View Image](https://github.com/athuly/Crime_Prediction_4m_Street_Images/blob/master/Images/download.png)
- Use the Street View Images and Street Metric to train the Deep Learning Classifier
  ![Results](https://github.com/athuly/Crime_Prediction_4m_Street_Images/blob/master/Images/Screen%20Shot%202019-03-09%20at%204.44.12%20PM.png)
- For testing, get the nearest street centerpoint for any given location, grab the Google Street View Image and feed it to the classifier. 
 
