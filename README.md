# movie-recommender-system-tmdb-dataset
A content based movie recommender system using cosine similarity
The details of the movies (title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB,

### About The Project
I have develop a Movie Recommendation System which will support only Hollywood movies. In this project if you will search for a movie, you will be recommended 5 more movies other than your searched movie having the same genre .The front-end of the project have been made on PyCharm whereas the backend is developed on Jupyter notebook .The recommended movies will appear along with their posters and these posters have been fetched using an API https://api.themoviedb.org/3/movie/n-US 
I have also used two datasets to implement my project. The first one is   “tmdb_5000_credits.csv”,this dataset provides the data of the movie id ,title ,cast and crew.        
The second dataset used is “tmdb_5000_movies.csv”, this dataset provides the data of the budget ,genres, original- title ,popularity and production components of different Hollywood movies.

### How to get the API key?
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.
How to run the project?
1.	Clone or download this repository to your local machine
2.	Install all the libraries pandas, streamlit, numpy   with the command pip install (library name).
3.	Get your API key from https://www.themoviedb.org/.
4.	Open your terminal/command prompt from your project directory and run the file app.py by executing the command streamlit run app.py
5.	Go to your browser and type https://192.168.0.143:8501  in the address bar.
6.	Hurray! That's it
7.	Now you just have to type the movie name from the dropdown  in the search bar and you are good to go.

### Similarity Score :

How does it decide which item is most similar to the item user likes? Here come the similarity scores.
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

### How Cosine Similarity works?

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
 
 ![WhatsApp Image 2022-05-29 at 8 25 38 PM](https://user-images.githubusercontent.com/105016477/170876592-a3cf43ed-cc57-4c1a-a21c-8842d1982329.jpeg)

 
