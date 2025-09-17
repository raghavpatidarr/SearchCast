# SearchCast 🌍⛅

SearchCast is an AI-powered assistant built with **LangChain** and **OpenAI**, designed to answer queries by combining **web search** and **real-time weather data**.

## 🚀 Features
- 🌐 **Web Search** – Uses DuckDuckGo Search to fetch up-to-date information.  
- ☁️ **Weather Updates** – Fetches current weather for any city via the Weatherstack API.  
- 🧠 **ReAct Agent** – Reasons step by step, choosing when to use search or weather tools.  
- 🔗 **LangChain Integration** – Demonstrates how to combine LLMs with external tools.

## 🛠️ Tech Stack
- [LangChain](https://www.langchain.com/)  
- [OpenAI Chat Models](https://platform.openai.com/)  
- [DuckDuckGo Search API](https://duckduckgo.com/)  
- [Weatherstack API](https://weatherstack.com/)  

## 📦 Installation
```bash
git clone https://github.com/raghavpatidarr/searchcast.git
cd searchcast
pip install -r requirements.txt

## ⚡ Usage

Update your API keys in the script:

OPENAI_API_KEY for OpenAI

WEATHERSTACK_API_KEY for Weatherstack

## Run the agent:

python agents_in_langchain.py


Example:

Input: "Find the capital of Madhya Pradesh, then find its current weather condition"
Output: "The capital of Madhya Pradesh is Bhopal. The current weather in Bhopal is ..."

