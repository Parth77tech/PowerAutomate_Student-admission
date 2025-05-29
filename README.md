# 🎓 Student Admissions Automation with Power Automate

---

## 🚀 Project Summary

### Objective  
Develop a multi-stage Power Automate workflow to streamline the student admissions process by automating data capture, approval routing, document generation, and communication, thereby improving data accuracy and operational efficiency.

### Key Features  
- **Data Capture:** Collect student inquiry data via online forms and store it securely in SharePoint Lists.  
- **Approval Workflow:** Route student records through an automated approval process, syncing only approved entries to the enrollment list.  
- **Document Automation:** Automatically generate and email formatted Word documents containing student intake details to the Admissions Department.  

---

## 🏗️ Automation Workflow Architecture

The project consists of three main Power Automate flows working together:

1. **Student Inquiry to MS List + Email**  
   - Triggered by HTTP request from intake forms  
   - Captures and stores student data in Microsoft Lists  
   - Generates Word documents and emails them to Admissions  

2. **Sync List on Approval**  
   - Activated when student records are approved  
   - Synchronizes approved entries between SharePoint lists  
   - Maintains data consistency across intake and enrollment  

3. **Student Intake to Admissions**  
   - Combines data capture and document automation  
   - Ensures seamless, error-free transmission of admission documents  

---

## 📖 Detailed Workflow Descriptions

### FLOW 1️⃣: Student Inquiry Info to MS List + Email  
- 📝 Collects student details via online form submissions  
- 💾 Stores data in Microsoft Lists for structured management  
- 📄 Generates formatted Word documents with student information  
- 📧 Sends documents via institutional email to Admissions  

### FLOW 2️⃣: Sync List on Approval – Information to Enrollment  
- 🔔 Triggers on approval of student record in SharePoint  
- 📖 Reads data from the **Information Sheet** list  
- ✍️ Updates or creates matching entries in the **Enrollment Sheet** list  
- 🔄 Ensures accurate synchronization and data integrity  

### FLOW 3️⃣: Student Intake to Admissions  
- 📝 Captures student inquiry data from external sources  
- 💾 Stores data in SharePoint Lists  
- 📄 Generates admission intake documents via Word Online  
- 📧 Automates email delivery to Admissions Department  

---

## 🧩 Technologies Used  
- **Microsoft Power Automate** – Workflow orchestration and automation  
- **SharePoint Online** – Data storage and list management  
- **Word Online (Business)** – Dynamic document generation  
- **Office 365 Outlook** – Automated email sending  

---

## 🌟 About Me

Hi! I'm **Parth**, an experienced Data Professional passionate about leveraging Microsoft 365 tools to build efficient, scalable workflows that reduce manual effort and increase operational accuracy in education and business processes.
