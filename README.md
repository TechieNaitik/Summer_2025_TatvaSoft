# 📘 Summer Internship Project – 2025  
**Virtual Community Support Platform**  
_Full-Stack Web Application (Angular + .NET + PostgreSQL)_

---

## 🚀 Project Overview  
This project was developed during a **15-day Summer Internship Program (2025)**.  
It is a full-stack web application designed to manage:

- Missions  
- Mission Themes  
- Mission Skills  
- Mission Applications  
- User Profile  
- Role-Based Authorization  

The platform supports both **Admin** and **User** functionalities.

---

## 🧩 Technologies Used

| Layer        | Technology |
|--------------|------------|
| **Frontend** | Angular (`ci_platfrom_app-develop` folder) |
| **Backend**  | .NET Web API (`Mission` folder) |
| **Database** | PostgreSQL |
| **ORM**      | Entity Framework (Code First) |
| **Architecture** | N-Tier + Repository Pattern |
| **Auth**     | Authentication + Role-Based Authorization |
| **Tools**    | Swagger, VS Code, Visual Studio |

---

## 📂 Project Structure

```
/
├── Mission/                     # Backend (.NET Web API)
├── ci_platfrom_app-develop/     # Frontend (Angular)
├── Commands                      # Command notes
├── STEPS FOR FRONTEND SETUP     # Setup instructions for UI
└── Docs/                        # Local documentation (ignored from GitHub)
```

---

# ⚙️ Setup Instructions

## 🛠 Backend Setup (.NET)

1. Open the **Mission** folder in **Visual Studio**
2. Restore NuGet packages  
3. Update PostgreSQL connection string in `appsettings.json`
4. Run the API using IIS Express / Kestrel  
5. Swagger will be available at:  
   ```
   https://localhost:<port>/swagger
   ```

---

## 💻 Frontend Setup (Angular)

1. Navigate to the **ci_platfrom_app-develop** folder
2. Install packages:
   ```bash
   npm install
   ```
3. Run the project:
   ```bash
   ng serve --open
   ```
4. Refer to **“STEPS FOR FRONTEND SETUP”** for more details.

---

# 📚 15-Day Summer Internship Training Plan (2025)

Below is the summary of the official internship curriculum based on the provided document.

---

## 🗓 Day-by-Day Breakdown

### **Day 1 — Introduction to PostgreSQL**
- SQL basics  
- CI Platform DB schema  
- CRUD operations + sub-queries  

### **Day 2 — Introduction to Angular**
- Angular basics  
- Components, forms, routing  
- Build a simple app  

### **Day 3 — Introduction to .NET**
- .NET Web API  
- Swagger  
- N-Tier + Repository pattern  
- Entity Framework overview  

### **Day 4 — Code First + LINQ + Login API**
- EF Code-First approach  
- LINQ operations  
- Create login API  

### **Day 5 — Authentication & Authorization**
- Auth basics  
- Implement project-level authentication  

### **Day 6 — Role-Based Authorization**
- Admin vs User roles  
- Access control  
- Login functionality  

### **Day 7 — User Retrieval**
- LINQ joins  
- Sorting, filtering, paging  
- Basic CRUD  

### **Day 8 — Mission CRUD**
- Insert, update, delete mission records  

### **Day 9 — Mission Theme CRUD**
- CRUD on mission themes  

### **Day 10 — Mission Skill CRUD**
- CRUD on mission skills  

### **Day 11 — Mission Listing (User Side)**
- Display mission data on user UI  

### **Day 12 — Mission Apply + Mission Application CRUD**
- Apply for missions  
- CRUD operations on applications  
- Filtering + searching  

### **Day 13 — My Profile & Deployment**
- Implement profile page  
- Deployment strategies discussion  

### **Day 14 — Discussion & Review**

### **Day 15 — AWS Session**
- AWS services introduction  
- Deployment overview  

---

# 🎯 Features Implemented

### 👤 **User Module**
- View missions  
- Apply for missions  
- Manage profile  
- View application history  

### 🛠 **Admin Module**
- Manage missions  
- Manage themes & skills  
- CRUD operations for all entities  
- Manage users  

### 🔐 **Security Features**
- User authentication  
- Role-based authorization  

---

# 📝 Conclusion  
This project demonstrates a complete **end-to-end full-stack application** built using:  
**Angular + .NET Web API + PostgreSQL + EF Core**, following a structured 15-day internship curriculum.

---

