📸 Instagram Content Strategy Crew
A modular, agent-powered automation framework for generating complete Instagram content strategies using CrewAI. This project allows you to streamline the research, planning, content creation, and publishing workflow for Instagram pages.

🚀 Features
🤖 Multi-Agent System powered by CrewAI:
Structured workflow using specialized agents:

Market Researcher

Content Strategist

Visual Creator

Copywriter

📅 Inputs driven by user prompts:

Instagram page description

Topic of the week

Current date auto-filled

📊 Tasks & Agents configured via YAML

Easy-to-modify config files for custom agents and task flows

🔍 Built-in tools for:

Web and Instagram search using Serper API

Web content extraction via LangChain’s WebBaseLoader

🧠 How It Works
You run main.py

The system prompts for basic inputs like topic and page description

A crew of agents is initialized based on YAML configs

Each agent performs their task:

Market research

Strategy formulation

Visual content generation

Copywriting

Outputs are saved as .md files like market_research.md and final_content_strategy.md
