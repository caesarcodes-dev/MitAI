# Multi Agent HR Recruitment System

A multi-agent AI solution designed to rank candidates fairly and efficiently based on skills and location, while generating dynamic interview questions and providing a modern dashboard for recruiters.

---

## 🚀 Overview

This project implements an intelligent HR recruitment assistant that processes locally stored CVs, extracts skills, ranks candidates by relevance and location, and suggests interview questions tailored to job roles. The system uses a multi-agent architecture combining ranking, planning, and memory agents, wrapped in a clean and modern Streamlit UI. Bias-awareness and scalability are core design goals.

---

## 🔑 Core Features

- Multi-agent system for candidate ranking and skill validation  
- Fair and bias-aware candidate evaluation, including location normalization  
- Dynamic interview question generation based on job and skill context  
- Intuitive, modern dashboard for recruiters with real-time analytics  
- Efficient processing of local CV documents with memory persistence  
- Scalable design to handle growing candidate pools without crashing

---

## 🛠️ Tech Stack

- Python 3.8+  
- Streamlit for frontend UI  
- PyTorch and Sentence Transformers for skill extraction and embeddings  
- SQLite for memory and data persistence  
- Plotly for interactive analytics  
- Llama3 model (locally hosted or integrated as API) for language understanding

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/caesarcodes-dev/MitAI.git
cd MitAI
```
Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
Install dependencies:

```bash
pip install -r requirements.txt
```
⚙️ Usage
Run the Streamlit app:

```bash
streamlit run main.py
Open the displayed local URL 
```
Upload your CVs into the docs/ folder. Use the dashboard to create job searches, rank candidates, and view analytics.

🙌 Contribution
Feel free to fork, open issues, or submit pull requests to improve functionality, add features, or fix bugs.

⚠️ Disclaimer
This system processes only locally stored CVs and does not scrape web data. It is designed for internal HR use and focuses on fairness and bias mitigation in candidate ranking.

Contact
For questions or collaboration, please open an issue or contact the repository owner.


