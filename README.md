 Topic Modeling in NLP

This project demonstrates unsupervised topic modeling techniques in Natural Language Processing using Python and Jupyter Notebook. It explores techniques like **LDA (Latent Dirichlet Allocation)** and **NMF (Non-negative Matrix Factorization)** on a custom or public dataset.

---

📝 Project Features

- Text preprocessing (cleaning, tokenizing, stopwords removal, lemmatization)
- Feature extraction using TF-IDF and CountVectorizer
- Topic modeling using:
  - Latent Dirichlet Allocation (LDA)
  - Non-negative Matrix Factorization (NMF)
- Visualization of topics using:
  - Word clouds
  - pyLDAvis (if used)

---

 📁 Folder Structure

📦TopicModelling
┣ 📄Topic_Modeling.ipynb
┣ 📄requirements.txt
┗ 📄README.md

yaml
Copy
Edit

---

Installation & Requirements

Make sure Python is installed. Install required libraries:


pip install -r requirements.txt

Or manually install:

pip install numpy pandas scikit-learn nltk matplotlib seaborn gensim pyLDAvis wordcloud
🚀 How to Run the Project
Clone the repository:
git clone https://github.com/arjun-selson/TopicModelling.git
cd TopicModelling
Open the notebook:

jupyter notebook Topic_Modeling.ipynb
Run the cells to see preprocessing, modeling, and visualizations.
