# Sentiment Analysis Word Bubble Plot

## Overview

This project performs sentiment analysis on customer reviews for Starbucks and visualises the results using a word bubble plot. It helps you understand the sentiment of customer feedback and identifies frequently occurring words associated with positive and negative sentiments.

## Features

- **Text preprocessing**: Removes punctuation, converts text to lowercase, tokenises the text and removes carefully chosen stopwords.
- **Sentiment analysis**: Calculates sentiment scores for each review using the VADER sentiment analyser.
- **Word frequency analysis**: Counts word frequencies in the filtered tokens.
- **Word bubble plot**: Generates word clouds for words associated with positive and negative sentiments.
- **Visualisation**: Presents the word clouds in a visually appealing format for easy interpretation.

## Usage

1. **Install Dependencies**:
   - Ensure you have the required libraries installed. You can install them using pip:
     ```bash
     pip install pandas nltk matplotlib wordcloud
     ```

2. **Run the Code**:
   - Open the Jupyter Notebook or Python script to run the code.
   - Make sure you have the dataset ('reviews_data.csv') in the same directory or specify the correct file path.

3. **Interpret the Results**:
   - The code will generate a word bubble plot with two subplots: one for positive sentiment words and one for negative sentiment words.
   - Explore the word clouds to understand which words are associated with different sentiments in customer reviews.

4. **License**:
   - This project is licensed under the MIT License. You are free to use, modify, and distribute the code as per the license terms. See the [LICENSE](LICENSE) file for details.

## Dataset

The project uses a dataset of customer reviews for sentiment analysis. The data was obtained from the [Starbucks Reviews Dataset on Kaggle](https://www.kaggle.com/datasets/harshalhonde/starbucks-reviews-dataset).

## Author

- Lara Ann Xiberras
- laraxiberras@gmail.com

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for details.
