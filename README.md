# NLP Toxicity Classification & Detoxification Research

## Project Overview
This project focuses on identifying and mitigating toxic content in social media datasets (Twitter/X). It involves building a robust classification pipeline to detect harmful language and exploring generative approaches to "detoxify" text while maintaining its original meaning.

## Key Features
* **Data Engineering:** Preprocessing and cleaning of a multi-language dataset, with a focus on filtering and tokenizing French and English text.
* **Classification:** Training a Machine Learning model to categorize tweets based on their toxicity levels (Hate Speech, Offensive, or Neutral).
* **Detoxification Research:** Implementation of experimental sequence-to-sequence (Seq2Seq) models aimed at rewriting toxic inputs into neutral versions.
* **Performance Analysis:** Comprehensive evaluation of classification metrics and an honest assessment of the challenges involved in generative detoxification tasks.

## Tech Stack
* **Language:** Python
* **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib (and any others used in your notebook like NLTK, Spacy or TensorFlow).
* **Environment:** Jupyter Notebook

## How to use
1. Clone the repository: `git clone https://github.com/maxoum-shi7su/toxicity-classification.git`
2. Install dependencies: `pip install -r requirements.txt` (if applicable)
3. Open `toxicity-classification.ipynb` to see the full data analysis and model training pipeline.

## Results & Limitations
The classification model achieved high accuracy in detecting toxic content. However, the detoxification task highlighted the complexity of preserving semantic nuance in short-form text like tweets, providing valuable insights into the limitations of current generative architectures for this specific use case.
