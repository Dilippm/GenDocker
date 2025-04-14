# 🐳 GenDocker - Dockerfile Generator

A GenAI-powered tool that generates optimized Dockerfiles based on your programming language input. This project leverages Ollama with the LLaMA3 model to create Dockerfiles that follow best practices for containerization.

## 📦 Features

🔍 AI-powered Dockerfile generation

🧠 Uses LLaMA3 model via Ollama

⚙️ Generates production-ready, optimized Dockerfiles

💡 Simple and easy to use CLI interface

## 📋 Prerequisites

### 🐙 Install Ollama

For Linux

        curl -fsSL https://ollama.com/install.sh | sh

For macOS

        brew install ollama

### ▶️ Start Ollama Service


ollama serve

# 📥 Pull the LLaMA3 Model


ollama pull llama3.2:1b

# 🚀 Project Setup

1. Clone the Repository

        git clone https://github.com/your-username/dockerfile-generator.git
        cd dockerfile-generator

2. Create a Virtual Environment

        python3 -m venv venv
        source venv/bin/activate

3. Install Dependencies

        pip install -r requirements.txt

## 🧠 Run the Application

python3 generate_dockerfile.py
