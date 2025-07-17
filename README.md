# 📄 Automated Loan Application Processing (UiPath RPA Project)

## 🔍 Project Overview
This project aims to automate the **manual loan application processing system** used by a banking department. The bot simulates the role of a loan officer, efficiently handling incoming loan requests and reducing manual effort through Robotic Process Automation (RPA) using **UiPath**.

---

## 🎯 Objectives
- **Reduce manual processing time** by **80%** per loan application.
- Ensure **better tracking and monitoring** of tasks using automation logs.
- Improve **data accuracy** and **scalability** by automating repetitive loan entry processes.

---

## 🏗️ Process Overview
**Process Name**: Loan Applications Processing  
**Department**: Banking / Loan Operations  
**Role Simulated**: Loan Officer

### High-Level Steps:
1. Start the automation.
2. Access a dedicated **email inbox** to retrieve new loan requests.
3. **Download** loan application attachments (CSV format).
4. Open **UIBank portal** and **enter loan details** for each application.
5. Generate a **Loan ID** upon submission.
6. **Update the Excel file** with the new Loan ID.
7. Send a **confirmation email** back to the applicant.
8. Log activity and stop the process.

---

## 📥 Input Data
- **Email Inbox** with new loan applications.
- Attached CSV file containing loan details (Name, Amount, Reason, etc.).

## 📤 Output Data
- Updated Excel file with **Loan IDs**.
- Confirmation **emails** sent to each customer.
- Logs capturing each step of the process.

---

## 🧩 Tools & Technologies
- **UiPath Studio**
- **Outlook Integration**
- **Excel Activities**
- **UI Automation**
- **Exception Handling & Logging**

---

## 📦 Project Assets
- **PDD (Process Definition Document)**: Defines the business process and roles.
- **SDD (Solution Design Document)**: Describes UiPath workflow logic and technical implementation.
- **Workflow Files**: `.xaml` UiPath scripts automating each step of the loan process.

---

## ✅ Benefits
- **Eliminates manual data entry** errors.
- Improves **turnaround time** and customer satisfaction.
- Enhances **auditability** and **compliance** via logs and automation trails.
