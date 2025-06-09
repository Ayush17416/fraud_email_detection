# Email Fraud Detection Visualization Project

## 📌 Project Objective
The goal of this project is to explore and visualize an email dataset to uncover insights regarding spam (fraudulent) and ham (legitimate) messages. This analysis helps in understanding patterns in email content and supports spam detection systems.

## 🛠 Tools and Libraries Used
- **Python** (Jupyter Notebook)
- **Pandas, NumPy** for data analysis
- **Matplotlib, Plotly, WordCloud** for data visualization
- **NLTK** for text processing

## 📊 Key Visualizations
1. **Pie Charts** (Static and Interactive): Distribution of spam vs ham emails.
2. **Bar Plots**: Top 30 words in spam and ham emails.
3. **Histograms**: Distribution of word and character count.
4. **Word Clouds**: Commonly used words in both categories.

## 🔍 Data Preprocessing
- Removed duplicates
- Handled missing values
- Applied text cleaning using NLTK
- Added features like word count and character length

## 💡 Insights & Findings
- Spam emails tend to have higher word and character counts.
- Specific words appear more frequently in spam emails.
- Interactive plots offer a better understanding of email classification patterns.

## 🧪 Model Building (Brief)
- TF-IDF Vectorizer and CountVectorizer were used.
- Multiple ML models (e.g., XGBoost, Logistic Regression) were trained.
- Accuracy metrics were calculated to find the best-performing model.

## 🧭 How to Use
1. Clone the repository from GitHub.
2. Run `analysis.ipynb` using Jupyter Notebook.
3. Follow markdown instructions and visualize insights.

## 📂 Repository Contents
- `analysis.ipynb`: Main notebook with visualizations
- `data/`: Contains the email dataset
- `README.md`: Project documentation
