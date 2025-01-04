# Financial and Web Search Agent

This repository contains a demonstration project for setting up and using AI agents for financial data analysis and web search. The project utilizes the `phi` library to create and deploy agents that interact with financial data sources and perform web searches using OpenAI models.

## Project Files

### 1. `playground.py`
This script sets up a playground environment using two agents:
- **Web Search Agent**: Searches the web for information using DuckDuckGo.
- **Financial Agent**: Retrieves financial data, including stock prices, analyst recommendations, stock fundamentals, and company news using YFinanceTools.

It initializes the agents, configures them with the appropriate tools, and serves a playground application for interacting with these agents.

### 2. `financebot.py`
This script demonstrates the standalone use of financial and web search agents. It defines the following:
- **Web Search Agent**: As in `playground.py`, it searches the web for information.
- **Financial Agent**: Similar to `playground.py`, retrieves financial data.
- **Multi AI Agent**: Combines the two agents to provide a comprehensive response using both web search and financial data retrieval.

It also includes an example call to `multi_ai_agent.print_response` for summarizing analyst recommendations and sharing the latest news for a specific stock (e.g., NVDA).

### 3. `requirements.txt`
This file lists the dependencies required for the project, which should be installed in a virtual environment.

## Setup Instructions

### Prerequisites
- Python 3.x
- Virtual Environment
- API keys for OpenAI and PHI

### Steps to Set Up the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
