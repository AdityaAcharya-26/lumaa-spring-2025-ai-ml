Movie Recommendation System - Content-Based

This project implements a content-based movie recommendation system using TF-IDF and cosine similarity. Given a user’s description, it recommends the top 5 movies from a small dataset based on text similarity.
Dataset

The dataset used in this project is a movies dataset, which includes details about 4,803 movies, such as:
	•	Title
	•	Overview (plot summary)
	•	Genres
	•	Keywords
	•	Director

The dataset contains columns such as budget, revenue, runtime, etc., but we mainly use the overview, genres, keywords, and director columns for building the recommendation system.

How to load the dataset:
	1.	Download the dataset from Kaggle Movies Dataset. or from this repository under the name of movie_dataset.csv
	2.	Load the dataset into your Python environment:
 Setup

Python Version:
	•	Python 3.7+

 Dependencies:
	•	pandas
	•	sklearn
	•	nltk


Link to python collab file : For any difficulties faced here is the collab file link : https://colab.research.google.com/drive/1Sa85EYCcs7PntrMA8f4bpecREqt4AI51?usp=sharing
  
  Results :

When given an input like:

“I love thrilling action movies set in space, with a comedic twist.”
The top 5 recommended movies are:

🔹 Rank 1 | Similarity Score: 0.1137
🎬 **Space Dogs**
📖 Belka, the amazing flying dog is unexpectedly hurdled into the streets of Moscow when the rocket she is in malfunctions during one of her circus routines...
🎭 Genres: Family Animation

🔹 Rank 2 | Similarity Score: 0.1129
🎬 **Gravity**
📖 Dr. Ryan Stone, a brilliant medical engineer on her first Shuttle mission, with veteran astronaut Matt Kowalsky in command of his last flight before retiring...
🎭 Genres: Science Fiction Thriller Drama

🔹 Rank 3 | Similarity Score: 0.1083
🎬 **Moonraker**
📖 During the transportation of a Space Shuttle a Boeing 747 crashes in the Atlantic Ocean yet when they go to look for the destroyed shuttle it is not there...
🎭 Genres: Action Adventure Thriller Science Fiction

🔹 Rank 4 | Similarity Score: 0.0986
🎬 **Space Chimps**
📖 Circus monkey Ham III works in a circus where he's regularly shot from a canon but he still lives in the shadow of his father's legacy...
🎭 Genres: Animation Family

🔹 Rank 5 | Similarity Score: 0.0979
🎬 **Grindhouse**
📖 Two full-length feature horror movies written by Quentin Tarantino and Robert Rodriguez put together as a two-film feature...
🎭 Genres: Thriller Action Horror

Salary Expectations (monthly) : [1750$ - 1950$]

## 🎥 Demo Video

[Click here to watch the demo](https://drive.google.com/file/d/19qVXPZkqqge-E40Wn67HKzAqSj1e7Xvf/view)
