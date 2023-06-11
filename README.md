# hadoop
## simple practice projects to apply hadoop concepts 
- running MapReduce Job by analyzing movie ratings data to get the most popular ratings from ratings  data set.
## Running Steps :

- wget https://raw.githubusercontent.com/OmarKhaledAbdlhafez/hadoop/main/TopMovies.py
- wget https://raw.githubusercontent.com/OmarKhaledAbdlhafez/hadoop/main/ratings.txt
#### Running locally:
- python MovieRatings.py ratings.txt
##### Running on Hadoop cluster:
- python MovieRatings.py –r hadoop --hadoop-streaming-jar /usr/hdp/current/hadoop-mapreduce-client/hadoop-streaming.jar ratings.txt

