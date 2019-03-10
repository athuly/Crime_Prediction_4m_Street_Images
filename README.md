# Crime Prediction From Street Images

Humans can intuitively understand what kind of crime is likely to happen in a street just by looking at it. In this hack project, I'm trying Deep Learning to predict crime level and crime category of a street just using the Google Street View images. Our hypothesis was that we could train a CNN to learn this “intuition”. I achieved an accuracy of <h4>95%</h4> in this process


Order of notebooks: 
1. Hack Day Data Gen.ipynb
2. Data Gen - Street View Images Pull.ipynb
3. SF Crime.ipynb


Methodlogy: 
1. Collect Crime Data for a City like San Francisco frm SFPD data portal
2. Get a metric of crime level for each street in San Francisco
  ![Crime in SF](https://github.com/athuly/Crime_Prediction_4m_Street_Images/blob/master/Images/download%20(1).png)
  ![Crime Metric](https://github.com/athuly/Crime_Prediction_4m_Street_Images/blob/master/Images/Screen%20Shot%202019-03-09%20at%204.48.02%20PM.png)
3. Select random street center points and grab the Google Street View Images at each of those poits
  ![Google Street View Image](https://github.com/athuly/Crime_Prediction_4m_Street_Images/blob/master/Images/download.png)
4. Use the Street View Images and Street Metric to train the Deep Learning Classifier
  ![Results](https://github.com/athuly/Crime_Prediction_4m_Street_Images/blob/master/Images/Screen%20Shot%202019-03-09%20at%204.44.12%20PM.png)
 5. For testing, get the nearest street centerpoint for any given location, grab the Google Street View Image and feed it to the classifier. 
 
