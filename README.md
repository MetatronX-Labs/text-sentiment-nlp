# text-sentiment-nlp

Sentiment analysis using LSTM and Transformer models on real-world text data.

## 💡 Overview

This project performs sentiment classification (positive, negative, neutral) using deep learning models. It's built as part of the MetatronX open-source AI initiative.

You can:
- Train and evaluate an LSTM-based model
- Optionally use a Transformer (BERT) model
- Visualize training accuracy, F1-score, confusion matrix
- Extend to your own dataset or finetune on domain-specific corpora

## 🔧 Stack

- Python 3.10+
- TensorFlow / Keras or PyTorch
- Numpy, Pandas
- Matplotlib / Seaborn
- scikit-learn
- Hugging Face Transformers (optional)

## 📁 Directory Structure

<pre> ``` data/ # Raw & processed text files notebooks/ # Colab/Jupyter training notebooks src/ ├── data_loader.py ├── model_lstm.py ├── model_transformer.py ├── train.py ├── evaluate.py test_run.py # Runs full pipeline ``` ## 🚀 Quick Start To run training on the built-in dataset: ```bash pip install -r requirements.txt python test_run.py ``` ## 📜 License [MIT](LICENSE) --- ## 🤖 Part of the MetatronX-Labs Open Source AI Stack </pre>
