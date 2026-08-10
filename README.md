# multiclass-emotion-classifier-using-Roberta-
Fine-tuned RoBERTa-base for multiclass emotion detection from text. Classifies sentences into six emotions: sadness, joy, love, anger, fear, and surprise. Includes preprocessing, training, evaluation with reports &amp; confusion matrices, demo predictions, and saved model for reuse.
🚀 Training on Google Colab

Open Colab: Google Colab

Enable GPU:

Go to Runtime > Change runtime type

Select GPU → T4 (recommended, free on Colab)

Install dependencies (first cell in notebook):

!pip install -q transformers datasets accelerate evaluate scikit-learn seaborn


Run the provided script step by step. It will:

Load and clean the dataset

Tokenize text with RoBERTa tokenizer

Fine-tune the model with Hugging Face Trainer

Evaluate and generate reports/plots

Save the best model & tokenizer in roberta_emotion_best/

⏳ Training Time Estimate

Using NVIDIA T4 GPU on Colab Free Tier: ~15–25 minutes for 6 epochs (depends on batch size & dataset size).

With Colab Pro (faster GPUs like P100/V100): ~8–15 minutes.

🛠️ Tech Stack

Python, PyTorch

Hugging Face Transformers & Datasets

scikit-learn, seaborn, matplotlib

📦 Model Export

After training, the fine-tuned model and tokenizer are saved in:

roberta_emotion_best/


This can be zipped and downloaded for reuse without retraining.
