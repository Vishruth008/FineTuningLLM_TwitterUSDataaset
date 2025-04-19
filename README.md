# Fine-Tuning DistilBERT for Twitter Airline Sentiment Classification

This project fine-tunes a pretrained DistilBERT model on the Twitter US Airline Sentiment dataset using Hugging Face’s `transformers` and `datasets` libraries. It classifies tweets as **positive**, **neutral**, or **negative**, demonstrating the effectiveness of transfer learning for short-text sentiment classification.

---

## 📂 Project Structure

- `Twitter_Final_Documented.ipynb` – Full annotated notebook
- `train.csv`, `val.csv`, `test.csv` – Cleaned and stratified splits
- `requirements.txt` – Dependencies
- `final-model/` – (optional) saved model directory

---

## ⚙️ Setup Instructions

1. **Clone the repository** or upload files to Google Colab
2. **Install dependencies** (in Colab):
   ```bash
   !pip install transformers datasets evaluate scikit-learn pandas matplotlib
