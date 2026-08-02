# Researchmind-multi-agent-ai
# 🔬 ResearchMind – Multi-Agent AI Research System

> **ResearchMind** is a Multi-Agent AI Research Assistant built with **LangChain**, **Mistral AI**, **Tavily Search**, and **Streamlit**. It automates the complete research workflow by using specialized AI agents that search, scrape, write, and critique research reports on any topic.

---

## ✨ Features

- 🔍 **Search Agent**
  - Finds the latest and relevant information from the web.
  - Uses Tavily Search API.

- 📄 **Reader Agent**
  - Scrapes the most relevant web page.
  - Extracts detailed content for research.

- ✍️ **Writer Chain**
  - Generates a structured research report.
  - Includes:
    - Introduction
    - Key Findings
    - Conclusion
    - Sources

- 🧐 **Critic Chain**
  - Reviews the generated report.
  - Provides:
    - Score
    - Strengths
    - Areas to Improve
    - Final Verdict

- 🎨 **Modern Dark UI**
  - Premium Streamlit Interface
  - Real-time Pipeline Visualization
  - Download Report Feature

---

# 🏗️ Architecture

```
                User
                  │
                  ▼
          Streamlit Interface
                  │
                  ▼
        ┌────────────────────┐
        │  Search Agent       │
        │ (Tavily Search)     │
        └────────────────────┘
                  │
                  ▼
        ┌────────────────────┐
        │  Reader Agent      │
        │ (Web Scraper)      │
        └────────────────────┘
                  │
                  ▼
        ┌────────────────────┐
        │  Writer Chain      │
        │ (Generate Report)  │
        └────────────────────┘
                  │
                  ▼
        ┌────────────────────┐
        │  Critic Chain      │
        │ (Evaluate Report)  │
        └────────────────────┘
                  │
                  ▼
          Final Research Report
```

---

# 🚀 Tech Stack

- Python
- Streamlit
- LangChain
- Mistral AI
- Tavily Search API
- BeautifulSoup
- Requests
- HTML/CSS

---

# 📂 Project Structure

```
researchmind-multi-agent-ai/
│
├── app.py
├── agent.py
├── tools.py
├── requirements.txt
├── .env.example
├── README.md
│
├── screenshots/
│   ├── home.png
│   ├── pipeline.png
│   └── report.png
│
└── assets/
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/Shreya9996/researchmind-multi-agent-ai.git

cd researchmind-multi-agent-ai
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv .venv

.venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv .venv

source .venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file.

```
MISTRAL_API_KEY=YOUR_MISTRAL_API_KEY

TAVILY_API_KEY=YOUR_TAVILY_API_KEY
```

---

# ▶️ Run the Application

```bash
streamlit run app.py
```

---

# 🧠 Workflow

1. User enters a research topic.
2. Search Agent gathers recent information.
3. Reader Agent scrapes the best source.
4. Writer Chain generates a research report.
5. Critic Chain evaluates the report.
6. User downloads the final report.

---

# 📸 Screenshots

## Home Page

> Add your screenshot here.

```
<img width="971" height="592" alt="image" src="https://github.com/user-attachments/assets/103a4253-1f12-4cac-8cb9-c3f02f28c3c5" />
```

---

## Pipeline Execution

> Add your screenshot here.

```
<img width="1363" height="586" alt="image" src="https://github.com/user-attachments/assets/2e3bc0ca-977b-4954-8b61-81fd0d8df311" />

```

---

## Research Report

> Add your screenshot here.

```

<img width="1224" height="598" alt="image" src="https://github.com/user-attachments/assets/76f3d0d5-aa44-42da-8049-185cc37f91b4" />

```

---

# 🎯 Example Topics

- Quantum Computing Breakthroughs in 2025
- Future of Artificial Intelligence
- CRISPR Gene Editing
- Fusion Energy
- AI in Healthcare
- Autonomous Vehicles
- Climate Change Technologies

---

# 📈 Future Improvements

- LangGraph Workflow
- Memory Support
- Multi-LLM Support (OpenAI, Gemini, Claude)
- PDF Report Export
- Citation Verification
- RAG Integration
- Report History
- Authentication
- Docker Deployment

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👩‍💻 Author

**Shreya Gurbas Patil**

- Third-Year B.Tech Computer Science Student
- AI & Generative AI Enthusiast
- LangChain Developer
- IEEE Research Intern

---

## ⭐ If you like this project, don't forget to give it a Star!
