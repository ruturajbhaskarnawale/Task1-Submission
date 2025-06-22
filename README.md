# Task 1: Text Tokenization and Encoding

## Overview
This repository contains the implementation of Task 1 for the Data Science Internship, focusing on text tokenization and encoding using a pre-trained BERT model. The task involves processing a sample text, generating tokenized inputs and embeddings, and saving the results for further analysis.

## Objective
- Tokenize a given text using the BERT-base-uncased model.
- Encode the tokenized text into embeddings.
- Save the tokenized inputs and embeddings as files.
- Verify the process and document the results.

## Files
### Main Files
- `task1.ipynb`: Jupyter Notebook containing the complete code for tokenization, encoding, and file saving. Includes step-by-step execution with outputs.
- `requirements.txt`: List of Python package dependencies and their versions required to run the notebook.
- `report4.txt`: Detailed report summarizing the task objectives, methodology, results, challenges, and next steps.

### Output Files
- `outputs/task1_inputs.pt`: Saved PyTorch tensor containing tokenized inputs (input IDs, attention mask, token type IDs).
- `outputs/task1_embeddings.pt`: Saved PyTorch tensor containing the BERT embeddings.
- `outputs/task1_summary.txt`: Text file summarizing the input text, tokenized IDs, decoded tokens, and embeddings shape.

## Setup Instructions
To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Task1-Submission.git
   cd Task1-Submission/Task1
