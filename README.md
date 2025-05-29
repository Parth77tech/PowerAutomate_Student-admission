🎓 Student Admissions Automation with Power Automate
Summary
Designed and deployed a Power Automate workflow that captures student inquiries in SharePoint, routes records for approval, then automatically generates and emails admission documents to administrators, ensuring accurate data synchronization and streamlined onboarding.

This project features a multi-stage Power Automate workflow designed to streamline and optimize the student admissions process:

📝 Capture: Student inquiry data collected via online forms and stored in SharePoint Lists

✅ Approval: Automated approval workflows update records and synchronize approved data from the intake list to the enrollment list, ensuring data accuracy and efficient onboarding

📧 Automation: Generation and email delivery of intake documents sent directly to the Admissions Department



FLOW 1️⃣: Student Inquiry Info to MS List + Email
This Power Automate flow streamlines the collection, storage, and forwarding of student information during the admissions process. Triggered by an HTTP request (from an intake form or external system), it automates the following tasks:

📝 Collect: Captures student details submitted via an online form

💾 Store: Saves the information in a structured Microsoft List

📄 Generate: Creates a formatted Word document populated with the student's data

📧 Send: Emails the document via institutional email to the Admissions Department for further processing

This automation reduces manual data handling, improves data consistency, and accelerates the enrollment workflow.



FLOW 2️⃣: Sync List on Approval – Information to Enrollment
This Power Automate flow automates the synchronization of student data between two SharePoint lists — Information Sheet and Enrollment Sheet — based on approval status. It ensures that only approved student records are transferred, maintaining data integrity and streamlining the enrollment process.

🚀 What It Does
Once a student record is approved:

🔔 Triggers automatically upon approval of a SharePoint list item

📖 Reads data from the Information Sheet list

✍️ Creates or updates a corresponding entry in the Enrollment Sheet list

🔄 Ensures data consistency between intake and enrollment records

🧩 Technologies Used
SharePoint Online – source and destination lists

Microsoft Power Automate – workflow orchestration



FLOW 3️⃣: 🎓 Student Intake to Admissions – Power Automate Flow
This Power Automate flow streamlines the collection, storage, and forwarding of student information during the admissions process. It reduces manual data handling, improves data consistency, and accelerates the enrollment workflow.

🚀 What It Does
Triggered by an HTTP request (typically from an online intake form or external system), this flow automates the following tasks:

📝 Collects student details submitted via an online form

💾 Stores the information in a structured Microsoft List

📄 Generates a formatted Word document populated with the student's data

📧 Sends the document via institutional email to the Admissions Department for further processing

🧩 Technologies Used
SharePoint Online – for structured data storage

Word Online (Business) – for document generation

Office 365 Outlook – for automated email delivery

