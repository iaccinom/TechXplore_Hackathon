## Inspiration
The application and potential of an open-source stock market predictor was a very appealing idea and with the increasing attention on crypto, we wanted to create a project that can help regular investors become more informed on their purchases.

## What it does
This uses a simple framework for data analysis using pandas, it takes in a large dataset of the past bitcoin market rates including closing and market capital prices, and uses this to test and predict a closing value for bitcoin at a specific date. 

## How we built it
Using the Google-colab feature to work together and importing various training set libraries and methods,  we started off by reading in our data set that we would be basing our model off of. This was a set of about 2862 tuples in relation to 7 attributes. Since we were mainly focused on the prediction of future closing prices of bitcoin, we excluded the other columns and focused on the closing columns. Then we began constructing our model and importing libraries such as Sequential, Dense, Activation, and Adam. We then chose mean-squared error as our losing metric for our linear regression model. Next, we began training our model using some basic methods provided in the imported libraries. Then, we evaluated our model and tested its prediction accuracy using r2_score for this evaluation. We found our prediction ran with a score of about 0.998.  Finally, we included a demo testing section at the end of our code based on the columns provided in our database. Using a prediction method we were able to compare an actual tuple value for Bitcoin closing price against our predicted one and found it to be very close.

## Challenges we ran into
One challenge we ran into was the fact that we had no background knowledge in coding in python. Our group mainly had experience coding in C, Java, and SQL, which helped familiarize ourselves with the coding environment, but having to try and learn new machine learning concepts and methods was a challenge that we strived to overcome. Using guides from the workshops we were able to formulate a simple program that was able to utilize machine learning concepts to fulfill our project goals.
 
## Accomplishments that we're proud of
Accomplishments from this project were being able to successfully implement a program that used machine learning to accurately predict bitcoin closing price values given a data set of previous bitcoin statistics. We are also very proud to be taking our first steps into data science and machine learning and hope to continue improving and building upon our knowledge to create even more ambitious projects. 

## What we learned
We learned some basic Python syntax as well as implementing useful data analysis libraries for machine learning and data modeling. We also learned how to collaborate effectively on a coding project and make our vision a reality.

## What's next for Predicting The Future of Cryptocurrency
There are many consulting firms and even software applications that use sophisticated probability and statistical models to predict future stock and market values, however, by iterating and using concepts from machine learning, we were able to quickly implement a short program that was able to predict market values for Bitcoin. Cryptocurrency is on the rise but has also proven to be somewhat unpredictable through conventional methods, Through the application of machine learning in this sector we can more safely inform people before making large investment decisions. 
