
# 🤖 AI Recruiter using CrewAI + Google Gemini

This project demonstrates a fully automated AI-powered recruitment assistant built using **CrewAI** and **Gemini**. It streamlines the candidate screening process by analyzing resumes, matching candidates to job descriptions, scoring them, and generating a professional recruitment report.

## 🚀 Features

- Multi-agent system for parsing resumes, job descriptions, scoring, and report generation
- Integrated with **Gemini 2.5 Flash** for high token context windows (32K+)
- Optional **Gradio UI** for HR interaction
- Easily configurable, extensible, and scalable

## 🛠️ Installation

```bash
pip install crewai crewai_tools gradio pandas
```

## 📂 Components

- **Agents**: Resume Analyzer, Job Parser, Candidate Scorer, Report Generator
- **Tasks**: Defined to sequentially process data using agents
- **Crew**: Orchestrates execution of all tasks
- **Gradio Interface**: Enables file upload and visualization of results

## 📊 Sample Output

- Structured resume parsing
- Score breakdowns (Skills, Experience, Education, etc.)
- Ranked candidate list with hiring recommendations

## 🧠 Technologies Used

- [CrewAI](https://docs.crewai.com)
- [Google Gemini LLMs](https://ai.google.dev)
- [Gradio](https://gradio.app)
- Python

## 💡 Author

Developed as part of the **GenAI Cohort** by @asritha.sai.06

## 📄 License

MIT License
