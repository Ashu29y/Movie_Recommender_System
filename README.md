
# Movie Recommender System


## Overview
This project implements a movie recommender system using cosine similarity. The system suggests movies to users based on their preferences and similarity to other users.

## Features
- **Cosine Similarity:** Cosine similarity is a metric used to measure the similarity between two vectors in a multi-dimensional space. It calculates the cosine of the angle between the two vectors, which represents how similar they are in direction regardless of their magnitude.

In the context of a movie recommender system, cosine similarity is often used to compare the preferences of users for different movies. Each user's preferences can be represented as a vector where each dimension corresponds to a different movie, and the value of each dimension represents the user's rating or preference for that movie.
- **User-based Recommendation:** Recommends movies to users based on the preferences of similar users.
- **Movie Database:** Accesses a database of movies and their attributes to provide recommendations.
- **User Interaction:** Provides a simple user interface for users to input their preferences and receive movie recommendations.

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Streamlit (for web interface, optional)

## Installation
1. Clone the repository: git clone https://github.com/Ashu29y/Movie_Recommender_System  
1. 2. Install dependencies: pip install -r requirements.txt


## Usage
1. Ensure you have a dataset of movie ratings. The dataset should include user IDs, movie IDs, and ratings.
2. Run the recommender system:

## Credits
This project was developed by Ashutosh Kumar Gautam as part of intern at Acmegrade assigned to a project to build a Movie recommender System .


**Feel free to customize it further to suit your project's specific details and requirements!**




## Lessons Learned

**Introduction**  
Cosine similarity is like a compass guiding us through the vast landscape of data similarity. It's a mathematical tool that measures how alike two vectors are in direction, regardless of their magnitude. But how does it work, and why is it so useful?  

**Visualizing Similarity**  
Imagine each user's movie preferences as a unique vector in a multi-dimensional space. Each dimension represents a different movie, and the value along that dimension signifies the user's rating or preference for that movie.  
**Calculating Cosine Similarity**  
To find the cosine similarity between two user vectors, we take the dot product of the vectors and divide it by the product of their magnitudes. This gives us a value between -1 and 1.  
**Interpreting the Result**  
- Cosine Similarity = 1: Perfect alignment! The users have identical tastes in all movies.  
- Cosine Similarity = 0: Orthogonal vectors! No discernible similarity in preferences.  
- Cosine Similarity = -1: Perfect opposition! The users' preferences are exact opposites  
**Application: Movie Recommender System** : In the realm of movie recommendations, cosine similarity is a powerful tool. It helps us find users with similar tastes and suggests movies they might enjoy based on what others with similar preferences liked.  
**Conclusion**  
Cosine similarity isn't just a mathematical concept; it's a guiding light in the world of data similarity. With its help, we navigate through vast datasets, uncovering hidden connections and offering personalized recommendations.

So, let's embrace cosine similarity as our trusty compass, guiding us through the vast landscape of data!





## Screenshots

![App Screenshot]![Screenshot 2024-04-28 124429](https://github.com/Ashu29y/Movie_Recommender_System/assets/125810482/183ea42b-5e2f-466b-8f44-47e08e4b92d8)


