#  Agentic AI Multi-Agent System

##  Project Overview

This project demonstrates an **Agentic AI system** that uses multiple specialized agents to understand user queries and perform different tasks.

Unlike a traditional AI chatbot that mainly generates responses, an Agentic AI system can use **tools and specialized agents** to accomplish tasks.

One of the agents in this project uses **DuckDuckGo for web searching**, allowing the system to retrieve information from the internet when required.

---

##  Objective

The main objective of this project is to understand the fundamentals of **Agentic AI and multi-agent systems**.

This project demonstrates how:

- AI agents can work with external tools
- Different agents can perform specialized tasks
- Web search can be integrated into an AI system
- An LLM can be used as the reasoning component
- Agents can be combined to create a more capable AI application

---

##  Features

-  Agentic AI system
-  Multiple specialized agents
-  DuckDuckGo web search
-  Real-time web information retrieval
-  LLM-powered responses
-  Tool-based task execution
-  Python implementation
-  LangChain integration
-  Local LLM support using Ollama

---

##  Agents Used

###  1. DuckDuckGo Search Agent

The DuckDuckGo agent is responsible for performing web searches.

When the user asks for information that requires web access, the agent can use DuckDuckGo to search for relevant information.

This makes the AI system more useful for queries requiring current or external information.

###  2. Specialized Agent

The second agent performs another specialized task within the system.

The Agentic AI system can use the appropriate agent depending on the user's query.

> Update this section with the exact name and purpose of your second agent if you want the README to describe it specifically.

---

##  System Workflow

```text
                    User Query
                         │
                         ▼
                  Agentic AI System
                         │
                ┌────────┴────────┐
                │                 │
                ▼                 ▼
       DuckDuckGo Agent     Specialized Agent
                │                 │
                ▼                 ▼
          Web Search         Task Processing
                │                 │
                └────────┬────────┘
                         ▼
                  Final AI Response
