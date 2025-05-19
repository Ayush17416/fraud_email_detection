# 📧 Email Fraud Detection (Spam vs Ham)

This project focuses on exploring and analyzing an email dataset to identify and distinguish spam emails from non-spam (ham) ones. The notebook (`analysis.ipynb`) walks through the steps of data loading, cleaning, basic exploration, and initial visual insights.

---

## 📂 Project Overview

The notebook covers:

- Installation and import of necessary Python libraries
- Loading and inspecting a dataset of labeled emails
- Data cleaning and validation
- Exploratory data analysis (EDA), including visualizations

---

## 🛠 Technologies Used

- **Python**
- **Jupyter Notebook**
- **pandas**, **numpy**
- **matplotlib**
- **NLTK**
- **wordcloud**

---

## 🔧 Steps Performed

### 1. 📦 Installation & Setup

All necessary libraries are installed at the beginning using pip (executed in the notebook).

### 2. 🧪 Data Loading

- Dataset: `spam_ham_dataset.csv`
- Loaded using `pandas.read_csv()` with `latin1` encoding

### 3. 🧹 Data Cleaning

- Checked data structure using `df.info()`
- Identified missing values using `df.isnull().sum()`
- Detected and removed duplicate records using `df.drop_duplicates()`
- Reviewed dataset size with `df.shape`

### 4. 📊 Exploratory Data Analysis (EDA)

- **Class Distribution**:
  - Count and percentage of ham vs. spam emails
  - Displayed with a pie chart using `matplotlib`

- **Text Structure Analysis**:
  - Calculated number of characters and words per email using `.apply(len)` and `.apply(str.split).len()`

- **Visualization**:
  - Pie chart styled with custom colors, shadow, and labels to visualize spam vs ham distribution

---

## 📈 Visual Highlights

- 📉 **Pie Chart** showing class distribution (ham/spam)
- 📄 **DataFrame Preview** for initial dataset inspection
- 📏 **Text Metrics** including character and word counts

---

## 📁 File Structure

```
analysis.ipynb        # Jupyter Notebook with complete workflow
```

---

## ✅ Requirements

Install the required Python libraries with:

```bash
pip install numpy pandas matplotlib wordcloud nltk
```

Also, run the following in Python to download NLTK datasets:

```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```

---

## 📌 Notes

- This notebook provides a foundational analysis and prepares the data for future stages like feature extraction and machine learning.
- No machine learning model or advanced text processing (e.g., tokenization, TF-IDF) has been applied yet.

---

## 📬 Contact

For suggestions or collaboration, feel free to reach out.
