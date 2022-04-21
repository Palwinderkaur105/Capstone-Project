# RAINFALL PREDICTION IN AUSTRAILIA: WILL IT RAIN TOMORROW?
## OVERVIEW
My dataset is about rain in Australia, and it contains around ten years' worth of daily meteorological observations from a variety of sites across the country. There are 145460 records in this collection, with 23 attributes. 'Rain Tomorrow' is a predictor variable that answers the question, "Will it rain tomorrow, Yes, or No?" There is one Date/Time attribute, six categorical elements, and sixteen numerical attributes in our dataset. The primary motivation for using this dataset is to predict if it will rain tomorrow, predict the accuracy of our results, and do cross validation to determine which model is best for my dataset by comparing accuracies. Australia is the driest populated continent on the earth, with 70 percent of the continent classified as desert or semi-desert. Rainfall is the only source of water on this island continent. Water availability in Australia is influenced by rainfall variations, just as it is in any other region. 

On the continent, dryness (lack of rainfall), floods(excessive rainfall), and droughts are all prevalent weather patterns. From 2009 to 2012, the eastern Australian provinces were flooded extensively. The northern tropical parts receive the most rain, whereas the interior is arid and desolate. Variations in rainfall have an impact on water availability, management, and future resource planning. Australia is suffering from a severe drought, which could be alleviated with the use of rainfall forecasts.

## KEYWORDS
Data visualization, Logistic regression model, K-Nearest Neighbors, Random Forest, Naïve Bayes Classification models.

## RESEARCH QUESTIONS
1.	Find out the degree of temperature that lies as highly concentration points
	
SOL. The biggest concentration of temperature points, which includes the maximum counts, is between 17 and 20 Degrees Celsius.

2.	Check yearly distribution of rainfall to find the years with minimum and maximum rain fall. 

SOL. The yearly distribution of rainfall demonstrates that the year 2010, 2011 and 2016 experiences as maximum rainfall with almost having more than 33000mm whereas, the wettest years were 2007, 2008, and 2017 with rainfall ranging from 0 to 17000 mm and in 2009, 2012, 2013, 2014, and 2015 average rainfall was there.

3.	Evaluate whether will it be raining tomorrow or not?

SOL. The Rain Tomorrow attribute's distribution gives information on 'Will it rain tomorrow or not?' which has two categories: 'Yes' (Will Rain) and 'No' (Won't Rain) (No Rain). So, after visualising I come to know that more than half of the data frequencies were held by ‘No’ and very less frequencies were stored in ‘Yes’ which demonstrates that my target variable is not equally distributed. For getting an accurate result, I need to perform sampling for equally distribution.

4.	Build different classification models and select an optimal model by comparing accuracies of all models.

SOL. I built Logistic Regression, K-Nearest Neighbor, Nave Bayes, and Random Forest Classifiers using this dataset. After that, I use K-fold, Stratified K-fold, and repeated random train-test for cross validation. Then, after comparing accuracies, I discovered that the Random Forest classifier is the best model for my dataset because it has the highest accuracy across all approaches.

## TOOLS
I will use python software for performing operations and to visualize my dataset.


