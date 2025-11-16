# Rotten-Tomato-Score-Predictor

This project aims to predict Rotten Tomatoes critic scores using sentiment analysis on YouTube movie trailer comments. This predictive model can help assess audience and critic reactions before the movie's release, even ahead of official critic reviews, providing valuable insights for filmmakers, marketers, and analysts.

---
## Project Structure and Setup Instructions

### Open the Notebooks- Click the "Open in Colab" button at the top of the `.ipynb` file.

### Part 1 — Data Collection (Optional)  
**File:** `WebScraping_and_SentimentAnalysis.ipynb`  
**Author:** Guy Plawner  

This notebook:

- Scrapes YouTube trailer comments  
- Collects Rotten Tomatoes critic scores  
- Performs initial text cleaning and sentiment scoring  
- Generates the CSV dataset used for later modeling  

#### If you have a Google API Key:
-Ensure YouTube Data API v3 is enabled in your Google Developers Console<br>
-Insert your API Key where it says "youtubeAdmin = YouTube('APIKEY')" in code blocks 4 and 6 of the notebook<br>
-Run the notebook from the beginning cell by cell to scrape Rotten Tomatoes scores and YouTube comments and create a csv<br>
-Note: This step will take longer to run due to the web scraping process<br>
#### If you don’t have a Google API Key:
-Download the pre-scraped dataset movies_comments_cleanTest_with_sentimate.csv<br>
-Upload the file to the Colab environment<br>

### Part 2: Data Modeling, Training, and Visualization
**File:** `Data_Modeling_and_Visualization.ipynb`  
**Author:** Amy Margolina  

This notebook includes:

- Data loading and validation  
- Cleaning and preprocessing  
- Train/validation split  
- Feature engineering  
- Regression model training  
- Model evaluation  
- Visualizations and insights  

---

### Documentation and Model Evaluation  
**File:** `Project_Report.pdf`  

A full written report describing the entire project workflow, including model optimization steps and the progression of model metrics.
