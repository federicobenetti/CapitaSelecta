# Capita Selecta – Text Analysis & Topic Modeling

This project explores **web scraping, natural language processing, and topic modeling** on Italian text.  
It uses **Python**, **spaCy**, **scikit-learn**, and **LDA** to extract, clean, and analyze text data.  

## 📌 Features

- Web scraping with [`requests-html`](https://requests-html.kennethreitz.org/)  
- Text preprocessing (stopword removal, tokenization, lemmatization)  
- Topic modeling using **Latent Dirichlet Allocation (LDA)**  
- Interactive visualization with **pyLDAvis**  
- Data exploration with **pandas**, **matplotlib**, and **seaborn**

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/capita-selecta.git
cd capita-selecta
```

Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # on Mac/Linux
venv\Scripts\activate      # on Windows
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

Open the Jupyter notebook:

```bash
jupyter notebook Capita_Selecta_Federico_Benetti.ipynb
```

Run the cells step by step to:
1. Scrape Italian text data  
2. Clean and preprocess text  
3. Apply LDA topic modeling  
4. Visualize insights  

## 📊 Example Output

- Distribution of topics across documents  
- Interactive LDA visualization via **pyLDAvis**  
- Word clouds & keyword frequency plots  

## 📂 Repository Structure

```
├── Capita_Selecta_Federico_Benetti.ipynb   # Main analysis notebook
├── requirements.txt                        # Python dependencies
├── README.md                               # Project description
├── .gitignore                              # Ignore unnecessary files
├── data/                                   # (Optional) Store scraped/cleaned data
└── results/                                # (Optional) Save plots and models
```

