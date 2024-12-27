# TaxCraft-CodeRanges

# TaxCraft - Machine Learning-Powered Automated Tax Assistant

## Overview
TaxCraft is an innovative web application designed to automate and personalize tax advisory services using machine learning. It analyzes users' financial data to provide tailored tax-saving strategies, leveraging advanced technologies in natural language processing and machine learning.

## Problem Statement
In a complex tax environment with frequently changing laws and numerous possibilities for deductions, many individuals find it difficult to optimize their tax returns. TaxCraft aims to simplify this process by providing personalized, actionable tax advice.

## Features
- **Personalized Tax Deduction Advice**: Automated suggestions based on user's financial and tax data.
- **Advanced Document Analysis**: Uses OCR and machine learning to process tax documents and extract relevant information.
- **Real-time Assistance**: Incorporates a chatbot for immediate response to user queries.
- **User-Friendly Interface**: Developed using Streamlit for ease of use and efficient navigation.

## Tech Stack
- **Frontend**: Streamlit
- **Backend**: FastAPI
- **Database**: Firebase for user data storage and Chromadb vector database for document processing.
- **NLP/ML Tools**: LangChain, Gemini API, RAG, Tesseract OCR

## Installation
Clone the repository and set up the local development environment:
```bash
git clone https://github.com/your-github-username/taxcraft
cd taxcraft
pip install -r requirements.txt
```

### Running the code:
```text
streamlit run app.py
streamlit run login.py
```
