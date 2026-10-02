

Trust AI is an AI-powered ethical auditing platform designed to identify potential bias, privacy risks, security vulnerabilities, and compliance concerns in datasets and documents. Built with React and FastAPI, it uses a multi-agent AI architecture and Retrieval-Augmented Generation (RAG) to analyze data, explain potential risks, and generate structured audit reports.


Key Features:
Bias Detection: Identify potential bias and unfair representation in datasets.
Privacy Risk Assessment: Detect sensitive information such as dates of birth, addresses, and banking details.
Security Analysis: Identify potential security and data-handling risks.
Explainable AI (XAI): Provide understandable explanations of audit findings.
RAG-Based Compliance: Retrieve relevant information to support compliance analysis.
Multi-Agent Architecture: Coordinate specialized agents for different audit tasks.
Automated Audit Reports: Consolidate findings into structured reports with risk summaries and recommendations.
CSV and PDF Support: Analyze data from supported CSV files and PDF documents.
System Architecture

Trust AI follows a modular client-server architecture:

React Frontend — File uploads and audit result visualization.
FastAPI Backend — Handles API requests and coordinates the audit workflow.
AI Controller — Orchestrates specialized agents.
Specialized AI Agents — Analyze bias, privacy, security, explainability, and compliance.
RAG Component — Retrieves relevant information for compliance analysis.
Report Generation — Combines findings into a consolidated audit report.
Technology Stack
Category	Technologies
Frontend	React, JavaScript, HTML, CSS
Backend	Python, FastAPI
AI Architecture	Multi-Agent Systems
Retrieval	Retrieval-Augmented Generation (RAG)
Explainability	Explainable AI (XAI)
Data Processing	CSV, PDF
API	REST APIs
How It Works
Upload a supported CSV dataset or PDF document.
The frontend sends the input to the FastAPI backend.
The AI controller coordinates the relevant agents.
The agents analyze potential risks and compliance concerns.
Findings are consolidated into an audit report.
Review risk indicators, explanations, and recommendations.
Getting Started
Prerequisites
Python 3.10+
Node.js and npm
Git
Clone the Repository
git clone YOUR_REPOSITORY_URL
cd YOUR_PROJECT_FOLDER
Backend Setup
cd backend
python -m venv venv

Activate the virtual environment on Windows:

.\venv\Scripts\Activate.ps1

Install dependencies and start the backend:

pip install -r requirements.txt
uvicorn main:app --reload
Frontend Setup

Open a separate terminal:

cd frontend
npm install
npm run dev

Open the local URL displayed by the frontend development server.

Note: The commands assume separate frontend and backend directories and a FastAPI entry point named main.py. Adjust them if your repository uses a different structure.

Use Cases
Ethical AI auditing
Dataset bias and fairness analysis
Privacy risk identification
Security risk assessment
Compliance research
Explainable AI workflows

Trust AI supports human review and does not replace professional security, legal, or regulatory assessments.

Future Enhancements
Support additional file formats.
Improve bias detection and evaluation.
Add authentication and audit history.
Expand compliance reference sources.
Add automated testing and CI/CD.
Deploy the frontend and backend for public access.
Skills Demonstrated

React · Python · FastAPI · REST API Development · AI Agents · Multi-Agent Architecture · Retrieval-Augmented Generation (RAG) · Explainable AI · Data Processing · Software Architecture · Git · GitHub

Author

Ghanta Sai Neeraj.

If you find Trust AI useful, please give this repository a ⭐ star. Your support is appreciated!
