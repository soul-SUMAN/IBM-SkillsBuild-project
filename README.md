
# 🤖 Interview Trainer Agent | IBM SkillsBuild Project

This repository documents the final project submitted as part of the **IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies**, a collaborative initiative by **Edunet Foundation**, **AICTE**, and **IBM SkillsBuild**.

This AI-driven Interview Trainer Agent was developed using **IBM Watsonx.ai studio** and leverages **foundation models** and **Retrieval-Augmented Generation (RAG)** to simulate mock interview sessions, personalized to user profile, job role, and experience level.

---

## 📝 Table of Contents

- [Intern Details](#-intern-details)
- [About the Internship](#-about-the-internship)
- [Project: Interview Trainer Agent](#-project-interview-trainer-agent)
  - [Problem Statement](#problem-statement)
  - [Solution Overview](#solution-overview)
- [⚙️ Technology Stack](#️-technology-stack)
- [🚀 Project Workflow](#-project-workflow)
- [📊 Results](#-results)

---

## 👨‍💻 Intern Details

- **Name**: Suman Mondal  
- **Institute**: B. P. Poddar Institute of Management and Technology  
- **Department**: Information Technology  
- **Duration**: 4 Weeks (15th July 2025 – 7th August 2025)

---

## 📖 About the Internship

📖 About the Internship
This 4-week IBM SkillsBuild internship was structured to provide hands-on experience in AI, Cloud Technologies, and Foundation Models through a series of guided sessions, tools exploration, and a final capstone project. The program was jointly hosted by AICTE, Edunet Foundation, and IBM, with weekly mentor-led labs and project-based learning.

📅 Weekly Highlights:

Week 1 – AI & Cloud Fundamentals
- Orientation & IBM Cloud registration
- Intro to IBM Cloud Services, Jupyter Notebooks
- AI & ML basics, Crop recommendation use-case with AutoAI
- Generative AI and Granite models via Prompt Lab

Week 2 – Data Handling & RAG Concepts
- Data Analytics with IBM Data Refinery
- Project use-cases: Cloud Object Storage, Chatbot, Static Website Deployment
- Retrieval-Augmented Generation (RAG) introduction
- Hands-on with IBM Watsonx Assistant

Week 3 – Agentic AI & Real Projects
- RAG System Design using IBM Granite Models
- Introduction to Agentic AI using Watsonx Agentic Lab
- Building AI agents with LangGraph & ReAct
- Applied projects: skin disease detection, interview trainer, etc.

Week 4 – Final Project Lab & Submission
- Deep dive into LangChain and Data Prep Kit
- Agent finalization using 3B+ instruction-tuned LLMs
- Readiness checks, final evaluation & submission via IBM Watsonx

---

## 💡 Project: Interview Trainer Agent

#### 🔍 Problem Statement [🔗](https://github.com/soul-SUMAN/IBM-SkillsBuild-project/blob/main/problem-no-22.png)

Many job aspirants face difficulty in preparing for interviews due to:
- Lack of personalized, role-specific guidance
- Limited access to soft skill evaluations
- No feedback-driven practice experience

---

### ✅ Solution Overview

The Interview Trainer Agent provides:
- Role-based technical and soft skill questions
- Feedback and improvement suggestions
- Real-time mock interview experiences
- Resume/profile-based dynamic content

The solution uses IBM Watsonx foundation models with RAG to simulate interview coaching based on uploaded Q&A PDFs and user prompts.

---

## ⚙️ Technology Stack

| Category          | Tools / Services Used                                 |
|------------------|--------------------------------------------------------|
| Cloud Platform    | IBM Cloud (Lite Plan)                                 |
| AI/ML Services    | Watsonx.ai Studio, Agent Lab                          |
| Foundation Models | granite-3-3-8b-instruct, llama-3-2-11b-version-instruct |
| Storage           | IBM Cloud Object Storage                              |
| Architecture      | LangGraph & ReAct (Agentic Design)                    |
| Data Format       | PDF (custom Q&A dataset), Prompt chaining             |

---

## 🚀 Project Workflow

1. **Data Preparation**  
   - Curated job-role based technical & soft skill Q&A
   - Converted into searchable PDFs for RAG ingestion

2. **Project Setup in Watsonx**  
   - Created sandbox project in IBM Watsonx Studio  
   - Added Object Storage and Watsonx Runtime services

3. **Agent Configuration**  
   - Built an agent in Agent Lab using LangGraph & ReAct  
   - Enabled Document Tool for uploading Q&A PDFs  
   - Set up prompt logic for user-specific interview generation

4. **Prompt Execution**  
   - Users enter name, experience, job role, or paste resume  
   - Example: “Suman Mondal, Fresher, Web Developer”  
   - Agent dynamically fetches and generates relevant interview content

5. **Deployment & Evaluation**  
   - Agent deployed using default deployment environment  
   - Tested for multiple roles and experience levels

---

## 📊 Results

- Successfully generated:
  - 100+ mock interview questions across roles
  - Real-time feedback and improvement tips
- High relevance and accuracy using Watsonx foundation models
- Smooth integration of role-based PDFs via RAG
- 
Results Screen shots:
<img width="1919" height="930" alt="Screenshot 2025-08-01 034418" src="https://github.com/user-attachments/assets/98d0d76b-3c7b-4c89-9b89-901c9b670196" />
<img width="1919" height="927" alt="Screenshot 2025-08-01 034453" src="https://github.com/user-attachments/assets/9ebcf5e8-8e6c-4bbe-a419-a864aa7a5ca3" />
<img width="1918" height="927" alt="Screenshot 2025-08-01 034523" src="https://github.com/user-attachments/assets/9914097b-0af8-4cda-8615-2350781fe92b" />
<img width="1919" height="929" alt="Screenshot 2025-08-01 034541" src="https://github.com/user-attachments/assets/55f4dffd-581c-4d60-b0bb-5db30bbcbf6d" />
<img width="1919" height="929" alt="Screenshot 2025-08-01 144534" src="https://github.com/user-attachments/assets/307a3d76-e0e2-4e2e-b2f9-7d4b5e703057" />

> ✅ This project met all requirements for successful internship completion.

---


## 📜 Certificates & Resource

- 🧠 [Getting Started with AI – IBM SkillsBuild](https://github.com/soul-SUMAN/IBM-SkillsBuild-project/blob/main/Getting-Started-with-Artificial-Intelligence.jpg)
- ☁️ [Journey to Cloud – IBM SkillsBuild](https://github.com/soul-SUMAN/IBM-SkillsBuild-project/blob/main/Journey-to-Cloud-Envisioning-Your-Solution.jpg)
- 📚 [IBM RAG Lab Completion Certificate](https://github.com/soul-SUMAN/IBM-SkillsBuild-project/blob/main/Lab-Retrieval-Augmented-Generation-with-LangChain.jpg)
- 📑 [Sample-data-for-training](https://github.com/soul-SUMAN/IBM-SkillsBuild-project/blob/main/Sample-q%26a-for-training.pdf)   (<a href="Sample-q&a-for-training.pdf">Download PDF</a>)
---

## 🙏 Acknowledgements

- IBM SkillsBuild & Watsonx Team  
- Edunet Foundation & AICTE  
- Mentors and Volunteers from IBM Internship Program  

---

> 🔗 Feel free to clone, fork, or contribute to the repository.  
> This solution demonstrates the power of IBM Watsonx and foundation models in real-world problem solving.


