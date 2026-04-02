<h1 align="center">🚀 Smart AI Loan Processing</h1>
<h3 align="center">A Full-Stack, Agentic AI-Powered Loan Automation Platform</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-ReactJS-blue?style=flat-square&logo=react" />
  <img src="https://img.shields.io/badge/Backend-FastAPI-green?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/Database-MongoDB-brightgreen?style=flat-square&logo=mongodb" />
  <img src="https://img.shields.io/badge/AI-Agentic%20LangGraph-red?style=flat-square" />
  <img src="https://img.shields.io/badge/Visualization-PowerBI-yellow?style=flat-square&logo=powerbi" />
</p>

---

## 📌 Overview

**Smart AI Loan Processing** is a comprehensive loan lifecycle system built with an **agentic AI architecture**, using modern web technologies and intelligent agents to automate KYC, fraud detection, risk evaluation, and disbursement—all in one platform.

---

## 🧭 Workflow

1. 🔐 **Login**  
   Users log in via a React.js frontend. Credentials are verified using FastAPI and MongoDB.

2. 🏠 **Homepage**  
   After login, users can:
   - Create a new **Loan Application Number (LAN)**
   - Track existing LANs
   - View completed applications

3. 📤 **Document Upload**  
   - Users are redirected to an upload page (ReactJS)
   - Documents are uploaded and stored in **MongoDB**
   - A **unique LAN** is generated

4. 🧾 **KYC Verification (AI-Powered)**  
   - OCR extracts data from documents
   - Fraud is checked via **Detect-Fraud Agent**
   - Process is coordinated by the **Processed-Document Agent**
   - Backend in **FastAPI + Python**

5. 🧠 **Risk Assessment (Agentic AI)**  
   Triggered from the frontend, FastAPI runs 3 AI agents:
   - `credit_history_agent`
   - `max_loan_agent`
   - `loan_approval_agent`

6. 👤 **Human Intervention**  
   Manual verification of AI assessment for compliance.

7. 📧 **Email Communication**  
   - AI agent generates customized emails
   - Notifies the customer about approval or rejection

8. 📝 **JotForm Integration**  
   - Redirect to pre-filled form for final submission

9. 💰 **Disbursement**  
   - Final page fetches disbursement details from MongoDB
   - User sees disbursed or pending status

---

## 💻 Tech Stack

| Layer       | Technology       |
|-------------|------------------|
| Frontend    | ReactJS, CSS     |
| Backend     | FastAPI, Python  |
| Database    | MongoDB          |
| Agents      | LangGraph, Tracablity |
| Reports     | PowerBI          |

---

## 🧠 Agent Architecture

