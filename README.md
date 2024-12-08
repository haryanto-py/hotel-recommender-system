# Hotel Recommendation System

Welcome to the **Hotel Recommendation System** repository! This NLP project leverages two powerful filtering methods to recommend hotels based on user preferences and collaborative insights.

## Features
1. City-Based Filtering (Demographic filtering)
- Recommends hotels based on the user's selected city.
2. Collaborative Filtering
  - Offers personalized recommendations by considering various requirements:
    - City
    - Hotel name
    - Room type
    - Number of guests
    - Star rating
    - Room amenities
    - Rate description
    - Similarity score
  - Combines user preferences with insights derived from collaborative data.

## Getting Started
### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required python libraries:
  - Pandas
  - Numpy
  - NLTK
  - Scikit-learn

### Installation
1. Clone the repository
   ```bash
   git clone https://github.com/haryanto-py/hotel-recommender-system.git
2. Navigate to the project directory:
   ```bash
   cd hotel-recommender-system
3. Install the required dependencies:
  ```bash
  pip install -r requirements.txt
  ```

### Usage
1. Open the Jupyter Notebook
2. Open and run the hotel_recommender.ipynb file to interact with the recommendation system.

## How It Works
1. City-based filtering:
   Users can select a city, and the system will display available hotels.
2. Collaborative filtering:
   Users can provide multiple preferences such as room type, amenities, and star rating. The system will analyze these preferences and recommend the best matching hotels.

## Future Enchancements
- Integrate user reviews for sentiment analysis-based recommendations.
- Add a web interface for better accessibility.
- Explore advanced machine learning algorithms for improved collaborative filtering.

## Acknowledgments
Special thanks to Keshav Ramaiah for sharing an open public dataset for building this hotel recommender system.
https://www.kaggle.com/code/keshavramaiah/hotel-recommender
