# File Summarization Using Flan-T5 Model

This project implements an abstractive text summarization system using the **Flan-T5 model** to generate concise summaries from large documents. The system takes long-form text (from various file formats such as PDF, DOCX, TXT, etc.) and provides a short, meaningful summary. Additionally, it offers a feature to **translate the summary into three different languages** (English, Hindi, Kannada) based on user choice.

## Features

- Abstractive summarization of long documents using the Flan-T5 model.
- Supports multiple file formats: TXT, PDF, DOCX, etc.
- User-friendly interface for uploading files and receiving summaries.
- Translates the generated summary into **English**, **Hindi**, and **Kannada**, based on user selection.
- Optimized for fast and efficient processing.
  
## Prerequisites

Before running the project, ensure that you have the following software installed:

- **Python 3.x** (preferably Python 3.7+)
- **PyTorch** or **TensorFlow** (depending on the version of the model you choose to use)
- **Hugging Face Transformers** library
- **Streamlit** (for the web interface)

To install the necessary dependencies, use the following:

```bash
pip install transformers torch streamlit googletrans==4.0.0-rc1
