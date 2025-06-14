# Digital-Health-Card
# 🩺 Digital Health Identity System for Patients

A web-based platform that allows patients to create, manage, and share a personal digital health card with relevant medical information. It provides secure, role-based access for families and emergency responders.

---

## 📌 Problem Statement

In today's healthcare ecosystem, patient data is often scattered across hospitals, labs, and clinics. This fragmentation causes difficulties in accessing records quickly during emergencies and results in repeated tests, delayed treatment, or wrong decisions.

---

## 🎯 Objective

To build a **minimal, mobile-friendly, and secure** system where patients can:
- Create a digital health card
- Log medical history and medications
- Export and share their health summary securely

---

## 🚀 Features

### 1. Health Card Creation
- Name, DOB, Gender, Blood Group
- Medical conditions (e.g., asthma, diabetes)
- Emergency contact (name, phone, relation)

### 2. Medical History Management
- Doctor visit logs (name, date, prescription notes)
- Add medications with dosage and date
- Upload test results (PDF, images)

### 3. Health Card Output
- View as digital summary card
- Export to PDF
- QR code generation for public (read-only) sharing
- Emergency scan mode for quick access

### 4. Role-Based Access
- **Patient** → Full access
- **Family** → Read-only access
- **Emergency** → Limited view (blood group, conditions, contact)

---

## 🛠 Tech Stack

- HTML, CSS, JavaScript
- QR Code: [`qrcode.js`](https://github.com/davidshimjs/qrcodejs)
- (Optional) Firebase for storage & auth
- GitHub Pages / Vercel for hosting

---

## 📷 Screenshots

> *(Add screenshots of your app interface here)*

---

## 💡 Future Improvements

- Add mobile app version
- Integrate with hospital APIs
- Add voice-enabled data entry
- Blockchain for secure record sharing

---

## 📦 Installation & Usage

```bash
# Clone this repo
git clone https://github.com/your-username/digital-health-identity-system.git

# Open index.html in browser
