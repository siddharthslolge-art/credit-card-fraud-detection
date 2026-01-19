# Real-Time Credit Card Fraud Detection System

## Overview
This project is an end-to-end machine learning system that detects fraudulent credit card transactions in real time.  
It preprocesses transaction data, handles categorical and numerical features, and serves predictions through a FastAPI-based web application.

## Features
- Machine learning model trained on transaction data
- Handles class imbalance in fraud detection
- Categorical feature encoding
- Real-time fraud prediction
- Simple web interface for easy use
- REST API for programmatic access

## Tech Stack
- Python
- Scikit-learn
- FastAPI
- Pandas
- Jinja2
- HTML

## How It Works
1. User enters transaction details via a web form
2. Data is preprocessed and encoded
3. Trained ML model predicts fraud probability
4. System returns:
   - Fraud probability
   - Final decision (FRAUD / SAFE)

## How to Run Locally

```bash
pip install -r requirements.txt
uvicorn app:app --reload
