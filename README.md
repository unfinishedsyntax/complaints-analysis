# 📢 Customer Complaints Analysis (LLM)

## Overview
This Streamlit app generates **synthetic customer complaints** and uses a Hugging Face **Zero-Shot Classifier** to categorize them into:
- Delay
- Rude Behavior
- Pricing Issue
- Service Quality

## Features
- Auto-generated dataset (no need to upload data).
- Hugging Face transformer for complaint categorization.
- Bar chart of complaint distribution.
- Word cloud for each complaint category.
- Interactive complaints table.

## Run Locally
```bash
pip install -r requirements.txt
streamlit run app_complaints.py
```

## Deployment
- Deploy directly to [Streamlit Cloud](https://streamlit.io/cloud) or [Hugging Face Spaces](https://huggingface.co/spaces).