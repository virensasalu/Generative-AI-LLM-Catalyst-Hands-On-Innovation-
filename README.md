# Project Title: Generative AI & LLM Catalyst: Hands-On Innovation 

A collection of Jupyter notebooks demonstrating how to **summarize webpages** and create a **tech Q&A chatbot** using both **OpenAI** and **Ollama** (local LLM).

---

## Table of Contents

1. [Introduction](#introduction)  
2. [Project Structure](#project-structure)  
3. [Features](#features)  
4. [Getting Started](#getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
5. [Usage](#usage)  
   - [1. Summarizing with OpenAI](#1-summarizing-with-openai)  
   - [2. Summarizing with Ollama](#2-summarizing-with-ollama)  
   - [3. Tech Q&A Chatbot](#3-tech-qna-chatbot)  
6. [Notebook Details](#notebook-details)  
7. [Troubleshooting](#troubleshooting)  
8. [Contributing](#contributing)  
9. [License](#license)  
10. [Contact](#contact)

---

## Introduction

This repository showcases **multiple approaches** to leveraging Large Language Models (LLMs) for:

- Summarizing text from webpages
- Answering technical questions in a chatbot-like interface

You can choose between **OpenAI** (using their API) or **Ollama** (running a local LLM, like LLaMA or other models) depending on your needs and constraints.

---

## Project Structure
  
├── ollama_summarize_webpage.ipynb    # Notebook for local LLM summarization  
├── openai_summarize_webpage.ipynb    # Notebook for OpenAI-based summarization  
├── tech_qna_chatbot.ipynb            # Notebook for a Gradio-based tech Q&A chatbot  
├── requirements.txt                  # Python dependencies  
├── README.md                         # This file  




---

## Features

- **Webpage Summaries**: Pass a URL or webpage text to the notebooks to get a concise summary.
- **Local LLM (Ollama)**: Summarize text using a locally hosted LLM if you prefer not to send data externally.
- **OpenAI API**: Summarize text using OpenAI’s GPT models (requires an API key).
- **Tech Q&A Chatbot**: A simple interface that lets you ask technical questions and get answers in real time.

---

## Getting Started

### Prerequisites

- **Python 3.8+** (recommended)
- **Jupyter Notebook** or **JupyterLab** to run `.ipynb` files
- **pip** or **conda** for installing dependencies
- (For OpenAI) An **OpenAI API key** ([Sign up here](https://platform.openai.com/))
- (For Ollama) **Ollama** installed locally if you plan to run the local LLM approach. See [Ollama’s repo](https://github.com/jmorganca/ollama) for setup instructions.

### Installation

1. **Clone this repository**:
   ```bash
   git clone https://github.com//yourrepo.git
   cd yourrepo
2. pip install -r requirements.txt

3. conda env create -f environment.yml

4. conda activate <env-name>

export OPENAI_API_KEY="your-openai-api-key"


### Contact
	•	**Author**: Your Name (or Organization)
	•	**Email**: your.email@example.com
	•	**GitHub**: @yourusername
