# Financial News Summarization Sentimental Analysis

Financial News Summarization Sentimental Analysis is a natural language processing project that focuses on summarizing and analyzing sentiment in financial news articles. The system is designed to process user-provided URLs or text inputs, allowing users to quickly obtain insights into financial articles for informed decision-making.

## Project Goal

The primary goal of this project is to develop a system that can summarize financial news articles and analyze sentiment based on user-provided URLs or text. By leveraging advanced natural language processing techniques, the system aims to provide users with concise and informative summaries along with sentiment analysis results.

## Data Science Approach

The project utilizes a data science approach with the following key components:

1. **Fine-tuned LLM (Large Language Model):** Enhanced large language models for domain-specific understanding, contributing to improved comprehension of financial content.

2. **Finbert for Sentiment Analysis:** Integration of the Fine-tuned (by me) Finbert model for accurate financial sentiment analysis, ensuring the system captures nuanced sentiments related to the financial domain.

3. **Large-Bart CNN for Summarization:** Implementation of a CNN (Convolutional Neural Network) model using Large-Bart for extractive summarization, generating concise and informative summaries of financial news articles.

## Challenges Overcome

The development of FinancialNews_SentimentalAnalysis encountered and successfully addressed the following challenges:

1. **Imbalanced Data:** Mitigated through the application of augmentation and re-sampling techniques, ensuring a more balanced and representative dataset for training.

2. **Overfitting:** Addressed through regularization techniques and hyperparameter optimization, preventing the model from memorizing the training data and improving generalization to new data.

## Outcomes

The project has achieved a commendable 75% accuracy, providing users with quick insights into financial articles. The system's ability to summarize complex financial information and analyze sentiment empowers users to make more informed decisions in the realm of finance.

## Usage

### App.py

The main code file, `app.py`, contains the implementation of the system. Users can run the app by providing either a URL or text input. The system automatically scrapes the content from the URL if provided and displays the summarized text, sentiment analysis results with percentages, and the overall sentiment.

### Requirements.txt

The `requirements.txt` file lists the necessary dependencies to run the project. Ensure that these dependencies are installed in your environment before running the application.

## Example Usage

To test the system, I have run the app with the provided example URL:

- [Example URL](https://www.moneycontrol.com/news/business/stocks/broader-indices-touch-fresh-highs-48-small-caps-give-double-digit-return-11975831.html)

The output will include the URL, scraped text (in case of URL) or enteed text (in case of text), summarized text, sentiment with percentages, and the overall sentiment.

Feel free to experiment with other URLs or text inputs to observe the system's performance.

## Note

While the app runs for all cases, it is designed to provide more accurate and reliable results when given financial news content. Users are encouraged to explore the system with various inputs to experience its capabilities.

Feel free to contribute, report issues, or provide feedback to enhance the functionality of Financial News Summarization Sentimental Analysis.

**Note:** I apologize for not being able to upload the fine-tuned Finbert model in the repository due to its substantial size.
