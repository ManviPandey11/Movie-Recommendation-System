# Movie-Recommendation-System
This project implements a recommendation system using the MovieLens dataset. It uses collaborative filtering to predict movie ratings for users based on their past interactions.

## Data Description
The project uses the following CSV files from the MovieLens dataset:
- `ratings.csv`: Contains user ratings for movies.
- `movies.csv`: Contains movie information, including titles and genres.
- `links.csv`: Contains links to additional movie data.
- `tags.csv`: Contains tags associated with movies.

## Methodology
1. **Data Loading:** Load CSV files into pandas DataFrames.
2. **Data Preprocessing:** Merge datasets and preprocess the data.
3. **Model Building:** Use the Surprise library to implement collaborative filtering.
4. **Model Evaluation:** Evaluate the model using RMSE.
5. **Prediction:** Make predictions and visualize results.

## Results
- RMSE Score: X
- Example Prediction: The predicted rating for User 1 on 'The Matrix' is Y.

## How to Run the Code
1. Clone the repository: `git clone <repository_url>`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook or Python script.

## Dependencies
- pandas
- numpy
- matplotlib
- scikit-surprise

## License
This project is licensed under the MIT License.
