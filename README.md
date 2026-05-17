# News Article Classification using TF-IDF and Naive Bayes

This project is an Information Retrieval (IR) and Text Classification system built using Python and Machine Learning techniques.

The model classifies news articles into different categories using:

- Text preprocessing
- TF-IDF Vectorization
- Multinomial Naive Bayes
- Performance Evaluation Metrics

---

## Dataset

The project uses the **20 Newsgroups Dataset** provided by Scikit-learn.

It contains thousands of news articles divided into multiple categories.

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

---

## Project Steps

### 1. Load Dataset
The dataset is loaded using:

```python
fetch_20newsgroups()
```

---

### 2. Text Preprocessing

The text is cleaned by:

- Converting text to lowercase
- Removing punctuation
- Removing stopwords

---

### 3. Train-Test Split

The dataset is divided into:

- Training Set
- Testing Set

---

### 4. Feature Extraction using TF-IDF

TF-IDF converts text into numerical vectors.

```python
TfidfVectorizer()
```

---

### 5. Model Training

The classification model used:

- Multinomial Naive Bayes

```python
MultinomialNB()
```

---

### 6. Model Evaluation

The following metrics are used:

- Accuracy
- Precision
- Recall
- F1-Score

The project also visualizes:

- Confusion Matrix
- F1 Score per Class
- Overall Metrics

---

## Example Output

The model predicts the category of random news articles and compares:

- True Category
- Predicted Category

---

## How to Run

### Install Requirements

```bash
pip install pandas numpy nltk scikit-learn matplotlib seaborn
```

### Run the Notebook

Open the notebook using Jupyter Notebook or VS Code.

---

## Project Structure

```bash
├── IR_Project.ipynb
├── README.md
```

---

## Author

Abdulrahman Wahba
Faculty of Computers and Information
