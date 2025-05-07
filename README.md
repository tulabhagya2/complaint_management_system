# 🛠 Complaint Management System

This project is a **web-based complaint management system** developed using **NetBeans IDE**, **Apache Tomcat**, **HTML/CSS/JavaScript**, and **MySQL**. It is designed to manage and track complaints efficiently for a banking product-based environment.

---

## 👤 Modules Overview

### 👨‍💼 Admin
- View, update, and delete user details
- View, update, and delete associate details
- View complaints, ratings, and solutions
- Assign complaints to associates

### 👤 User
- Submit complaints related to banking products
- Provide ratings and feedback
- Track status of complaints
- View solutions

### 🧑‍🔧 Associate
- View assigned complaints and resolve them
- Access user and associate details
- View other associate solutions
- Review ratings

---

## 🧰 Technologies Used

- **Frontend:** HTML, CSS, JavaScript, JSP
- **Backend:** Java Servlets (NetBeans IDE)
- **Database:** MySQL
- **Server:** Apache Tomcat

---

## 🗂️ Folder Structure

```
ComplaintManagementSystem/
├── nbproject/                         # NetBeans configuration files  
├── src/                               # Java source files (servlets, database)  
│   ├── admin/                         # Admin-related servlets  
│   ├── user/                          # User-related servlets  
│   ├── associate/                     # Associate-related servlets  
│   └── db/                            # Database connection classes  
├── Web Pages/                         # JSP files and frontend resources  
│   ├── META-INF/
│   ├── WEB-INF/
│   ├── admin.jsp
│   ├── admincon.jsp
│   ├── ahome.jsp
│   ├── assign_complaint.jsp
│   ├── asslogcon.jsp
│   ├── associatelogin.jsp
│   ├── associatereg.jsp
│   ├── associateview.jsp
│   ├── assergcon.jsp
│   ├── Associate.jsp
│   ├── check_complaint_status.jsp
│   ├── com.jsp
│   ├── comcon.jsp
│   ├── complaints.jsp
│   ├── delete.jsp
│   ├── delete2.jsp
│   ├── delete3.jsp
│   ├── do_assign.jsp
│   ├── error.jsp
│   ├── index.jsp
│   ├── ratings.jsp
│   ├── ratingscon.jsp
│   ├── ratingssuccess.jsp
│   ├── resolve_complaint1.jsp
│   ├── seecomplaints.jsp
│   ├── selectcon2.jsp
│   ├── selectcon3.jsp
│   ├── selectrole.jsp
│   ├── selectrole2.jsp
│   ├── selectrole3.jsp
│   ├── solution.jsp
│   ├── solutioncon.jsp
│   ├── submit_solution.jsp
│   ├── success.jsp
│   ├── success2.jsp
│   ├── update.jsp
│   ├── update2.jsp
│   ├── updatecon.jsp
│   ├── updatecon2.jsp
│   ├── userlogcon.jsp
│   ├── userlogin.jsp
│   ├── userreg.jsp
│   ├── userregcon.jsp
│   ├── view_status.jsp
│   ├── view_solution.jsp
│   ├── view_unresolved_complaints.jsp
│   ├── viewratings.jsp
│   ├── viewusers.jsp
│   └── viewusers1.jsp
├── database/
│   └── complaint_system.sql           # SQL file to set up database tables  
├── build.xml                          # Apache Ant build script  
├── README.md                          # Project documentation  
```

---

## 🚀 How to Run

1. Clone the repository to your system.
2. Open the project in NetBeans IDE.
3. Configure the MySQL database using `complaint_system.sql`.
4. Deploy the project on Apache Tomcat Server.

---

## 📌 Notes

- Make sure MySQL and Apache Tomcat services are running.
- Customize JSPs and database configurations as per your setup.

---

## 🙌 Acknowledgments

This project is developed for managing banking product complaints efficiently and transparently, improving customer support through structured tracking and feedback.
