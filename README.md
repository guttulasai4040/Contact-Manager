
## 📌 Project Description: Contact Manager

The **Contact Manager** is a **Spring Boot-based CRUD application** that allows users to efficiently manage their personal or professional contacts. It works like a **digital phonebook**, enabling the storage and retrieval of essential contact details such as **name, phone number, email, and address**.

The system is built using **Spring Boot, Spring Data JPA, MySQL, and REST APIs**. It follows a clean **layered architecture** with entities, repositories, services, controllers, and DTOs to ensure **scalability, maintainability, and separation of concerns**.

### 🔹 Key Features:

1. **Add New Contacts** → Users can create and save new contacts with details like name, phone, email, and address.
2. **View Contacts** → Users can retrieve all contacts or fetch a specific one by ID.
3. **Update Contacts** → Modify existing contact details when needed.
4. **Delete Contacts** → Remove unwanted or outdated contacts.
5. **Validation** → Ensures data integrity (e.g., valid email format, required name/phone).
6. **Error Handling** → Custom exceptions for contact not found, with clear JSON responses.
7. **DTO Layer** → Separates request/response objects from database entities for cleaner APIs.

### 🔹 Tech Stack:

* **Backend:** Java, Spring Boot
* **Database:** MySQL (with Spring Data JPA for ORM)
* **Build Tool:** Maven
* **Testing APIs:** Postman (via JSON collection)
* **Lombok:** For reducing boilerplate code

### 🔹 How It Works:

* A user (via Postman or frontend) sends API requests (e.g., **POST /contacts**) with JSON data.
* The request is validated using **DTOs & Validation annotations**.
* The **Service layer** handles business logic and interacts with the **Repository layer** (which talks to MySQL).
* The response is returned as a clean **DTO JSON response**.

### 🔹 Example Flow:

1. **POST** `/contacts` → Create a new contact.
2. **GET** `/contacts` → Fetch all contacts.
3. **PUT** `/contacts/{id}` → Update a contact by ID.
4. **DELETE** `/contacts/{id}` → Delete a contact by ID..

---



👉 Do you want me to also prepare a **README.md file** (GitHub-style documentation) with setup instructions and API usage so it looks professional if you upload it?
