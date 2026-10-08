# Multiclass Emotion Classifier using RoBERTa

A fine-tuned **RoBERTa-base** model for multiclass emotion classification from text. The model classifies text into six emotion categories: **sadness, joy, love, anger, fear, and surprise**.

The project covers data preprocessing, tokenization, model fine-tuning, evaluation, visualization, and model export for future reuse.

## 🎯 Emotions

The model classifies text into:

* 😢 Sadness
* 😊 Joy
* ❤️ Love
* 😠 Anger
* 😨 Fear
* 😮 Surprise

## ✨ Features

* Fine-tuning of RoBERTa-base
* Text preprocessing and cleaning
* RoBERTa tokenization
* Multiclass emotion classification
* Model training using Hugging Face Trainer
* Evaluation using classification reports
* Confusion matrix visualization
* Demo predictions
* Saved model and tokenizer for reuse

## 🛠️ Tech Stack

* Python
* PyTorch
* Hugging Face Transformers
* Hugging Face Datasets
* scikit-learn
* Matplotlib
* Seaborn
* Google Colab

## 🚀 Training

The model can be trained using **Google Colab with GPU acceleration**.

### Install Dependencies

```bash
pip install -q transformers datasets accelerate evaluate scikit-learn seaborn
```

### Training Process

The training pipeline includes:

1. Load and clean the dataset
2. Tokenize text using the RoBERTa tokenizer
3. Fine-tune the RoBERTa model
4. Evaluate model performance
5. Generate classification reports and confusion matrices
6. Save the trained model and tokenizer

## 💻 Google Colab

For faster training, a GPU runtime such as **NVIDIA T4** can be used in Google Colab.

Go to:

**Runtime → Change runtime type → GPU**

Training time depends on the dataset size, batch size, number of epochs, and available GPU.

## 📦 Model Export

After training, the best model and tokenizer are saved in:

```text
roberta_emotion_best/
```

The exported model can be downloaded and reused without training the model again.

## 📊 Evaluation

The project includes:

* Classification reports
* Confusion matrices
* Model predictions
* Evaluation metrics

These help analyze how well the model performs across the six emotion categories.

## 🎯 Project Goal

The goal of this project is to explore **Natural Language Processing (NLP)** and **Transformer-based models** for emotion detection from text.

It demonstrates practical experience with:

* NLP
* Transfer Learning
* Transformer Models
* Text Classification
* Model Evaluation
* Hugging Face ecosystem

## 👨‍💻 Author

**Malik Asad**

Computer Science Graduate | Web Developer | AI Enthusiast

* LinkedIn: [linkedin.com/in/malikasad7](https://www.linkedin.com/in/malikasad7/)
* GitHub: [github.com/malikasad7ya](https://github.com/malikasad7)
