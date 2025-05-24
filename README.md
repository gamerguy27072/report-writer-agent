# AI Report/Essay Writter Agent

An advanced AI agent built with **LangGraph** designed to automate the process of researching, outlining, and drafting essays based on a given prompt.

---

## ✨ Features

* **Automated Essay Generation:** Generates comprehensive essays from a user-provided topic or prompt.
* **Intelligent Research Capabilities:** Utilizes external tools (e.g., search APIs) to gather relevant information and context for essay content.
* **Structured Writing Process:** Implements a multi-step, agentic workflow to outline, write, and refine essay sections iteratively.
* **Contextual Understanding:** Maintains context throughout the writing process to ensure coherence and relevance across the essay.
* **LangGraph Orchestration:** Leverages the **LangGraph** framework for robust state management and complex agentic workflow design.

---

## 🛠️ Technologies Used

* **Python**
* **LangGraph** (for agent orchestration)
* **uv** (for dependency management and virtual environments)
* Large Language Models (LLMs) (e.g., OpenAI, Google AI)
* External Search Tools (e.g., Tavily API, Google Search API)

---

## 🚀 Getting Started

Follow these steps to set up and run the AI Essay Writer Agent locally.

### Prerequisites

* Python 3.9+
* `uv` installed: `pip install uv`

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/gamerguy27072/report-writter-agent.git
    cd report-writter-agent
    ```

2.  **Create and activate a virtual environment with `uv`:**
    ```bash
    uv venv
    source .venv/bin/activate # On macOS/Linux
    # .venv\Scripts\activate   # On Windows (in PowerShell/Cmd)
    ```

3.  **Install dependencies:**
    ```bash
    uv pip install -e .
    ```

### Configuration

* **API Keys:** You will need API keys for your Large Language Model (LLM) provider (e.g., OpenAI, Google AI) and any external search tools (e.g., Tavily API). Create a `.env` file in the root directory of the project and add your keys:
    ```
    OPENAI_API_KEY=your_openai_api_key
    TAVILY_API_KEY=your_tavily_api_key
    # Add other keys as needed, e.g., GOOGLE_API_KEY
    ```

---

## 💡 Usage

To run the AI Report/Essay Writer Agent, you will need to execute the code manually through the Jupyter Notebook:

1.  Ensure your virtual environment is active.
2.  Navigate to the `Notebooks` directory:
    ```bash
    cd Notebooks
    ```
3.  Open `Agent.ipynb` in a Jupyter Notebook environment (e.g., by running `jupyter lab` or `jupyter notebook` in the terminal and navigating to the file, or by opening it directly in VS Code).
4.  Run the cells within `Agent.ipynb` sequentially, providing your desired essay prompt when prompted, to initiate the essay generation process.

---

## 🚧 Work in Progress

This project is currently under active development. The following key objectives are planned:

* **Deployment:** The project is not yet deployed and therefore does not have a public-facing link.
* **API Endpoints:** Implementation of FastAPI routes to expose the essay writing functionalities as a web API, allowing for programmatic access and integration into other applications.

---
