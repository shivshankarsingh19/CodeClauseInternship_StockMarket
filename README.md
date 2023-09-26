# Stock Market Analysis

The dataset used (https://www.kaggle.com/datasets/aaron7sun/stocknews)

The provided code appears to be a Jupyter Notebook containing a combination of tasks and operations related to stock market prediction and natural language processing (NLP). Here's a summary of what each section of the code does:

1. **Importing Libraries:**
   - Imports various Python libraries such as NumPy, Pandas, Seaborn, Matplotlib, re (regular expressions), TextBlob, and scikit-learn modules for data analysis, data visualization, and machine learning.

2. **Loading Data:**
   - Loads two CSV files, 'Combined_News_DJIA.csv' and 'upload_DJIA_table.csv', presumably containing stock market news headlines and stock market data.

3. **Data Preprocessing:**
   - Combines the news headlines into a single column called 'Combined_News'.
   - Performs data cleaning on the headlines, removing characters like 'b', single and double quotes, and other special characters.
   - Preprocesses the text data by removing accented characters, handling contractions, and removing stopwords.

4. **Word Cloud:**
   - Uses the WordCloud library to create a word cloud visualization of the preprocessed news headlines.

5. **Tokenization and Sequencing:**
   - Tokenizes and sequences the preprocessed text data using the Tokenizer from Keras.
   - Prepares the text data for use in machine learning models.

6. **Sentiment Analysis:**
   - Calculates sentiment scores (subjectivity, polarity, compound, negative, positive, and neutral) for the news headlines using TextBlob and VADER SentimentIntensityAnalyzer.

7. **Feature Engineering:**
   - Creates a DataFrame containing various features, including sentiment scores, stock market data (Open, High, Low, Volume), and others.

8. **Machine Learning Model (Linear Discriminant Analysis):**
   - Divides the data into training and testing sets.
   - Utilizes Linear Discriminant Analysis (LDA) from scikit-learn to build a classification model for predicting stock market movements.
   - Makes predictions on the test data.
   - Plots a confusion matrix to evaluate the model's performance.

Please note that this code snippet provides a high-level overview of the operations performed in the notebook. The specific details and results of each operation, as well as the overall performance of the model, would require a deeper analysis of the notebook's output and additional information about the dataset used.
