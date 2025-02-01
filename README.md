# RBC Branch Sentiment Analysis & Web Scraping

## Project Overview
This project involves **web scraping customer reviews** from **10 RBC bank branches** in **downtown Toronto** using **Google Maps API**. The collected reviews are then anazlyzed using **Natural Language Processing (NLP) and sentiment analysis** to gain insights into customer satisfaction and banking performance.

## Key Objectives
- Scrape customer reviews from  **Google Maps API** for RBC branches.
- Performance **sentiment analysis** to classify reviews as positive, negative, or neutral.
- Visualized customer sentiment trends using **data visualization techniques**.
- Bauild a **machine learning model** to predict sentiment from text data.

## Insight from the Data
- **70% of reviews were positive**, hihglighting **friendly staff and good service**
- **20-25% of reviews were negative**, pointing to **long wait times and poor servicec experiences**
- **5-10% of reviews were neutral** indicating mixed experiences.
- **Frequent negative keywords** included "slow","worst","issue", while **positive reviews** often mentioned "helpful","friendly", "efficient".

## Tech Stack 
- **Web Scraping**: Python (requests, pandas)
- **Sentiment Analysis**: nltk (VADER SentimentIntensityAnalyzer)\
- **Machine Learning**: sklearn (Logistic Regression with TF-IDF)
- **Data Visualization**: Matplotlib, Seaborn, WordCloud

## Results & Next Steps
- **Accuracy**: The sentiment classification model achieved ~70% accuracy.
- **Future Improvements**:
  - Test with deep learning models (BERT, RoBERTa) for better accuracy.
  - Compare RBC reviews with other major Canadian banks.
  - Expand data collection for long-term trend analysis.

## Conclusion
This project successfully analyzed customer sentiment regarding RBC bank branches in downtown Toronto using web-scraped reviews. The sentiment analysis revealed that while most customers had positive experiences, a significant portion expressed negative feedback, particularly around issues like service quality and branch management.
Key findings:
- **Positive sentiment** was dominant, with keywords like "service," "staff," and "customer" frequently appearing.
- **Negative reviews** highlighted concerns about service issues, long wait times, and account-related problems.
- **Neutral reviews** had overlapping elements from both positive and negative sentiments, making them harder to classify accurately.
The model achieved an **accuracy of 70%**, with strong performance in identifying positive sentiments but struggling with neutral reviews. Future improvements could include fine-tuning the model with additional training data, using more advanced NLP techniques, and incorporating aspect-based sentiment analysis to pinpoint specific areas of concern.
Overall, this project provides valuable insights into customer experiences at RBC branches, helping identify strengths and areas for improvement.

 ## Contributing
 Feel free to submit issues or pull requests to improve this project!
