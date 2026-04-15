🇮🇳 SAARANSH – E-Consultation Sentiment Analysis Platform
AI-Powered Citizen Feedback Intelligence for Government Policies

🚀 Developed for India Innovates 2026 – World’s Largest Civic Tech Hackathon

📌 Overview

SAARANSH is an AI-powered platform designed to automatically analyze large volumes of citizen feedback submitted during government policy consultations.

Government ministries often receive thousands of public comments on draft policies through e-consultation portals. These submissions are typically unstructured, multilingual, and time-consuming to analyze manually.

SAARANSH transforms this overwhelming data into structured, actionable insights using advanced Natural Language Processing (NLP) and ensemble AI models.

The platform enables policymakers to:

Understand public sentiment quickly
Identify key policy concerns
Detect trending topics
Generate summarized reports for decision-making

Our system reduces manual review time by over 80% while ensuring 100% feedback coverage.

🏆 Hackathon

This project was developed for:

India Innovates 2026 – World’s Largest Civic Tech Hackathon

📍 Venue: Bharat Mandapam, New Delhi
📅 Date: 28 March 2026

The hackathon focuses on building technology-driven solutions for governance, democracy, and public systems.

SAARANSH fits within the Digital Democracy / Civic Tech domain, aiming to improve how governments interpret and respond to citizen feedback.

🎯 Problem Statement

Modern digital governance encourages public participation in policy making, but governments face a major challenge:

Thousands of citizen responses are submitted during consultations, making it extremely difficult to manually analyze them.

Key challenges include:

Massive volume of public feedback
Unstructured text data
Multilingual comments (English + Indian languages)
Mixed formats (text, PDFs, scanned documents)
Long review time per comment

Officials may spend 15–20 minutes reviewing a single comment, leading to massive productivity losses.

SAARANSH solves this problem using AI-driven automated analysis.

💡 Solution

SAARANSH is a multi-stage NLP pipeline that automatically processes citizen comments and generates insights for policymakers.

The system performs:

✔ Sentiment analysis
✔ Topic clustering
✔ Keyword extraction
✔ Policy insight generation
✔ Automatic summarization

It transforms raw feedback → actionable intelligence for government decision makers.

🧠 Core Features
📊 Automated Sentiment Analysis

Classifies citizen comments into:

Positive
Neutral
Negative

With confidence scores for reliability.

🌍 Multilingual Processing

Handles code-mixed Indian languages including:

English
Hindi
Regional languages

Using specialized language models.

🧾 Policy Feedback Summarization

Automatically generates concise summaries of thousands of public comments.

🔍 Topic & Keyword Detection

Extracts key themes from feedback using NLP techniques.

Example insights:

Policy concerns
Public priorities
Frequently mentioned issues
📈 Interactive Admin Dashboard

Provides visual insights including:

Sentiment distribution charts
Word clouds
Trend analysis
Downloadable reports
📂 Multi-Format Input Support

Supports:

Text submissions
PDF documents
Scanned files via OCR
🏗 System Architecture
User Submissions
       │
       ▼
Input Layer
(Text / PDF / Image OCR)
       │
       ▼
Data Preprocessing
Cleaning | Tokenization | Language Detection
       │
       ▼
AI Model Ensemble
(BERT / Legal-BERT / IndicBERT / LLMs)
       │
       ▼
Expert Voting System
Model consensus for reliable predictions
       │
       ▼
Insight Generation
Sentiment | Keywords | Topics | Summaries
       │
       ▼
Admin Dashboard
Visualization + Reports
🤖 AI Models Used

SAARANSH uses an ensemble approach combining multiple transformer models for better accuracy.

Potential models include:

BERT / DistilBERT – baseline embeddings & sentiment analysis
Legal-BERT – domain understanding for policy and legal text
IndicBERT – multilingual Indian language processing
mT5 – multilingual summarization
Mistral / LLaMA-2 – advanced reasoning and summarization

A model voting mechanism ensures robust and reliable results.

⚙️ Tech Stack
Backend
FastAPI
Python
NLP pipelines
AI / ML
Transformers
HuggingFace
Ensemble learning
OCR processing
Database
PostgreSQL
Infrastructure
Kubernetes (for scaling)
Microservices architecture
Visualization
Dashboard with analytics and reports

The system relies heavily on open-source technologies to ensure cost-efficient deployment for government use.

✨ Innovation

SAARANSH introduces several innovations:

🧠 Ensemble Transformer System

Instead of relying on a single model, the system combines multiple AI models for higher reliability.

📄 Multimodal Processing

Supports both:

text comments
scanned documents via OCR
🏛 Government-Grade AI System

Designed specifically for policy consultation workflows rather than generic sentiment tools.

⚡ Scalable Architecture

Deployable across multiple government ministries under the Digital India ecosystem.

📈 Impact

If implemented across government consultation portals, SAARANSH can:

✔ Reduce manual analysis workload by 80%+
✔ Process thousands of citizen comments instantly
✔ Improve policy transparency and responsiveness
✔ Strengthen citizen participation in governance

The platform supports ministries such as:

Ministry of Corporate Affairs
Ministry of Finance
Ministry of Environment
Ministry of Health
Ministry of Education
🚧 Current Development Status

Prototype Level: 3 / 5

Completed:

✔ Text feedback processing pipeline
✔ Sentiment analysis module
✔ Summarization engine

Upcoming:

OCR support for PDFs and images
Advanced analytics dashboard
Region-wise policy sentiment insights
Real-time consultation monitoring

Full development roadmap: 3–4 months.

👨‍💻 Team
Name
Priyesh Raj
Devisha Bhargava
Abhay Raj
Ishaan Saxena
Shivam Shaurya
📚 References

Key research inspirations include:

BERT – Devlin et al. (2019)
Legal-BERT – Chalkidis et al. (2020)
IndicNLPSuite – Kakwani et al. (2020)
Digital India Public Consultation Framework
Ministry of Corporate Affairs Consultation Guidelines
🤝 Contributing

Contributions, suggestions, and improvements are welcome.

If you'd like to contribute:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a Pull Request
📜 License

This project is developed for research and hackathon purposes under the India Innovates 2026 initiative.

⭐ If you like this project, consider starring the repository!
