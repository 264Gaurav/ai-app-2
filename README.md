# ai-app-2

AI application using langchain, langgraph and langsmith framework/tool - building medium to advanced level AI application

## setup UP python package manager (similar to npm in javascript)

1. install uv in your maching -
   pip install uv

2. create virtual env -
   uv venv my-env-name

3. Activate your virtual env
   e.g., source my-env-name/bin/activate

4. Add requirements.txt file - and mention required components/libraries

---

5. install all libraries/components -
   uv add -r requirements.txt

#### you can see the installed packages/libraries inside pyproject.toml . like -

[project]
name = "ai-app-2"
version = "0.1.0"
description = "Add your description here"
readme = "README.md"
requires-python = ">=3.13"
dependencies = [
"langchain>=0.3.25",
"langgraph>=0.4.8",
"langsmith>=0.3.45",
]

---

6. install -
   uv add ipykernel

# Langgraph

Langgraph can be used in two main ways:

1. **Graph API**: Provides an interface for working with graphs programmatically.
2. **Functional API**: Offers a set of functions for performing graph-related operations.

## Login to groq cloud and get your model api key

`https://console.groq.com/playground?model=llama3-8b-8192` and put the api key in .env

## Tavily - web search tool

get TAVILY_API_KEY and put it in .env

# AI Agent using Langgraph

Langgraph enables the creation of AI agents by providing tools for graph-based reasoning and decision-making.

![AI Agent Diagram](images/agent.png)

# ReAct Agent Architecture using Langgraph

The ReAct agent combines reasoning and acting capabilities, leveraging Langgraph to structure interactions and make informed decisions.

![ReAct Agent Diagram](images/reActAgent.png)
