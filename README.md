# 🚀 Project Name

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
AI Driven Entity Intelligence Risk Analysis - AI/ML powered solution to gather and enrich the infromation for identifyig, verifying and risk scoring of the entities involved in the finanical transactions 

## 🎥 Demo
🔗 [Live Demo](#) (if applicable)  
📹 [Video Demo](#) (if applicable)  
🖼️ Screenshots:

![Screenshot 1](link-to-image)

## 💡 Inspiration
What inspired you to create this project? Describe the problem you're solving.

## ⚙️ What It Does
Explain the key features and functionalities of your project.
1) Read the input file having financial transactions, identify the involved entities and classify them under one of the categories like person, orgnisation, shell compnay, etc.
2) Enrich entities informatiom from various data sources like: Open Sanctions, Offshore Leaks, Wikipedia, Corporates API database, etc.
3) Calculate the risk scoring for each transaction considering various factors like transction amount, transaciton mode, entity risk factor like listed in the sanctions list or offshore leaks database or PEP list, etc.
4) For each factor, weightage and risk score assinged and accordingly risk rate and level calculated
5) All details gathered and derived are appended to the input file
6) Finally key data elements are converted to json and output file is generated

## 🛠️ How We Built It
1) Solution developed in Python using the NLP model provided in the Spacy libraries.

## 🚧 Challenges We Faced
1) Test data to simulate all use cases and to cover various data sources.   Few data sources like Coporate API and Open Sanctions are not providing the access to their sandbox environment so had tough time to prepare the test data to cover all scenarios.

## 🏃 How to Run
1. Clone the repository  
   ```sh
   git clone https://github.com/your-repo.git
   ```
2. Install dependencies  
   ```sh
   npm install  # or pip install -r requirements.txt (for Python)
   ```
3. Run the project  
   ```sh
   npm start  # or python app.py
   ```

## 🏗️ Tech Stack
- 🔹 Frontend: Not Applicable
- 🔹 Backend: Not Applicable
- 🔹 Database: Third party APIs, .csv
- 🔹 Other: Python

## 👥 Team
- **Your Name** - [GitHub](#) | [LinkedIn](#)
- **Teammate 2** - [GitHub](#) | [LinkedIn](#)
