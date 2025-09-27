# 📚 Student Management System

A simple **Spring Boot CRUD application** using **Thymeleaf** and **Spring Data JPA**.  
It allows you to manage student records (Add, Edit, Delete, List) with a clean **Bootstrap + custom CSS UI**.

---

## 🚀 Features
- ➕ Add new student  
- 📝 Edit student details  
- ❌ Delete student  
- 📋 View all students in a table  
- 🌐 Neon-themed Bootstrap UI with hover effects  

---

## 🛠️ Tech Stack
- **Backend:** Spring Boot, Spring MVC, Spring Data JPA (Hibernate)  
- **Frontend:** Thymeleaf, Bootstrap 5, Custom CSS  
- **Database:** H2 (in-memory) / MySQL (configurable)  
- **Build Tool:** Maven  

---

## 📂 Project Structure
src/main/java/com/example/demo
│

├── controller

│ └── StudentController.java

│

├── model

│ └── Student.java

│

├── repository

│ └── studentRepository.java

│

├── service

│ ├── StudentService.java

│ └── StudentServiced.java

│

└── DemoApplication.java


**Thymeleaf Templates (Frontend):**
src/main/resources/templates

│

├── student.html # Student list page (View/Delete/Edit)

└── add-student.html # Add or Edit student form

---

## ⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/student-management.git
   cd student-management
2. **Build the project with Maven**
    ```bash
    mvn clean install
3. **Run the application**
   ```bash
   mvn spring-boot:run
4. **Open in your browser:** 
   ```bash
   http://localhost:8080

## 🖥️ Usage (Step-by-Step)
1️⃣ **View Student List**

- Navigate to the home page (/).

- You will see all students displayed in a table with Edit and Delete buttons.

📸 Screenshot:<img width="1920" height="1037" alt="sms2" src="https://github.com/user-attachments/assets/275fe209-dcd6-4c4d-8cda-a81a12434db6" />
<img width="1920" height="1037" alt="sms2" src="https://github.com/user-attachments/assets/d596e592-6137-4b0c-8b4c-043fb527e50c" />



2️⃣ **Add a New Student**

- Click on Add New Student button.

- Fill in student details: Name, Email, Course, Phone.

- Click Save to add the student.

📸 Screenshot:
<img width="1920" height="1035" alt="sms8" src="https://github.com/user-attachments/assets/ba0dd491-aa87-434a-aa5e-911da1228ce1" />

<img width="1920" height="1039" alt="sms3" src="https://github.com/user-attachments/assets/adcf77a6-d5db-4a1a-a767-63ea558776d5" />


3️⃣ **Edit Student**

- From the student list, click Edit on a student record.

- Update the details and click Save.

📸 Screenshot:
<img width="1920" height="1035" alt="sms4" src="https://github.com/user-attachments/assets/d44d0acb-a625-4524-835e-197ba6537f02" />

<img width="1920" height="1035" alt="sms5" src="https://github.com/user-attachments/assets/17e9cdb1-4444-4a7a-83d0-cdf94a481d06" />


4️⃣ **Delete Student**

- From the student list, click Delete.

- The student will be removed from the database.

📸 Screenshot:
<img width="1920" height="1033" alt="sms6" src="https://github.com/user-attachments/assets/4914687c-7f35-4abc-a7cb-370f7555aeee" />
<img width="1920" height="1032" alt="sms7" src="https://github.com/user-attachments/assets/97b6beee-2d8b-4f30-93fb-c6dbf8782269" />

## 🔧 Database Configuration

By default, the project uses H2 in-memory database.
To switch to MySQL, update application.properties in:

src/main/resources/application.properties

 **Example for MySQL:**

    ```properties:
    spring.datasource.url=jdbc:mysql://localhost:3306/studentdb
    spring.datasource.username=root
    spring.datasource.password=yourpassword
    spring.jpa.hibernate.ddl-auto=update

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit pull requests.

## 📜 License

This project is licensed under the MIT License.

## 👨‍💻 Author
Deepa M
GitHub: deepa-m-dev
