# Prodigy Task 1 – GPT-2 Text Generation Pipeline

## Overview

This project demonstrates the use of Hugging Face's Transformers library to build a text generation pipeline using the GPT-2 language model. It involves the use of custom datasets, tokenizer configuration, and inference through a pre-trained model.

## Contents

- `prodigytask1.ipynb`: Jupyter Notebook that includes the entire implementation of the pipeline.
- Sample usage of:
  - `GPT2Tokenizer`
  - `GPT2LMHeadModel`
  - `pipeline` from `transformers`
- Dataset preprocessing and model loading steps.

## Dependencies

Make sure you have Python 3.7+ installed, then install the required packages:


pip install transformers datasets pandas
If using Jupyter Notebook:


pip install notebook
How to Run
Clone this repository or download the notebook:

git clone https://github.com/your-username/prodigy-gpt2-task.git
cd prodigy-gpt2-task
Start Jupyter Notebook:


jupyter notebook prodigytask1.ipynb
Execute each cell in the notebook to replicate the full workflow.

Features
🧠 Model: Uses GPT2LMHeadModel from Hugging Face for text generation tasks.

📝 Tokenizer: Loads and uses GPT-2 tokenizer for input encoding.

📦 Dataset: Utilizes the Hugging Face datasets library to create or manipulate custom datasets.

🔁 Inference Pipeline: Uses the pipeline API for fast and easy text generation.

📊 Exploratory Code: Contains code for debugging, generating text, and managing input/output streams.

Example Snippet

from transformers import pipeline

generator = pipeline("text-generation", model="gpt2")
generator("The future of AI is", max_length=50, num_return_sequences=1)
Author
RAKESH KUMAR KANNEKANTI

LinkedIn Profile:https://www.linkedin.com/in/rakesh-kumar-kannekanti-1aab70290/

Email: 

License
This project is licensed under the MIT License. See the LICENSE file for details.



