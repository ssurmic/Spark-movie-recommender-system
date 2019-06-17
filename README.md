# Spark-movie-recommender-system
Movie recommender engine in Spark/Elastic Search
# Movie recommender engine in Spark/Elastic Search


<a href="http://tinypic.com?ref=op4mww" target="_blank"><img src="http://i64.tinypic.com/op4mww.png" border="0" alt="Image and video hosting by TinyPic"></a>
***
work is inspired by https://developer.ibm.com/patterns/build-a-recommender-with-apache-spark-and-elasticsearch/
*** 
work flow is listed as below:
1. Load the movie dataset into Spark.

2. Use Spark DataFrame operations to clean up the dataset and load it into Elasticsearch.

3. Using Spark MLlib, train a collaborative filtering recommendation model.

4. Save the resulting model into Elasticsearch.

5. Using Elasticsearch queries and a custom vector scoring plugin, generate some example recommendations. The Movie Database API is used to display movie poster images for the recommended movie.



### Desired result:
<a href="http://tinypic.com?ref=1yv9kh" target="_blank"><img src="http://i65.tinypic.com/1yv9kh.png" border="0" alt="Image and video hosting by TinyPic"></a>
