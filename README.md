
# Student Result Analysis & Email Automation Agent

An automated student result distribution system built using **n8n, Microsoft Excel, and Gmail**. It processes student marks from an uploaded Excel file, generates personalized result reports, sends emails to students, and provides the teacher with a summary of email delivery status.

## 📌 Project Overview

Manually preparing and sending result emails to individual students can be time-consuming. This project automates the process using an n8n workflow.

The teacher uploads an Excel file containing student information and subject-wise marks and provides their email address. The workflow processes the data, generates personalized HTML result reports, sends emails through Gmail, and sends a final confirmation email to the teacher.

## ✨ Features

- 📂 Excel file upload through an n8n form.
- 📊 Automatic extraction of student details and subject-wise marks.
- ✅ Validation of student records and email addresses.
- 📧 Personalized HTML result reports with colourful marks tables.
- 👨‍🎓 Individual result emails for students.
- 📩 Teacher confirmation email after processing.
- ⚠️ Handling of invalid records and email-sending errors.
- 📈 Summary of successful, failed, and skipped email attempts.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Microsoft Excel | Storing student details and marks |
| Gmail | Sending student result reports |
| HTML | Designing personalized email reports |
| JavaScript | Data processing and report generation within the workflow |

## ⚙️ System Workflow

1. **Teacher Upload:** The teacher uploads an Excel file and enters their email address.
2. **Excel Processing:** The workflow extracts student details and subject-wise marks.
3. **Data Validation:** Student records and email addresses are checked.
4. **Report Generation:** A personalized HTML result report is created for each valid student record.
5. **Student Email Delivery:** The result reports are sent to students through Gmail.
6. **Status Handling:** Successful, failed, and skipped email attempts are tracked.
7. **Teacher Confirmation:** A summary email is sent to the teacher after processing.

## 📋 Sample Excel File Structure

The Excel file should contain student information and subject-wise marks.

| Roll Number | Student Name | Email | Python | Java | SQL |
|---|---|---|---:|---:|---:|
| 101 | Aarav Sharma | aarav@example.com | 28 | 25 | 27 |
| 102 | Riya Patil | riya@example.com | 26 | 29 | 28 |

*Note: The above records are examples for demonstration only. Use valid email addresses when testing email delivery.*

The workflow should support different subject columns, provided the uploaded file follows the expected student-data structure.

## 📧 Email Output

### Student Result Email

Each student receives an individual email containing:
- Student name
- Roll number
- Subject-wise marks table
- A personalized result report in HTML format

### Teacher Confirmation Email

After processing the student records, the teacher receives a summary containing:
- Number of emails sent successfully
- Number of failed email attempts
- Number of skipped records

## 🚀 How to Use

1. Open the published n8n form.
2. Upload an Excel file containing student details and marks.
3. Enter the teacher's email address.
4. Submit the form.
5. Allow the workflow to process the records and send student result emails.
6. Check the teacher's inbox for the final processing summary.

**Requirements:** An active n8n workflow, correctly configured Gmail credentials, a valid Excel file, and valid recipient email addresses.

## 🔒 Security

- Do not upload real student records or confidential academic information.
- Never publish Gmail credentials, API tokens, OAuth tokens, or passwords.
- Use dummy student data for demonstrations.
- Protect student email addresses and other personal information.

## 🎯 Project Objectives

- Automate student result distribution.
- Reduce repetitive manual work for teachers.
- Generate clear and professional result reports.
- Simplify email delivery tracking.
- Improve the efficiency of academic communication.

## 🔮 Future Scope

- Add performance charts for individual students.
- Develop a dashboard to monitor email delivery.
- Add multilingual result reports.
- Integrate with college management systems.
- Improve duplicate-record detection and error reporting.

## 👩‍💻 Author

**Samruddhi Budde**

Computer Science Engineering Student

- GitHub: https://github.com/buddesamruddhi



*This project demonstrates workflow automation, spreadsheet processing, HTML email generation, and Gmail integration using n8n.*
