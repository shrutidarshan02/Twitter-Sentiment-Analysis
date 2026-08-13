# Dataset

The dataset used in this project was obtained from Kaggle.

## Dataset Details

- **Dataset:** Sentiment140
- **Source:** Kaggle
- **Records:** 1,600,000
- **Sentiment Classes:** Positive and Negative
- **File Used:** `training.1600000.processed.noemoticon.csv`

## Dataset Structure

The dataset contains the following fields:

- `sentiment` — sentiment label
- `id` — record identifier
- `date` — tweet date and time
- `query` — query field
- `user` — user identifier/name
- `text` — original tweet text

During the analysis, additional columns such as `clean_text`, `weekday`, and `hour` were created for text preprocessing and time-based analysis.

## Dataset Balance

The dataset contains:

- **800,000 negative records**
- **800,000 positive records**

Therefore, the dataset used in this project has an equal distribution of the two sentiment classes.

## Note

The original CSV dataset is **not included in this repository** because of its large file size.

To reproduce the analysis, download the Sentiment140 dataset from Kaggle and place the CSV file inside this `data/` folder.

The exact Kaggle dataset URL is not included because the original project was created several months ago and the exact source link is no longer available.
