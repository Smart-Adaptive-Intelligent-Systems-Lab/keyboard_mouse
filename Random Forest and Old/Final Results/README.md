
# Workflow

## preprocess data 2.ipynb
- input: raw dataset

- output: user1_preprocessed_2.csv, user2_preprocessed_2.csv

## gretel preprocess.ipynb

- input: user1_preprocessed_2.csv, user2_preprocessed_2.csv

- output: preprocessed_gretel.csv

## gretel.ai
- input: preprocessed_gretel.csv

- output: gretel_data.csv

## gretel_postprocess.ipynb
- input: gretel_data.csv

- output: postprocessed_gretel.csv

## Random Forest Final.ipynb
- input: postprocessed_gretel.csv, user1_preprocessed_2.csv, user2_preprocessed_2.csv

- output: 5-Fold CV results