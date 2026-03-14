# Spring Core Employee Management

This project demonstrates a **simple Employee Management Module using Spring Core**.
It shows how **Inversion of Control (IoC) and Dependency Injection (DI)** work using Spring annotations.

Employee data is stored **in memory**, and beans are managed using **BeanFactory**.

---

## 📌 Features

* Employee creation and display
* Demonstrates **Spring IoC Container**
* Uses **Dependency Injection with @Autowired**
* Uses **@Component for bean creation**
* Uses **BeanFactory to manage beans**
* Stores employee data in **memory using ArrayList**

---

## 🧰 Technologies Used

* **Java**
* **Spring Core Framework**
* **Annotations (@Component, @Autowired)**
* **BeanFactory**
* **Maven / Java Project**

---

## 📂 Project Structure

```
SpringEmployeeManagement
│
├── Employee.java
├── EmployeeRepository.java
├── EmployeeService.java
├── AppConfig.java
└── MainApp.java
```

---

## ⚙️ Key Concepts

### Inversion of Control (IoC)

Spring manages object creation instead of the developer manually creating objects.

### Dependency Injection (DI)

Dependencies are injected automatically using:

```
@Autowired
```

### Component Annotation

Marks a class as a Spring Bean.

```
@Component
```

### BeanFactory

Responsible for creating and managing beans.

```
BeanFactory factory = new AnnotationConfigApplicationContext(AppConfig.class);
```

---

## ▶️ Program Output

```
Employee Added Successfully!
Employee Added Successfully!

Employee List:
Employee ID: 1 Name: Kiran Salary: 50000
Employee ID: 2 Name: Rahul Salary: 45000
```

---

## 🌍 Real-World Usage

This architecture is widely used in:

* HR management systems
* Enterprise applications
* Payroll systems
* Large Spring Boot applications

---

## 🚀 Future Improvements

* Add employee search
* Implement update and delete operations
* Connect to a real database
* Convert to a full **Spring Boot REST API**

---

## 👨‍💻 Author

**Done by KIRAN AKKALURI**

---

## 📜 License

This project is created for **learning and educational purposes**.
