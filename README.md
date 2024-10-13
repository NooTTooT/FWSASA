# WSFFSA
Project Overview:
This project integrates a web scraper to collect financial data and performs sentiment analysis using a pre-trained model from Hugging Face.


Key Components:
- Web Scraper: Gathers financial text data.
- Pre-trained Model: The Gemma-2B-it-Finance-Aspect-Based-Sentiment-Analyzer handles aspect-based sentiment analysis (https://huggingface.co/snrspeaks/Gemma-2B-it-Finance-Aspect-Based-Sentiment-Analyzer).
- Integration: The scraper feeds data to the model for analysis.
- Dependencies
- transformers
- torch
- requests
- beautifulsoup4 (for HTML parsing)
- pandas (for data handling)


Install dependencies:
pip install transformers torch requests beautifulsoup4 pandas
