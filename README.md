# NYC Facial Market Analysis: Reddit & Google Maps Integration

This project identifies the best-rated facial treatments in New York City by merging crowd-sourced sentiment from Reddit with verified business data from Google Maps. 

## 🔍 Project Overview
Standard review sites often feel "pay-to-play." This analysis cuts through the noise by scraping 11 niche Reddit threads to find authentic community recommendations and then validating those suggestions against Google Maps ratings and review volumes.

## 🚀 Key Technical Features
* **Multi-Source Scraping:** Automated extraction of unstructured text from 11 Reddit community threads.
* **Sentiment Validation:** Cross-referenced Reddit "hidden gems" with Google Maps API data to confirm reliability.
* **Data Parsing:** Used Regular Expressions (Regex) to isolate user-suggested pricing (e.g., "$150", "120+") from messy comment data.
* **Metric Engineering:** Analyzed the "Value Ratio"—identifying locations with high community sentiment but lower-than-average NYC pricing.

## 🛠️ Tech Stack
* **Python:** Core analysis and data processing.
* **BeautifulSoup / PRAW:** Web scraping and Reddit API interaction.
* **Pandas:** Data cleaning, merging, and structured DataFrame management.
* **Matplotlib/Seaborn:** Visualization of price distributions across NYC boroughs.

## 📂 Repository Structure
* `yu/NYC_Facial_Analysis.ipynb`: Main analysis notebook containing scraping and visualization logic.
* `Facial_NYC_Results.csv`: The final cleaned dataset featuring pricing and review scores.
