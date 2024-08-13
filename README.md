

Welcome to my Sentiment Analysis Project, developed as part of the IT CODING course. This project focuses on extracting and analyzing customer sentiment from Amazon product reviews.

## Project Overview

- **Web Scraping**: The project includes a web scraper designed to extract reviews from Amazon. The scraper is limited to the first 10 pages of reviews due to Amazon's restrictions.
  
- **Sentiment Analysis**: Once the reviews are gathered, the project delves into sentiment analysis using Natural Language Processing (NLP) techniques. Two powerful models are used for this purpose:
  - **VADER**: A rule-based sentiment analysis tool that is particularly effective in social media texts.
  - **RoBERTa**: A robustly optimized BERT approach, which is a state-of-the-art model for sentiment classification.

- **Model Selection & Fine-Tuning**: After conducting the initial analysis, different machine learning models are fine-tuned and evaluated to determine which performs best for sentiment classification on this dataset.

## How to Use

1. **Web Scraping**: Run the web scraper to collect Amazon reviews. Please note that scraping is limited to 10 pages due to Amazon's anti-scraping mechanisms.
2. **Sentiment Analysis**: Perform sentiment analysis using VADER and RoBERTa to assess the sentiment of the reviews.
3. **Model Evaluation**: Compare various machine learning models to select and fine-tune the best one for sentiment analysis.

## Contributing

If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request. Your feedback is highly appreciated!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to customize this further based on your project specifics!
