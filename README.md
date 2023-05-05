# Topic-Modelling-using-LDA-model


This notebook loads data from a JSON file and performs some data analysis and visualization on it. The code reads the first 10,000 lines from the JSON file and loads them into a list of dictionaries using the json.loads() function. It then extracts the categories of the news articles, creates a frequency distribution of the categories, and plots a bar chart and a pie chart to visualize the distribution.

The code also groups the news articles by category and plots a line chart to show the trend of the publication dates of the articles in each category. Finally, the code defines a function to clean the text data by removing URLs, HTML tags, punctuation, and stop words, and tokenizing the text.

## Getting Started

### Prerequisites

- Python 3.x
- pip package manager

### Installing Dependencies

- Install all the dependencies given in requirements.txt file.

### Running the Program

1. Clone the repository
2. Install the dependencies
3. Open `topic_modeling.ipynb` in Jupyter Notebook
4. Run the notebook to preprocess the data, train the LDA model, and generate topic visualizations.

## File Description

- `topic_modeling.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and visualization.
- `data`: Data used in this project is kaggle news category dataset.

## Results

- The top words for each topic are displayed using word clouds.

## Authors

- Bhavya Pandya(https://github.com/bhavyapandya)

## Acknowledgments

- https://www.kaggle.com/datasets/rmisra/news-category-dataset
