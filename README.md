# Sentiment-Analysis-Topic-Modelling
The purpose of this project is that, If is one buying any product online he/she will not have to go through all the reviews of any in fact our model will perform sentiment analysis on all the reviews and help make a better decision if the product is worth purchasing and also have a model that lists 5 topics people are talking about in the reviews

Flowchart: Here is the entire flow chart of the project.
Start
|
|-- Collect  Dataset
| |
| |-- Explore and Preprocess Data
| | |
| | |-- Remove duplicates
| | |-- Handle missing values
| | |-- Tokenization, stemming/lemmatization (running to run: base form)
| | |-- Remove stop words and special characters
| | |-- Vectorize text data  (TF-IDF)
| | |
| |-- Split Dataset into Training and Testing Sets
| |
| |-- Training Data
| | |
| | |-- Train Sentiment Analysis Model
| | | |
| | |-- Select NLP model (SVM)
| | |-- Fine-tune model on sentiment labels
| | |
| | |-- Train Topic Modeling Model
| | |
| | |-- Select Topic Modeling Algorithm (LDA)
| | |-- Extract topics from reviews
| |
| |-- Testing Data
| |
| |-- Sentiment Analysis
| | |
| | |-- Predict sentiment of reviews
| |
| |-- Topic Modeling
| |
| |-- Extract topics from reviews
|
|-- Combine Sentiment and Topic Scores
| |
| |-- Create a Scoring System 
|
|-- Product Recommendation
| |
| |-- Define Recommendation Rules
| | |
| | |-- Use sentiment and topic scores
| | |
| |-- Apply Recommendation Rules
| |
| |-- Recommend products based on scores
|
|-- End


