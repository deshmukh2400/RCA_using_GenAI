# RCA_Using_GenAI

## Overview
A Flask-based prototype that uses Azure OpenAI (GPT) to perform Root Cause Analysis (RCA) on IT alerts.

## Project Structure
- **backend/**: Flask app and GenAI integration
- **frontend/**: Static HTML/CSS and D3.js for visualizing dependencies and RCA output
- **requirements.txt**: Python dependencies

## Usage
1. Set your Azure OpenAI environment variables:
   ```bash
   export AZURE_OPENAI_ENDPOINT="https://<your-resource>.openai.azure.com/"
   export AZURE_OPENAI_KEY="<your-key>"
   export AZURE_DEPLOYMENT_NAME="gpt-35-turbo"
   
2.	Install dependencies:
   ```bash
   pip install -r requirements.txt

3.	Run the server:
   ```bash
   python backend/main.py

4.	Open your browser at http://localhost:5000.