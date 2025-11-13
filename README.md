# Jigsaw Toxicity Classification — Simple Reproduction Project

## 🚀 Project Overview
This project is a competition study based on the Jigsaw Toxicity Classification competition on Kaggle, focusing on NLP and LLM fine-tuning.
My goal is to reproduce a top-10 score from the past competition.

## 🛠️ Tech Stack
| Category | Tools |
|-----------|--------|
| Language | Python 3 |
| Framework | PyTorch, Hugging Face Transformers |
| Data | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Experiment Tracking | Weights & Biases (W&B) |
| Environment | Jupyter Notebook / Colab / Kaggle |

## 🧩 System Architecture
Here is a simple diagram of how the system works:

          +------------------------+
          |  Raw Text Data         |
          +-----------+------------+
                      |
                      v
          +------------------------+
          |  Preprocessing         |
          | (clean, tokenize text) |
          +-----------+------------+
                      |
                      v
          +------------------------+
          | Transformer Model      |
          | (BERT / RoBERTa etc.)  |
          +-----------+------------+
                      |
                      v
          +------------------------+
          | Fine-tuning & Testing  |
          +-----------+------------+
                      |
                      v
          +------------------------+
          |  Inference / Scoring   |
          +------------------------+

## 🎨 Demo / Results


