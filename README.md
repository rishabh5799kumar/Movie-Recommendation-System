# Movie Recommendation System
This project is a content-based movie recommendation system that uses machine learning techniques to suggest movies similar to the ones you like. It utilizes the cosine similarity algorithm to find similarities between movies based on their features like genres, keywords, and overview.

## Features
- **Data Preprocessing:** Load and preprocess movie data from a CSV file, including cleaning and handling missing values.
- **TF-IDF Vectorization:** The model uses the Term Frequency-Inverse Document Frequency (TF-IDF) technique to convert textual data into vectors.
- **Cosine Similarity:** To calculate the similarity between movie vectors, cosine similarity is employed to recommend the most relevant movies.
- **Movie Recommendation:** Based on the selected movie, the system suggests similar movies by matching features like genre, plot, and other descriptions.

## How to Run
1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Download the `movies.csv` dataset and place it in the project directory.
4. Run the notebook:
    - Open the Jupyter Notebook `Movie_Recommendation_System.ipynb` and execute the cells to run the code.
    
## Dependencies
- Python 3.x
- NumPy
- Pandas
- Scikit-learn

## Future Improvements
- Incorporate a hybrid recommendation approach by combining content-based filtering with collaborative filtering.
- Include user-based filtering to personalize recommendations further.

## License
This project is licensed under the MIT License.
