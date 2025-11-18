# Fake News Detection using Machine Learning

This repository contains a complete Fake News Detection system built using **Machine Learning**.  
The goal is to classify news articles as **Fake** or **Real** based on their textual content.

The project is implemented in a **Jupyter Notebook** and uses two datasets: `fake.zip` and `true.zip`.

---

## Dataset

The project uses two compressed datasets:

### **`fake.zip`**
Contains text files of fake news articles.

### **`true.zip`**
Contains text files of real and verified news articles.

Each ZIP file includes multiple `.txt` files, each representing a single news article.  
The notebook extracts, loads, and processes these files to build the dataset.

Place the dataset files in the root directory of the project:

```
Fake_News_Detection.ipynb
fake.zip
true.zip
```

---

## Features

- Load and extract text dataset from ZIP archives  
- Clean and preprocess text  
- Convert text into numerical features using **TF-IDF**  
- Train a **PassiveAggressiveClassifier**  
- Evaluate accuracy and model performance  
- Manually test custom user input  

---

## Repository Structure

```
📦 Fake-News-Detection
│
├── Fake_News_Detection.ipynb     # Main notebook
├── fake.zip                      # Fake news dataset
├── true.zip                      # Real news dataset
└── README.md                     # Project documentation
```

---


##  Installation

### 1. Clone the repository

```bash
git clone https://github.com/SAHELBouchra/Fake_news_detection.git
cd Fake_news_detection
```

### 2. Install dependencies

Install required Python libraries manually:

```
pandas
numpy
scikit-learn
nltk
```


##  Running the Notebook

1. Ensure `fake.zip` and `true.zip` are in the same directory as the notebook  
2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open:

```
Fake_News_Detection.ipynb
```

4. Run all cells sequentially

---

## Manual Testing

Use the following function to classify your own text:

```python
manual_testing("Write your news text here...")
```

It outputs:

- **Fake News**  
- **Not A Fake News**

---

## Model Performance

The model achieves strong accuracy on the dataset.  
All evaluation metrics are available in the notebook.


