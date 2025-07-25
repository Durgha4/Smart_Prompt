🚀 Smart Prompt – AI Tool Prompt Generator (RAG-Based)

Smart Prompt is a powerful web-based prompt generation engine that helps users craft tailored prompts for popular AI tools like ChatGPT, Gemini, Claude, Copilot, DeepSeek, Midjourney, and Grok. Built on a Retrieval-Augmented Generation (RAG) architecture, the system takes user input (like tool, use case category, depth level, and tone) and dynamically generates a shallow to structured prompt using pre-engineered templates and contextual knowledge.

🔧 Key Features

🎯 Tool-Specific Prompting: Generates AI prompts customized to the syntax/style of selected tools.

🧠 RAG Architecture: Retrieves relevant context from a local knowledge base before prompt generation.

📊 Structured or Shallow Modes: Choose depth from beginner-friendly to expert-level formats.

🎨 Style Adaptation: Supports different tones like creative, technical, persuasive, etc.

🌐 Web App Interface: Clean React frontend with interactive prompt generation.

⚙️ Tech Stack 🧠 AI + RAG Core:

LangGraph-inspired architecture: For multi-step generation and memory.

SentenceTransformers (MiniLM): To embed and retrieve relevant context using semantic search.

Prompt Templates (JSON): AI tool-specific prompt formatting logic.

🖥 Backend:

FastAPI: Fast Python web framework for backend API.

Watsonx AI: Used as the LLM to generate refined content (optional integration layer).

Python-dotenv: For managing API keys and config.

🎨 Frontend:

React (Vite): Blazing fast and modular frontend.

Axios: For calling the FastAPI backend.

Modular Components: Includes PromptForm and ResultCard for user input and display.

📦 Deployment:

Docker: Containerization of FastAPI backend.

Vercel: Frontend deployment (Vite-React optimized).# Smart_Prompt
