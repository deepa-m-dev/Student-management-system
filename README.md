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


2️⃣ **Add a New Student**

- Click on Add New Student button.

- Fill in student details: Name, Email, Course, Phone.

- Click Save to add the student.

📸 Screenshot:

3️⃣ **Edit Student**

- From the student list, click Edit on a student record.

- Update the details and click Save.

📸 Screenshot:


4️⃣ **Delete Student**

- From the student list, click Delete.

- The student will be removed from the database.

📸 Screenshot:

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
