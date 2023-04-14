# Youtube Adview pridiction
Youtube is a world wide interactive platform, It is the second most visited website, right after Google itself. YouTube has more than one billion monthly users who collectively watch more than one billion hours of videos each day. As of May 2019, videos were being uploaded at a rate of more than 500 hours of content per minute.

Unlike popular videos which get number of likes and views by the time they are stated as popular, YouTube trending videos represents the content which is gaining viewership over a certain time period and has a potential to be
popular. 


<p>&nbsp</p>

# ⭕bjective
To build a Machine Learning model which will predict youtube adview count based on other youtube metrics including likes, dislike, comments, views, watch time etc.
Certain ML models have been trained and tested to pridict the adview score. 

<p>&nbsp</p>

# Instinct
1. ----> supervised and unsupervised learning
   
		 supervised -> Data remain tagged, features and lables are present, classification & regression takes place,
                       we train regressor or cluster

                                classification => classify which label a given set of features belong to.
                                    regression => find out the value of data using previous data.

		unsupervised -> Data not tagged, features and lables are not present, training not done, 
                        clustering and association takes place
						 
                                   association => association rule learning problem. such as poeple that buy X also 
                                                  tend to buy Y.
                                     clustring => discover the inherent groupings in the data, such as customers by 
                                                  purchasing behaviour.
                                    
				

3. ----> steps in typical machine learning 	
   
   		1) problem identification
		2) data collection and validation 
		3) model building
		4) feedback


4. ----> Training and test, splitting
   		
		* For any ML model 
			input = features
			output = label
			features ----> MODEL -----> label

		* Out data gets divided or splits into 2 parts 
    
            -> training data = used to train the model
                -> test data = use to test the mode checking its accuracy, if more it is nearner to the setted label, 
                               the more the accurate model will be.

  

<p>&nbsp</p>

# 📂 Data-Sets
* train.csv - Training set

* test.csv - Test set

* File train.csv contains data or information based on different attributes and other details of about 15000 YouTube videos, the file is taken for training and fitting into different algorithms. The data contains the number of views, likes, dislikes, comments and apart from that published date, duration and category are also included. The train.csv file also contains the data or information of ad views which is our target attribute for prediction. After training the data it is tested with test.csv 
  
<p>&nbsp</p>

# 📎Attribute Information

   * Vidid ---------/ unique Inditification ID for each video

   * AD VIEW -----/ Number of ad views for each video Project

   * VIEWS --------/ Number of unique views for each video

   * LIKES ---------/ The number of likes for each video

   * DISLIKES -----/ The number of Dislikes for each video

   * COMMENT ---/ Number of unique comments for each video

   * PUBLISHED ---/ Data of uploading the video

   * DURATION ----/ Duration of the video (in min. and seconds)

   * CATEGORY ----/ Category of each video
  
<p>&nbsp</p>

# <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/></a> Libraries & Technologies used

## <img src="https://numpy.org/images/logo.svg" alt="numpy" height="40" width="40"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> <img src="https://matplotlib.org/_static/images/logo2.svg" alt="matplotlib" width="60" height="40"/> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> <img src="https://keras.io/img/logo.png" alt="Keras" width="80" height="40"/>


<p>&nbsp</p>
<p>&nbsp</p>

<h3>Find useful, don't forget to hit ⭐</h3>
