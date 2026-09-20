<h1 align="center">🩺 MediEase Pro</h1>
<h3 align="center">AI-Based Clinical Prescription Analysis System</h3>

<p align="center">
  <img src="https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/-OCR-000000?style=flat-square" />
  <img src="https://img.shields.io/badge/-Groq%20LLaMA%203.1-FF6F00?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Private%20Repo-red?style=flat-square" />
</p>

🎥 [**Watch Full Demo Video**](https://github.com/user-attachments/assets/b262e090-29c9-4f23-b6bd-6f7a8f645665)

---

## 📖 Overview

**MediEase Pro** is an AI-powered clinical decision-intelligence platform that transcribes handwritten prescriptions, cross-references detected medicines against a drug knowledge base, and flags potential risks — built for doctors, pharmacists, analysts, and patients through role-based dashboards.

The system solves a real clinical problem: handwritten prescriptions are often hard to read and prone to misinterpretation. MediEase Pro uses OCR + LLM reasoning to transcribe, validate, and explain prescriptions in seconds, reducing manual lookup time and medication errors.

---

## ✨ Key Features

- 🔐 **Role-based access** — 5 distinct dashboards: Admin, Doctor, Pharmacist, Analyst, Patient
- 📷 **Multi-input prescription capture** — upload an image, use a live camera, or paste text
- 🤖 **AI-powered OCR + reasoning** — OCR Space Engine extracts handwritten text; Groq LLaMA 3.1 interprets and validates it
- 💊 **Drug Knowledge Base** — searchable database of 34+ medicines with dosage, interactions, contraindications, and risk levels
- ⚠️ **Risk stratification** — every analyzed prescription is flagged Safe / Caution / High Risk
- 📊 **Clinical analytics dashboard** — scan volume trends and risk distribution at a glance
- 🧑‍⚕️ **Patient portal** — patients can view their own prescription history and download PDF reports
- 🧾 **Pharmacy management** — pending prescriptions queue for pharmacists to review and dispense
- 📝 **Full audit logging** — every login and action is tracked for security/compliance

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Java, Spring Boot |
| AI / OCR | OCR Space API, Groq LLaMA 3.1 |
| Frontend | HTML, CSS, Bootstrap 5, Thymeleaf |
| Database | H2 / SQLite, Spring Data JPA |
| APIs | REST APIs |

---

## 🖼️ Walkthrough

### 1. Role-Based Login
Users sign in through one unified portal and are routed to the dashboard matching their role.
<p align="center">
  <img src="https://raw.githubusercontent.com/Roshni-1227/portfolio-assets/main/MediPro%20Project%20Screenshots/01-login.png" width="70%" />
</p>

### 2. Prescription Upload & OCR Detection
A prescription image is uploaded (or captured live) — the OCR engine reads the handwriting and the AI detects each medicine automatically.
<p align="center">
  <img src="https://raw.githubusercontent.com/Roshni-1227/portfolio-assets/main/MediPro%20Project%20Screenshots/03-prescription-upload.png" width="45%" />
  <img src="https://raw.githubusercontent.com/Roshni-1227/portfolio-assets/main/MediPro%20Project%20Screenshots/04-ocr-detected-medicines.png" width="45%" />
</p>

### 3. Medicine Detail & Risk Assessment
Each detected medicine can be expanded into a full clinical profile — composition, dosage, interactions, and risk level.
<p align="center">
  <img src="https://raw.githubusercontent.com/Roshni-1227/portfolio-assets/main/MediPro%20Project%20Screenshots/05-medicine-detail-card.png" width="60%" />
</p>

### 4. Drug Knowledge Base
A searchable library of the full medicine database, browsable by name, category, or symptom.
<p align="center">
  <img src="https://raw.githubusercontent.com/Roshni-1227/portfolio-assets/main/MediPro%20Project%20Screenshots/06-drug-knowledge-base.png" width="70%" />
</p>

### 5. Doctor Dashboard
Doctors get a weekly activity summary, risk alerts, and their recent prescription history.
<p align="center">
  <img src="https://raw.githubusercontent.com/Roshni-1227/portfolio-assets/main/MediPro%20Project%20Screenshots/07-doctor-dashboard.png" width="70%" />
</p>

### 6. Patient Portal
Patients can track their own prescription history, view AI risk assessments, and download PDF reports.
<p align="center">
  <img src="https://raw.githubusercontent.com/Roshni-1227/portfolio-assets/main/MediPro%20Project%20Screenshots/08-patient-portal.png" width="70%" />
</p>

### 7. Pharmacy Management
Pharmacists manage a live queue of pending prescriptions and cross-check them against the drug knowledge engine before dispensing.
<p align="center">
  <img src="https://raw.githubusercontent.com/Roshni-1227/portfolio-assets/main/MediPro%20Project%20Screenshots/09-pharmacy-management.png" width="70%" />
</p>

### 8. Clinical Intelligence Analytics
A real-time view of total scans, safe vs. caution vs. high-risk results, and analysis trends over time.
<p align="center">
  <img src="https://raw.githubusercontent.com/Roshni-1227/portfolio-assets/main/MediPro%20Project%20Screenshots/10-analytics-dashboard.png" width="70%" />
</p>

---

## 🔒 Source Code

The source code for this project is kept in a **private repository** to protect proprietary implementation details. Access can be shared on request — feel free to reach out via [LinkedIn](https://www.linkedin.com/in/roshni-k-a2855a28a) or [email](mailto:roshni.academic.in@gmail.com).

---

<p align="center">⬅️ <a href="https://github.com/Roshni-1227/Roshni-1227">Back to Profile</a></p>
