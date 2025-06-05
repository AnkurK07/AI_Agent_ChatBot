# AI Agent ChatBot
![image](https://github.com/user-attachments/assets/3339e10c-1a55-424b-a541-4d37b628c010)

### 🧩 Problem Statement
In today's digital world, most chatbots operate with limited context and lack adaptability in dynamic conversations. Traditional rule-based or static NLP bots fail to:

- Understand multi-turn dialogue with context memory

- Adapt their responses based on evolving user intents

- Integrate with tools/APIs to perform tasks intelligently

- Reason or take initiative like a human agent

This leads to user frustration, repetitive interactions, and limited scalability for real-world applications in customer support, personal assistance, or education.

### 💡 Solution
AI_Agent_ChatBot is an intelligent, autonomous chatbot powered by AI agent architectures. It is designed to:<br>

✅  **Understand context-rich, multi-turn conversations**<br>
✅  **Adapt and respond intelligently using reasoning and memory**<br>
✅ **Integrate tools/APIs to perform real-world tasks (search, calendar, code execution, etc.)**<br>
✅ **Leverage LLMs and agentic workflows to simulate human-like initiative and dialogue**<br>

Built using state-of-the-art frameworks like LangChain, OpenAI, or Crew AI, the chatbot functions as a modular, extensible AI agent that can:

- Serve as a personal assistant

- Guide users through support or onboarding

- Perform autonomous decision-making for assigned tasks











# Project Setup Guide

This guide provides step-by-step instructions to set up your project environment, including setting up a Python virtual environment using Pipenv, pip, or conda.

## Table of Contents

1. [Setting Up a Python Virtual Environment](#setting-up-a-python-virtual-environment)
   - [Using Pipenv](#using-pipenv)
   - [Using pip and venv](#using-pip-and-venv)
   - [Using Conda](#using-conda)
2. [Running the application](#project-phases-and-python-commands)


## Setting Up a Python Virtual Environment

### Using Pipenv
1. **Install Pipenv (if not already installed):**  
```
pip install pipenv
```

2. **Install Dependencies with Pipenv:** 

```
pipenv install
```

3. **Activate the Virtual Environment:** 

```
pipenv shell
```

---

### Using `pip` and `venv`
#### Create a Virtual Environment:
```
python -m venv venv
```

#### Activate the Virtual Environment:
**macOS/Linux:**
```
source venv/bin/activate
```

**Windows:**
```
venv\Scripts\activate
```

#### Install Dependencies:
```
pip install -r requirements.txt
```

---

### Using Conda
#### Create a Conda Environment:
```
conda create --name myenv python=3.11
```

#### Activate the Conda Environment:
```
conda activate myenv
```

#### Install Dependencies:
```
pip install -r requirements.txt
```


# Project Phases and Python Commands

## Phase 1: Create AI Agent
```
python ai_agent.py
```

## Phase 2: Setup Backend with FastAPI
```
python backend.py
```

## Phase 3: Setup Frontend with Streamlit
```
python frontend.py
```

## IMPORTANT
### Make sure backend python script is running in a separate terminal



