# 🔍 Fake News Detection System

A machine learning project that detects fake news articles using multiple classification models and advanced NLP techniques.

---

## 📊 Dataset

The dataset files are hosted on **Google Drive** due to GitHub's 25MB file size limit.

### 📥 Download Dataset

**[Click Here to Download Dataset]([https://drive.google.com/drive/folders/YOUR_GOOGLE_DRIVE_FOLDER_ID](https://drive.google.com/drive/folders/10LAc0GBmU0-upfUVZnozdDOeelQbJmKz?usp=sharing))**

**Dataset Files:**
- `True.csv` - Real news articles (labeled as authentic)
- `Fake.csv` - Fake news articles (labeled as false)
- Size: ~25MB total

**Setup Instructions:**
```bash
# 1. Download the dataset ZIP from Google Drive link above
# 2. Extract the files
# 3. Place them in the data/ folder:
#    data/True.csv
#    data/Fake.csv
```

---

## 🛠️ Features

✅ **Multiple ML Models:**
- Logistic Regression
- Decision Tree Classifier
- Gradient Boosting Classifier
- Random Forest Classifier

✅ **Real-time Detection:**
- Analyze news articles in real-time
- Get confidence scores
- Detect patterns and anomalies

✅ **Interactive Testing:**
- Input any news text
- Get instant predictions
- Compare multiple model results

---

## 💻 Technology Stack

- **Python 3.x**
- **Jupyter Notebook**
- **Libraries:**
  - `pandas` - Data processing
  - `scikit-learn` - Machine Learning models
  - `numpy` - Numerical computations
  - `matplotlib` - Data visualization
  - `seaborn` - Statistical visualization
  - `textblob` - Sentiment analysis
  - `wikipedia-api` - Fact checking

---

## 🚀 Quick Start

### Prerequisites
```bash
python --version  # Python 3.7+
pip --version     # pip 20+
```

### Installation

**Step 1: Clone the repository**
```bash
git clone https://github.com/yourname/Fake-News-Detection.git
cd Fake-News-Detection
```

**Step 2: Create virtual environment**
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

**Step 3: Install dependencies**
```bash
pip install -r requirements.txt
```

**Step 4: Download dataset**
- Download from [Google Drive Link]((https://drive.google.com/drive/folders/10LAc0GBmU0-upfUVZnozdDOeelQbJmKz?usp=sharing))
- Extract to `data/` folder

**Step 5: Launch Jupyter Notebook**
```bash
jupyter notebook
```

**Step 6: Run the notebook**
- Open `Fake_News_Detection.ipynb`
- Press `Kernel → Restart & Run All`
- Test with your own news articles

---

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| Logistic Regression | 98.5% | 98.3% | 98.7% | 98.5% |
| Decision Tree | 97.2% | 97.0% | 97.4% | 97.2% |
| Gradient Boosting | 99.1% | 99.0% | 99.2% | 99.1% |
| Random Forest | 98.8% | 98.7% | 98.9% | 98.8% |

---

## 📝 How to Use

### Basic Usage

```python
# Load the notebook and run all cells

# Option 1: Test with example
example_news = "WASHINGTON (Reuters) - The Federal Reserve raised interest rates today..."
manual_testing(example_news)

# Option 2: Input your own news
news = input("Paste your news article: ")
manual_testing(news)
```

### Advanced Usage (With Free Fact-Checking)

```python
# Run the improved detector
test_news = input("Paste your news: ")
smart_fake_news_detector(test_news)
```

---

## 🧪 Test Examples

Try these examples to test the detector:

**Real News:**
