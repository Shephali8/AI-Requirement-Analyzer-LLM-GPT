# AI-Powered Requirement Analyzer (LLM + Prompt Engineering)

This project demonstrates how Large Language Models (LLMs) like GPT can assist Business Analysts and product teams by analyzing requirement documents and automatically extracting:

- User stories  
- Acceptance criteria  
- Business rules  
- High-level summary and key points  

The goal is to reduce manual effort in requirement analysis and improve clarity before development and testing.

---

## 🔍 Problem Statement

Business Analysts often receive long, unstructured requirement documents (BRDs/PRDs, emails, notes).  
Manually converting them into user stories and acceptance criteria is time-consuming and error-prone.

This project uses an LLM + prompt engineering workflow to:

- Read a requirement document
- Extract structured user stories
- Generate acceptance criteria
- Highlight potential ambiguities

---

## ✨ Key Features

- AI-assisted requirement analysis using GPT-based LLMs  
- Automatic extraction of user stories and acceptance criteria  
- Conversion of unstructured text into sprint-ready items  
- Prompt templates that can be reused or customized  

---

## 🛠 Tech Stack

- Python (optional for automation)  
- GPT / LLM (e.g. OpenAI ChatGPT API or UI)  
- Prompt Engineering  
- Markdown / Excel for output formatting  

---

## 📂 Suggested File Structure

AI-Requirement-Analyzer-LLM-GPT/
├─ README.md
├─ samples/
│  ├─ requirement_sample_1.txt
│  ├─ requirement_sample_2.txt
├─ prompts/
│  ├─ user_story_prompt.txt
│  ├─ acceptance_criteria_prompt.txt
└─ outputs/
   ├─ user_stories_example.md
   ├─ acceptance_criteria_example.md
