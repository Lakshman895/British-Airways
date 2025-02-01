# Airline Reviews Data Analysis

<img src="Image/image.webp" alt="Brithish Airways Analysis" title="Weather Image Classification" width="600" height="400">

## 📌 Overview
This project focuses on extracting and analyzing airline reviews through web scraping. The collected data undergoes multiple preprocessing steps to ensure quality analysis. The insights help in understanding customer sentiments, identifying common complaints, and extracting valuable information for airline service improvements.

## 🔍 Data Extraction & Processing
1. **Web Scraping** 🕸️ - Collected airline reviews from various sources.
2. **Convert Text to Lowercase** 🔡 - Ensures uniformity in text analysis.
3. **Remove Numbers** 🔢 - Eliminates unnecessary numerical values.
4. **Remove Punctuation** ✂️ - Cleans text for better analysis.
5. **Remove Extra Whitespaces** 🚮 - Standardizes text format.
6. **Remove Stopwords** 🚫 - Improves the relevance of words in analysis.
7. **Perform Lemmatization** 🔄 - Converts words to their base form.
8. **Correct Spelling** ✅ - Ensures consistency in word usage.

## 📊 Key Insights
1. ✔️ **Data Cleaning & Preprocessing** - Improved text quality by removing irrelevant elements.
2. ✔️ **Sentiment Analysis** - Classified reviews as positive, negative, or neutral.
3. ✔️ **Word Frequency & WordCloud** - Identified the most common words used in reviews.
4. ✔️ **Named Entity Recognition (NER)** - Extracted key details such as airline names, locations, and dates.
5. ✔️ **Topic Modeling (LDA)** - Discovered recurring themes in customer feedback.
6. ✔️ **Customer Complaint Analysis** - Identified major issues like delays, lost baggage, and customer service concerns.

## 📁 Project Structure
- **data/** - Contains raw and processed datasets.
- **notebooks/** - Jupyter notebooks for data analysis.
- **visualizations/** - Includes generated charts and word clouds.
- **scripts/** - Python scripts for data preprocessing and analysis.
- **README.md** - Project documentation.

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Lakshman895/British-Airways.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run preprocessing script:
   ```bash
   python scripts/preprocess_data.py
   ```
4. Run analysis notebooks to generate insights.

## 🤝 Contributing
Feel free to submit issues or pull requests to improve this project. Any contributions are welcome!

## 📜 License
This project is licensed under the MIT License.

