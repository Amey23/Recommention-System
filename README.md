## Read the complete medium article [here](https://medium.com/swlh/beginners-guide-to-build-recommendation-system-2bd4a96aa3e?source=---------12----------------------------)

# Recommention-System
**This repository contains the code for building movie recommendation system.**

-	Approach 1 :- By weighted average
-	Approach 2 :- By popularity and genre
-	Approach 3 :- By content(overview) based


**Dependencies**
1. Python >=3.5
2. pandas
3. numpy
4. scipy
5. scikit-learn
6. scikit-surprise
7. matplotlib
8. seaborn
9. jupyter notebook
10.jupyter lab

**Download dataset**
- [Link :-](https://drive.google.com/drive/folders/1JnQXDCsGAb75I4PRRMDHUO0WxmXT-usv?usp=sharing)
 
**Obseravtions**
- From approach 1 we got that The Shawshank Redemption movie has the highest weighted_average score.
- From approach 2 we got that Wonder Woman movie is most popular among all the movies in dataset. When a new user will introduced in dataset then ofcourse this movie will be recommended to him as he won't have browsing history at initial time.
- From approach 2 we also got movie recommendations for a particular genre based on scaling of movies according to the Weighted_average score from highest to lowest.
- From approach 3 we got recommendations based on content-based filtering using tfidfVectorizer and cosine similarity.
