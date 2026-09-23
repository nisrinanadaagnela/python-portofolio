# Product Selection Optimization using Sentiment Analysis and Feature Weighting

My undergraduate thesis project. A full pipeline that combines web scraping, NLP-based sentiment analysis, and Binary Integer Programming to select the optimal set of sunscreen products based on real customer reviews, feature importance, and budget constraints.

## What it does

This project answers the question: *given a budget and a set of products, which combination of products should be selected to maximize overall consumer satisfaction?* It does this by building a complete data pipeline:

1. **Web scraping** — collecting customer review data for 9 sunscreen brands (Emina, Azarine, Skin Aqua, Biore, NPURE, L'Oréal Paris, NIVEA, Carasun, Wardah) from an online review platform.
2. **Preprocessing** — cleaning and normalizing raw review text, then splitting it into sentences using Stanza.
3. **Aspect extraction** — identifying product aspects/features (e.g. texture, price, effectiveness) mentioned in each review using Stanza's NLP pipeline.
4. **Sentiment classification** — classifying the sentiment of each aspect-related sentence using a fine-tuned IndoBERT model, then aggregating results into per-aspect satisfaction scores.
5. **Feature weighting** — determining the relative importance of each product aspect using the Best-Worst Method (BWM).
6. **Optimization** — formulating the product selection problem as a Binary Integer Programming (BIP) model, solved using a custom implementation of the **Balas algorithm** (a best-first search branch-and-bound method for 0-1 integer programming), to find the optimal set of products under budget and product-count constraints.

## Tech stack

- Python
- BeautifulSoup & requests (web scraping)
- Stanza (NLP: sentence splitting, aspect extraction)
- Transformers / IndoBERT (sentiment classification)
- pandas & NumPy (data processing)
- Custom implementation of the Balas algorithm (Binary Integer Programming solver)
- Microsoft Excel (feature weighting calculation using BWM)

## How to run

Open the notebook in Google Colab (recommended, since it connects to Google Drive for data storage) and run cells in order, section by section: Scraping → Preprocessing → Aspect Extraction → Sentiment Classification → Optimization.

## Note

This is my thesis project (undergraduate final project) in Mathematics at Universitas Padjadjaran. It represents the most comprehensive project in this portfolio, combining natural language processing, statistical analysis, and optimization theory to solve a real-world business decision problem.
