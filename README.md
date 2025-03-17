# Real_time_Sentiment_Analysis-Emman

# Real-Time Social Media Sentiment Analyzer

## 📌 Project Overview

This project is a **Real-Time Social Media Sentiment Analyzer** that utilizes **VADER (Valence Aware Dictionary and sEntiment Reasoner)** to analyze the sentiment of social media comments and tweets. It classifies text as **Positive, Negative, or Neutral**, helping businesses and individuals monitor public perception in real time.

## 🚀 Features

- Uses **VADER** for sentiment analysis (optimized for short social media text).
- Processes large datasets efficiently.
- Allows real-time sentiment analysis on user-inputted text.
- Provides visualizations for sentiment distribution.

## 📂 Dataset

- **Dataset Used:** Sentiment140
- **Source:** [Kaggle - Sentiment140 Dataset](https://www.kaggle.com/datasets/kazanova/sentiment140)
- **Size:** 1.6 million tweets
- **Columns Used:**
  - `target` (0 = Negative, 2 = Neutral, 4 = Positive)
  - `text` (Tweet content)

⚠ **Note:** Since the dataset exceeds GitHub's upload limit, please download it from Kaggle before running the project.

## 🛠 Installation & Setup

### Prerequisites

Ensure you have the following installed:

- **Python 3.x**
- Required libraries: `nltk`, `pandas`, `matplotlib`, `seaborn`

Install dependencies using:

```bash
pip install nltk pandas matplotlib seaborn
```

### Running the Project

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/Real-Time-Sentiment-Analyzer.git
   cd Real-Time-Sentiment-Analyzer
   ```

2. **Download the Dataset:**\
   Since the dataset is too large for direct upload, download it manually from [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140) and place it in the `data` folder.

3. **Run Sentiment Analysis on Dataset:**

   ```bash
   python src/sentiment_analysis.py
   ```

   This processes the dataset and classifies sentiments.



## 📊 Output

- **Predicted Sentiments:** Positive, Neutral, Negative
- **Visualization:** Bar charts and pie charts for sentiment distribution
- **Accuracy:** 73% using VADER

## 🏆 Future Enhancements

- Fine-tune VADER for industry-specific sentiment analysis.
- Integrate additional ML models for better accuracy.
- Implement a web-based interface for real-time sentiment tracking.

## 📝 License

This project is licensed under the **MIT License**.

## 📬 Contact

For queries or contributions, feel free to reach out or submit a pull request! 🚀

