# Media-Guardian

YouTube Link: https://www.youtube.com/watch?v=d-UilNQ8JD4

Overview:
The Government Feedback and Sentiment Analysis System is a comprehensive solution designed to facilitate effective government feedback by leveraging machine learning and data scraping methodologies. The system is adept at collecting information from a myriad of sources, including regional news websites, YouTube channels, and Twitter, employing robust web scraping tools and APIs.

Key Features:

1. Data Scraping:
Utilizing tools such as Beautiful Soup, Scrapy, and requests, the system meticulously scrapes data from around 200 news websites, capturing diverse perspectives across multiple languages. The scraped data is then organized and stored in a structured format, providing a foundation for subsequent analysis.

2. Sentiment Analysis Pipeline:
The backend, built with Flask and hosted on AWS, orchestrates a sentiment analysis pipeline. A fine-tuned Roberta model performs sentiment analysis on the scraped data, categorizing sentiments as negative, neutral, or positive. The resulting sentiment scores are aggregated to provide an insightful overview of public perception.

3. Interactive Dashboard:
The frontend, developed using React, features an interactive dashboard that transforms sentiment analysis results into actionable visualizations. Users can explore dynamic sentiment graphs, revealing temporal shifts in public sentiment, and an interactive Indian map, offering a state-wise breakdown of sentiment variations.

4. Machine Learning Insights:
The machine learning pipeline detects language, translates text into English, and employs the Roberta model for sentiment analysis. The model's predictions are mapped to sentiment scores on a continuous scale, offering nuanced insights into public sentiment.

Deployment:
The system's backend APIs are hosted on AWS, ensuring scalability and reliability. The GitHub repository includes comprehensive documentation, guiding users through the setup and deployment processes.

