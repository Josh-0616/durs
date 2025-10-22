# 📘 PCR Performance Commitment and Review System  

## 🏫 Overview  
The **PCR System** (Performance Commitment and Review) is a web-based platform developed for **Philippine Countryville College, Inc.** It allows administrators, faculty to manage performance evaluations, submissions, and ratings digitally.  

This system streamlines the evaluation process by allowing users to submit PCR forms, track performance, and generate reports efficiently.  

---

## ⚙️ Features  

### 👩‍💼 Admin Panel  
- Manage users (faculty)  
- View, approve, and rate PCR submissions  
- Generate reports per department  
- View analytics and statistics  
- Manage announcements and deadlines  
- Recycle bin and restore options  
- Dark/Light mode toggle  

### 👨‍🏫 Faculty Panel  
- Submit and edit IPCR forms  
- View submission history and total submissions  
- Track PCR status (Pending, Reviewed, Approved)  
- View announcements and deadlines  
- Generate personal PCR reports in PDF  
- Manage account and change password  
- Recycle bin for deleted submissions  
- Dark/Light mode toggle  

---

## 🧰 Technologies Used  
- **Frontend:** HTML5, CSS3, Bootstrap 5  
- **Backend:** PHP 8  
- **Database:** MySQL  
- **PDF Generation:** TCPDF 
- **JavaScript:** Chart.js for analytics  
- **Authentication:** PHP Session-based Login + Google Sign-In  
- **UI Design:** Glassmorphism & Soft Modern UI with Responsive Design  

---

## 🗄️ Database Structure  
**Database Name:** `apps_pcc_db`  

Main tables:
- `users` — stores account details and roles (admin, faculty, staff)  
- `ipcr_forms` — stores submitted IPCR form data  
- `ipcr_entries` — stores IPCR performance indicators  
- `ratings` — stores admin ratings and remarks  
- `logs` — activity logs  
- `notifications` — announcement and alert system  

---

## 📂 Project Folder Structure  




