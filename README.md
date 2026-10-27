
# 🤖 Agentic Review Generator — Dependency Usage Analyzer

An AI-powered automation project built as part of the **Agentic AI: Powering Next-Generation Innovation** course at Geethanjali College of Engineering and Technology, in collaboration with Brainovision Solutions India Pvt. Ltd.

Our team explored Agentic AI by building an automation workflow that analyzes Python project dependencies and generates structured reports using AgentKit Studio and Ollama.

## 📌 Project Overview

The Dependency Usage Analyzer is designed to inspect Python files, identify imported libraries, and generate reports that summarize dependency usage.

The project demonstrates how AI-powered automation can help developers understand project dependencies and organize code analysis results.

## ✨ Key Features

- **Dependency Detection:** Identifies imported libraries in Python files.
- **Dependency Statistics:** Generates a summary of detected imports and their usage frequency.
- **Project Overview Generation:** Creates a structured overview of project features and libraries.
- **Automated Report Generation:** Produces Markdown reports for easier analysis and documentation.
- **Local AI Integration:** Uses Ollama as part of the local AI workflow.
- **Visual Automation Interface:** Uses AgentKit Studio to configure and execute automation tasks.
- **Output Preview:** Allows generated reports and output files to be reviewed.

## 🛠️ Technologies Used

- **Python** — Core programming and analysis
- **Ollama** — Local AI model integration
- **AgentKit Studio** — Automation workflow and visual interface
- **FastAPI** — Backend API
- **SQLite** — Database interaction support
- **Git & GitHub** — Version control and project collaboration
- **HTML, CSS & JavaScript** — Frontend interface

## ⚙️ How It Works

1. Configure the dependency analysis task in AgentKit Studio.
2. Provide Python files or project input for analysis.
3. Identify imported libraries and collect dependency information.
4. Generate dependency statistics and a project overview.
5. Produce structured Markdown reports.
6. Preview the generated files through the interface.

*The exact workflow and available outputs depend on the configured automation and input files.*

## 📄 Sample Outputs

The project can generate structured reports such as:

### 1. Dependency Statistics
Summarizes the number of detected imports and lists the libraries identified during analysis.

### 2. Project Overview
Provides an overview of the analyzed project, including its libraries, major features, and relevant workflow details.

## 🚀 Getting Started

### Prerequisites

- Python installed on your system
- Ollama installed and configured if required by the AI workflow
- Project backend files available locally

### Installation

Clone the repository:

```bash
git clone https://github.com/Bhavana-1308/agentic-review-generator.git
cd agentic-review-generator
```

Install the backend dependencies:

```bash
pip install fastapi uvicorn pydantic requests python-multipart
```

### Run the Application

Start the FastAPI server:

```bash
uvicorn api:app --reload --host 127.0.0.1 --port 8000
```

Open the following URL in your browser:

```text
http://127.0.0.1:8000
```

**Note:** Ensure the required backend files, frontend files, and any additional project dependencies are available. Configure Ollama according to the model and integration used by your setup.

## 🎯 Learning Outcomes

Through this project, we gained practical exposure to:

- Agentic AI concepts and automation workflows
- Integrating local AI tools into development workflows
- Python dependency analysis and report generation
- Backend APIs and frontend integration
- Collaborative development and GitHub-based project sharing

## 👥 Team Project

This project was developed collaboratively as part of our Agentic AI learning experience.

## 🔮 Future Improvements

- Support analysis of entire Python repositories
- Improve dependency detection and reporting accuracy
- Add visual dependency summaries
- Expand reporting formats and export options
- Introduce recommendations for unused or potentially unnecessary dependencies

## 🙌 Acknowledgements

Thanks to Geethanjali College of Engineering and Technology, Brainovision Solutions India Pvt. Ltd., and our trainers for providing this opportunity to explore Agentic AI through hands-on project development.

---

**Built with curiosity, collaboration, and a passion for AI-powered automation.** 🚀

