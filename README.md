# Spark-movie-recommender-system
Movie recommender engine in Spark/Elastic Search
# Movie recommender engine in Spark/Elastic Search


<a href="http://s1383.photobucket.com/user/ssurmic/media/Screen%20Shot%202019-11-22%20at%203.35.38%20AM_zpsidghrwwn.png.html" target="_blank"><img src="https://i1383.photobucket.com/albums/ah307/ssurmic/Screen%20Shot%202019-11-22%20at%203.35.38%20AM_zpsidghrwwn.png" border="0" alt=" photo Screen Shot 2019-11-22 at 3.35.38 AM_zpsidghrwwn.png"/></a>
***
work is inspired by https://developer.ibm.com/patterns/build-a-recommender-with-apache-spark-and-elasticsearch/
*** 
work flow is listed as below:
The required data for the project is in data.zip file under the same repo

1. Load the movie dataset into Spark.

2. Use Spark DataFrame operations to clean up the dataset and load it into Elasticsearch.

3. Using Spark MLlib, train a collaborative filtering recommendation model.

4. Save the resulting model into Elasticsearch.

5. Using Elasticsearch queries and a custom vector scoring plugin, generate some example recommendations. The Movie Database API is used to display movie poster images for the recommended movie.



### Desired result:
"http://s1383.photobucket.com/user/ssurmic/media/Screen%20Shot%202019-11-22%20at%203.35.38%20AM_zpsidghrwwn.png.html" target="_blank"><img src="https://i1383.photobucket.com/albums/ah307/ssurmic/Screen%20Shot%202019-11-22%20at%203.35.38%20AM_zpsidghrwwn.png" border="0" alt=" photo Screen Shot 2019-11-22 at 3.35.38 AM_zpsidghrwwn.png"

