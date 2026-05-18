# AI IAM Access Governance Copilot

An enterprise-style AI-powered Identity and Access Management (IAM) governance platform that automates access reviews, detects risky user behavior, generates AI-driven security recommendations, and simulates real-world identity governance workflows using Large Language Models (LLMs), anomaly detection, semantic search, and real-time dashboards.

---

# Project Overview

This project simulates modern enterprise IAM and cybersecurity governance systems used by organizations to monitor employee access, identify security risks, and automate governance workflows.

The platform combines:
- AI-powered access risk analysis
- Identity governance workflows
- Privileged access monitoring
- Security anomaly detection
- Semantic vector search
- AI security copilot recommendations
- Real-time governance dashboards

The project is inspired by enterprise IAM platforms such as:
- SailPoint
- CyberArk
- Okta
- Ping Identity

---

# Key Features

## AI-Powered Security Copilot
Uses LLM-based prompt engineering to:
- Analyze employee access profiles
- Explain security risks
- Generate remediation recommendations
- Automate access review workflows

---

## IAM Risk Scoring Engine
Calculates employee risk levels based on:
- Failed login attempts
- Privileged/admin access
- Sensitive system exposure
- Geographic login risk

Risk Levels:
- LOW
- MEDIUM
- HIGH

---

## Security Anomaly Detection
Implements machine learning-based anomaly detection for:
- Suspicious authentication behavior
- Abnormal login activity
- Potential account compromise
- Privilege escalation indicators

Uses:
- Isolation Forest
- Behavioral analytics workflows

---

## Semantic Vector Search
Implements AI-powered semantic search using vector embeddings.

Features:
- Similar user access search
- Security incident similarity retrieval
- Governance intelligence workflows
- RAG-style security search foundation

---

## Real-Time Governance Dashboard
Interactive Streamlit dashboard for:
- Employee risk monitoring
- AI-generated governance reviews
- Risk distribution visualization
- Security analytics

---

# Architecture

```text
Employee Access Data
          ↓
IAM Risk Scoring Engine
          ↓
LLM Security Copilot
          ↓
AI Governance Recommendations
          ↓
Anomaly Detection Engine
          ↓
Semantic Vector Search
          ↓
Real-Time Dashboard
```

---

# Tech Stack

## Languages & Frameworks
- Python
- Streamlit
- Pandas
- NumPy

---

## AI & Machine Learning
- Hugging Face Transformers
- FLAN-T5
- Sentence Transformers
- Scikit-learn
- Prompt Engineering
- NLP

---

## Cybersecurity & IAM Concepts
- Identity & Access Management (IAM)
- OAuth 2.0 Concepts
- Single Sign-On (SSO)
- Role-Based Access Control (RBAC)
- Privileged Access Governance
- Security Analytics

---

## Vector & Semantic Search
- Embeddings
- Semantic Similarity
- Vector Search
- RAG Foundations

---

# Project Workflow

## 1. Employee Access Data Ingestion

The platform processes employee identity and access data including:
- Roles
- Login activity
- Privileged access
- Sensitive system permissions
- VPN access
- Location risk

Example:

```text
Employee: Sarah
Role: Admin
Failed Logins: 18
Sensitive Access: True
Location Risk: HIGH
```

---

## 2. IAM Risk Analysis

The system calculates risk scores using enterprise-style governance logic.

Factors include:
- Excessive failed logins
- Administrative privileges
- High-risk access patterns
- Sensitive system exposure

Example Output:

```text
Risk Level: HIGH
```

---

## 3. AI Governance Review

The LLM security copilot generates:
- Risk explanations
- Security concerns
- Recommended remediation actions

Example Output:

```text
Risk Explanation:
The employee has excessive failed login attempts and privileged admin access.

Security Concern:
Potential account compromise or unauthorized privileged activity.

Recommended Action:
Require MFA verification and temporarily review account permissions.
```

---

## 4. Security Anomaly Detection

The anomaly detection engine identifies abnormal user behavior such as:
- Unusual login activity
- Potential insider threats
- Suspicious authentication patterns

---

## 5. Semantic Governance Search

Vector embeddings enable semantic similarity search for:
- Similar user access profiles
- Related governance incidents
- Security intelligence retrieval

---

## 6. Governance Dashboard

Interactive visual dashboards display:
- Risk distributions
- High-risk employees
- AI-generated governance reviews
- Security analytics

---

# Folder Structure

```text
AI-IAM-Access-Governance-Copilot/
│
├── data/
│   └── iam_users.csv
│
├── notebooks/
│   └── AI_IAM_Governance_Copilot.ipynb
│
├── app/
│   └── streamlit_app.py
│
├── screenshots/
│
├── requirements.txt
│
└── README.md
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/AI-IAM-Access-Governance-Copilot.git
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Project

## Google Colab

Open:

```text
notebooks/AI_IAM_Governance_Copilot.ipynb
```

Run all notebook cells sequentially.

---

## Streamlit Dashboard

```bash
streamlit run app/streamlit_app.py
```

---

# Sample Use Cases

- IAM governance automation
- Security access reviews
- Privileged access monitoring
- AI-assisted cybersecurity workflows
- Enterprise identity governance
- Security analytics platforms
- Governance intelligence systems

---

# Future Enhancements

- LangChain multi-agent governance workflows
- RAG-based IAM knowledge retrieval
- FastAPI deployment
- Real-time Kafka event streaming
- OpenAI API integration
- SIEM integration simulation
- MFA workflow simulation
- Access approval automation
- Enterprise audit logging

---

# Learning Outcomes

This project demonstrates:
- AI automation engineering
- LLM application development
- Prompt engineering
- IAM governance workflows
- Security analytics
- Anomaly detection systems
- Vector embeddings & semantic search
- Enterprise cybersecurity architecture thinking

---

# Resume Impact

This project was designed to simulate enterprise-grade IAM and AI cybersecurity automation systems commonly used in:
- Identity Governance Platforms
- Security Operations Centers (SOC)
- Access Governance Teams
- Cybersecurity Analytics Environments
- AI-assisted Security Automation Systems

---

# Author

Vaishnavi Surnilla

MS Information Technology  
University of Cincinnati

---
