# Master Thesis - Reward Systems Analysis on EthTrader

This repository contains all the code used for the thesis titled **"Exploring Rewards Systems in Online Social Media through Content Analysis Techniques"**. Below is the list of scripts, a brief explanation of their purpose, and the datasets they utilize.

## Project Structure

### 1. `rewards analysis_Github.ipynb`
- **Description**: Analysis on correlation and trend over time.
- **Data Required (Google Drive link)**:
  - `reddit_distr` 
  - `reddit_distr/posts`
- Already run. Results are included in the notebook.

### 2. `label_analysis_x_GitHub.ipynb`
- **Description**: Analyses on labels assigned to items by human reviewers.
- **Data Required (Google Drive link)**:
  - `sample_final.xlsx` 
  - `reddit_distr/posts`
- Already run. Results are included in the notebook.

### 3. `feature_extraction_all_data_x_GitHub.ipynb`
- **Description**: Extraction and creation of features to test the best model on all posts.
- **Data Required (Google Drive link)**:
  - `reddit_distr/posts` 
  - `data_pre_reward_x_final_classification` 
  - `data_post_reward_x_final_classification` 
- Not run. Aggregated results are provided, as the script requires a large amount of data and significant processing time. Therefore, the code execution took place on multiple files.

### 4. `models_x_GitHub.ipynb`
- **Description**: Applies machine learning models on a sample of Reddit posts, extracts features, performs feature selection, and evaluates models. The best model is used for feature importance and applied to the entire dataset for classification.
- **Data Required (Google Drive link)**:
  - `sample_final` 
  - `reddit_distr/posts` 
  - `all_1`
  - `all_2`
  - `input_data_final`
  - `sample_x_best_model`
  - `data_pre_reward_x_final_classification`
  - `data_post_reward_x_final_classification` 
- Already run. Results are included in the notebook.

