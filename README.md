 🎓 ScholarEase – Smarter Scholarship Management

**ScholarEase** is a database-driven platform built to streamline and modernize how scholarship programs are managed by educational institutions, government agencies, and foundations. It’s designed with accessibility, transparency, and automation in mind to ensure that scholarships are awarded fairly, efficiently, and with minimal manual effort.

---
 📌 Project Overview

ScholarEase replaces manual, error-prone scholarship processes with a secure, integrated, and fully digital workflow. Students apply through a user-friendly portal, while administrators, reviewers, and financial teams collaborate seamlessly through shared dashboards, eligibility checks, and automated decision support.

This repository contains the complete **MySQL database schema** powering ScholarEase — ready to be deployed, extended, or integrated into larger systems.

---

## 🧠 Key Features

- **Automated Eligibility Checks**  
  Filters applicants based on academic records, financial need, extracurriculars, and more.

- **End-to-End Workflow**  
  From application submission to award disbursement, everything is tracked and stored securely.

- **Reviewer Collaboration**  
  Built-in scoring, review logs, and decision tools for scholarship committees.

- **Accessibility First**  
  Screen reader support, keyboard navigation, adjustable font sizes — designed for everyone.

- **Secure Messaging**  
  Students and administrators can communicate directly via the system for updates and decisions.

- **Real-Time Reporting**  
  Gain insights into fund usage, recipient demographics, and program performance.

---

 📊 Tables Included

| Table               | Purpose                                              |
|--------------------|------------------------------------------------------|
| `Student`          | Stores student information                          |
| `Department`       | Academic departments linked to students/faculty     |
| `Faculty`          | Faculty serving as reviewers or mentors             |
| `Application`      | Submitted scholarship applications                  |
| `Scholarship`      | Defined scholarship opportunities                   |
| `Criteria`         | Eligibility and scoring rules                        |
| `Reviewer`         | Reviewers who score and assess applications         |
| `Review`           | Scores and feedback tied to reviewers and applicants|
| `Award`            | Records of awarded scholarships                     |
| `Disbursement`     | Financial disbursement logs                         |
| `DisbursementMethod` | Payment methods (check, bank transfer, etc.)     |
| `Institution`      | Info about participating colleges/universities      |
| `ReportingPeriod`  | Defines application cycles and deadlines            |
| `Report`           | Aggregated output for analysis or auditing          |

---

 🚀 How to Use

### 🛠 Requirements
- MySQL 8.x or compatible
- MySQL Workbench (recommended for visualization)
- Optional: Lucidchart for ERD modeling

 🔧 Importing the Database

Once you have the exported `ScholarEase.sql`:

```bash
mysql -u root -p ScholarEase < ScholarEase.sql
