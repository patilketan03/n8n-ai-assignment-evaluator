# 🚀 n8n-AI-Driven-Assignment-Evaluation-and-Scoring-System

This repository contains an automated workflow built with n8n to evaluate student assignment PDFs submitted inside a ZIP file.  
The system extracts question–answer pairs from each PDF, sends them to an AI model for scoring, and returns a structured evaluation to the user through Telegram.

---

## 📸 Workflow Snapshot
<img width="750" alt="AI Assignment Evaluator" src="https://github.com/user-attachments/assets/819747f6-f67d-4725-9c32-d7e33b1cab38" />
 />


---

## ⭐ Features

- Accepts ZIP files containing multiple assignment PDFs  
- Automatically extracts and processes all PDFs  
- Reads and identifies question–answer pairs  
- AI-powered scoring using the Gemini Chat Model  
- Sends evaluation results directly through Telegram  
- Supports multiple files using loop-based processing  
- Modular, simple, and easy to customize  

---

## 📘 How It Works

1. Telegram Trigger – user uploads the ZIP assignment  
2. Decompress ZIP  
3. Split PDFs  
4. Loop over PDF files  
5. Extract text from each PDF  
6. AI Agent processes Q&A and generates scores  
7. Send evaluation results to Telegram  
8. Optional wait step for pacing  

---

## 🛠️ Tools Used

- n8n  
- Telegram Bot API  
- Google Gemini Chat Model  
- PDF text extraction  
- ZIP decompression  

---

## ⚙️ Setup

1. Import the JSON workflow into n8n  
2. Add your Telegram Bot token  
3. Add your Gemini/OpenAI API key  
4. Start the workflow  
5. Upload a ZIP file through Telegram to receive an automated evaluation

---

## ▶️ Demo Video
[Watch Here](https://github.com/patilketan03/n8n-ai-assignment-evaluator/blob/main/assignment-evaluation-workflow-demo.mp4)

---

