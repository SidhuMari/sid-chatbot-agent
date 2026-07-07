# sid-chatbot-agent

Live Web Agent
A Streamlit application that utilizes the LangChain library to create a live research assistant. The agent is equipped with a DuckDuckGo web search tool to find current information and answer user queries.

Features
Live web browsing and analysis
Utilizes LangChain library for AI-powered research assistance
Equipped with DuckDuckGo web search tool
Streamlit-based user interface for easy interaction
Requirements
Python 3.8+
Streamlit
LangChain
LangChain Community
LangGraph
Installation
To install the required libraries, run the following command:

pip install -r requirements.txt
Usage
Run the application using the following command:
streamlit run app.py
Open a web browser and navigate to the URL displayed in the terminal.
Enter your Groq API key in the sidebar.
Ask a question about current events in the chat input field.
The agent will browse the web, analyze the results, and provide a response.
Configuration
Groq API key: Enter your API key in the sidebar to utilize the LangChain library.
System prompt: The system prompt is predefined to ensure the agent uses the web search tool to find current information.
Notes
This application is for demonstration purposes only.
The LangChain library and Groq API key are required for the application to function properly.
The DuckDuckGo web search tool is used to find current information and answer user queries.
