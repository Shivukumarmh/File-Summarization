# File Summarization using Flan-T5

## Overview

This repository provides an abstractive summarization system using the **Flan-T5** model. The system is designed to summarize large documents into concise and meaningful summaries. It supports various file formats and leverages the power of **transformer-based models** for high-quality text summarization.

## Features

- Supports multiple file formats including **TXT, PDF, and DOCX**.
- Utilizes the **Flan-T5 model** for abstractive summarization.
- Efficiently processes large documents to extract key information.
- Provides an easy-to-use command-line interface.
- Optionally includes a **Streamlit-based web interface** for user-friendly interaction.

## Installation

Ensure that you have **Python 3.8+** installed. Then, install the required dependencies using the following command:

```bash
pip install -r requirements.txt
transformers
torch
sentencepiece
streamlit
pypdf
python-docx
