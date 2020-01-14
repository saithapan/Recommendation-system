# Recommendation-system

For First project Weighted hybrid technique

-> Load the data
-> Merge the two files with they common id
-> clean the data which is not required 
-> check the data if any null value exists or not
-> For imdb website we get the weight formula
-> In the dataset there are also provided the popularity 
-> so the recommendation will show 50% from weight score and 50% from the popularaity

For KNN movie recommendation project
AIM:- Giving similar recommendations to the user who give somerating to the movie  
-> Load the data
-> Merge the two files with they common id
-> clean the data which is not required 
-> Now calculate the total # number ratings given for each movie 
-> Setting some threshold value from histogram for total number of rating
-> creating pivot matrix
-> Knn use euclidean distance to find distance inside that we will use cosine similarity


For movie recommendation using content filtering

-> Load the two datasets
-> Merge with common ids
-> Drop the unnecessary columns
-> Consider overview column  and convert that to vector matrix
-> For that we will using one of the NLP method  TF-IDF vectorizer
-> From here it will make sparse matrix
-> sparse matrix:- Matrix's which has lots of zero's values and less number of Non-Zero values
-> For Tf-IDF we will get vector matrix
-> So now we will apply sigmoid_kernel here
-> Sigmoid function explanation :- In logistic regression graph  the raph varies from 0 to 1 here sigmoid function is responsible for        transforming the input from b/w 0 to 1
-> For example consider overview1 is compared with al other overviews the resulting value with high proability top 10 will recommend
-> Call the function with movie name and sort and return the top 10 movie from it 
