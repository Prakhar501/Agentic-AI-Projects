# Currency Conversion Agent

## Overview
This project is an AI-powered **Currency Conversion Agent** built using **LangChain**, **Groq LLM**, and custom tools.  
The agent can:

- Fetch currency conversion rates
- Convert one currency into another
- Use tool calling with an LLM
- Perform reasoning-based currency queries using natural language

Example:
> “What is the conversion rate of USD to INR and convert 25 USD to INR”

---

## Tech Stack

- Python
- LangChain
- LangChain Community
- LangChain Groq
- Groq API
- Llama 3.1 8B Instant Model

---

## Features

- AI agent with tool-calling capability
- Natural language currency conversion
- Modular tool-based architecture
- Groq-powered fast inference
- Beginner-friendly implementation

---

## Project Structure

```bash
Currency-Conversion-Agent/
│
├── Currency_Conversion_Agent.ipynb
├── requirements.txt
└── README.md
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Prakhar501/Agentic-AI-Projects.git
cd Agentic-AI-Projects
```

---

### 2. Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate environment:

#### Windows
```bash
venv\Scripts\activate
```

#### Linux / Mac
```bash
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Requirements

Create a `requirements.txt` file with:

```txt
langchain
langchain_community
langchain_groq
groq
```

---

## Setup API Key

Inside your Python file or notebook:

```python
import os
os.environ["GROQ_API_KEY"] = "YOUR_API_KEY"
```

Get your API key from:  
https://console.groq.com/keys

---

## How It Works

### Step 1: User Query
The user asks a currency-related question in natural language.

### Step 2: LLM Reasoning
The Groq-powered LLM analyzes the request.

### Step 3: Tool Calling
The agent calls custom tools like:

- `get_conversion_factor()`
- `convert()`

### Step 4: Final Response
The agent returns the conversion result in natural language.

---

## Example Query

```python
messages=[HumanMessage(
"What is conversion Rate of USD to INR and can u convert 25 USD to INR"
)]
```

### Example Output

```bash
25 USD = 2080 INR
```

---

## Concepts Used

- LangChain Tools
- Tool Binding
- Function Calling
- LLM Agents
- AI Automation
- Prompt-based Reasoning

---

## Future Improvements

- Real-time forex API integration
- Multiple currency support
- Streamlit/Web UI
- Voice-enabled currency assistant
- Agent memory support
- Multi-tool financial assistant

---

## Author

Prakhar Bhatnagar  
B.Tech AIML Student | AI & Agentic AI Enthusiast

GitHub: https://github.com/Prakhar501
