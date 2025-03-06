# AI Agent Automated Job Search System

This project is built on **n8n**, integrating **Google Cloud**, **Google Gemini AI**, and **web scraping** to create an **intelligent job search automation system**.  
The system can **automatically search for job listings, analyze and compare job criteria, process data, and update the results to Google Cloud**, significantly improving job search efficiency and reducing the time spent on manual searching and filtering.

---

## System Workflow Overview
### Part 1 : Job Data Extraction & Preprocessing
![image](/image/AI_Agent_Part1.jpg)
### Part 2 : AI-Powered Job Analysis & Matching
![image](/image/AI_Agent_Part2.jpg)

---

## Key Features

- **📌 Automated Job Search**: Retrieves the latest job listings from multiple sources via **HTTP Requests**.  
- **🧠 AI-Powered Analysis**: Utilizes **Google Gemini AI** to analyze job descriptions and assess their relevance to the user’s skills and experience.  
- **📊 Google Cloud Integration**: Reads, updates, and stores job data for easy access and management.  
- **🛠 Intelligent Data Processing**: Cleans, filters, and stores valuable job data using custom scripts.  
- **🔄 Efficient Parallel Processing**: Implements loop and batch processing to quickly filter multiple job listings, improving performance.  
- **🌍 Web Data Extraction**: Parses **HTML content** to extract key job information, reducing manual screening efforts.  

---

## Workflow Overview

### **1️⃣ Automated Job Data Retrieval**
- The system retrieves job listings via **HTTP Requests**, ensuring real-time updates with the latest job opportunities.  
- The retrieved data is compared against **existing job records**, storing only new job listings to prevent duplicates.  
- Newly filtered job listings are automatically saved to **Google Cloud**, ensuring an up-to-date database.  

### **2️⃣ AI Analysis & Data Processing**
- **Google Gemini AI** analyzes job descriptions, extracts key details, and performs semantic analysis.  
- **Job Matching Evaluation**: The AI ranks and filters job listings based on the user’s skills, experience, and preferences.  
- **Code Nodes** clean and structure job data, such as parsing URLs and extracting HTML content.  
- **Mapping & Filtering Logic** ensures the extracted data is accurate and useful, preventing irrelevant listings from entering the final results.  

### **3️⃣ Storage & Output**
- **Filtered job data** is automatically saved to **Google Cloud** for easy tracking and management.  
- **AI Scoring Mechanism** helps users quickly identify the most relevant job opportunities, increasing application success rates.  
- The system can **dynamically add or update** job listings to keep information current.  

---

## Future Enhancements
- **📈 Expanding Job Sources**: Integrating more **job search APIs** to cover a wider job market.  
- **📩 Notification Features**: Implementing **Email or Slack notifications** to alert users about newly matched job opportunities.  
- **📤 Automated Resume Submission**: Enabling automatic resume submission to streamline the job application process.  
- **🗣 Advanced AI Interaction**: Enhancing Google Gemini AI to provide **job search advice and interview preparation assistance**, increasing job search success rates.  
