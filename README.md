# Healthcare Recommendation System

## Project Description
This project implements a healthcare recommendation system that processes patient data to suggest personalized treatment plans. It leverages:

- **PySpark** for large-scale data processing of patient records  
- **TensorFlow LLM API** for summarizing patient histories and generating treatment recommendations  
- **Firebase** for managing patient interactions and appointment tracking  
- **Kubernetes** for cloud-native deployment with multi-cloud support  

## Repository Structure

- `/pyspark/` — PySpark scripts for patient data processing  
- `/tensorflow/` — TensorFlow LLM API integration code  
- `/firebase/` — Firebase setup files including Firestore rules and cloud functions  
- `/deployment/` — Kubernetes and cloud deployment configuration files  
- `app.py` — Main Flask API application for treatment recommendations  
- `requirements.txt` — Python dependencies  

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd <repo-folder>
   2. Install Python dependencies:
   pip install -r requirements.txt
3. Configure Firebase credentials:

Replace placeholders in firebase/config.json with your Firebase project details

4. Run the Flask API locally

**Live Demo**
The API is deployed and accessible at:
https://b0be-34-168-6-39.ngrok-free.app/

Visiting the base URL will return:
