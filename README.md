# Movie Recommendation System

This project is a content-based movie recommendation system that utilizes a dataset of approximately 5,000 movies to provide tailored suggestions based on user input. Developed using Jupyter Notebook and PyCharm, the system leverages movie metadata to compute similarities and recommend movies that align with user preferences.

## Features

- **Content-Based Filtering**: Recommends movies by analyzing movie metadata such as genres, cast, crew, and keywords to find similar films.

- **Extensive Movie Dataset**: Incorporates data from around 5,000 movies, ensuring a broad range of recommendations.

- **Interactive Interface**: Provides an interactive platform for users to input their favorite movies and receive personalized recommendations.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Yuvraj657/MovieRecommendationSystem.git
   ```


2. **Navigate to the Project Directory**:

   ```bash
   cd MovieRecommendationSystem
   ```


3. **Install Required Libraries**:

   Ensure you have Python installed. Install the necessary packages using pip:

   ```bash
   pip install -r requirements.txt
   ```
   

   If `requirements.txt` is not provided, manually install the following libraries:

   - pandas
   - numpy
   - scikit-learn
   - nltk

   Install them using:

   ```bash
   pip install pandas numpy scikit-learn nltk
   ```


## Usage

1. **Prepare the Dataset**:

   Ensure that `movies.csv` and `credits.csv` are present in the project directory. These files contain the necessary movie metadata.

2. **Run the Jupyter Notebook**:

   Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```


   Open and execute the `Movie Recommender.ipynb` notebook to interact with the recommendation system.

3. **Using the Python Script**:

   Alternatively, you can run the `MovieRecommend.py` script:

   ```bash
   python MovieRecommend.py
   ```


   Follow the prompts to input your favorite movie and receive recommendations.

## How It Works

- **Data Preprocessing**: The system processes the movie metadata to extract relevant features such as genres, cast, crew, and keywords.

- **Feature Engineering**: Combines the extracted features into a single 'tag' for each movie.

- **Vectorization**: Converts the 'tags' into numerical vectors using techniques like CountVectorizer.

- **Similarity Calculation**: Computes the cosine similarity between movie vectors to determine how similar they are.

- **Recommendation Generation**: Based on the similarity scores, the system suggests movies that are most similar to the user's input.


## Acknowledgments

- The movie dataset used in this project is sourced from TMDb (The Movie Database).

- Inspired by various content-based filtering techniques in recommendation systems.

## Author

- Yuvraj Singh(AI and Data Science)
