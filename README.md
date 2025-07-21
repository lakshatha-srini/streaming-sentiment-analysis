# streaming-sentiment-analysis
This project loads and cleans streaming platform data from Amazon Prime, Disney+, Hulu, and Netflix. It performs exploratory data analysis, visualizing content types, genres, ratings, durations, and monthly title additions. Sentiment analysis on show titles and descriptions is done using TextBlob with detailed visualizations to compare platforms.

## Dataset

- Data sourced from CSV files for each platform (`amazon_prime_titles.csv`, `disney_plus_titles.csv`, `hulu_titles.csv`, `netflix_titles.csv`).

## Technologies Used

- Python
- Pandas, NumPy (Data processing)
- Seaborn, Matplotlib (Data visualization)
- TextBlob (Sentiment analysis)
- adjustText (Plot label adjustment)

## How to Run

1. Clone the repository.
2. Install required packages:

```bash
pip install -r requirements.txt
