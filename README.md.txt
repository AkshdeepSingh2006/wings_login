# Wings Login System

##  Project Structure

* frontend → Flutter app
* backend → Spring Boot API
* database → PostgreSQL dump

---

##  Setup Instructions

### 1. Database

* install PostgreSQL
* Create an empty database and name it Coaching_mgmt
* restore the backup file or run the .sql file in query tool

---

### 2. Backend

* Open `backend/` in VS Code
* Update DB username/password in `application.properties`
* Run Spring Boot app in terminal using ./mvnw spring-boot:run 

---

### 3. Frontend

```bash
cd frontend/login_page_wings
flutter pub get
flutter run
```

---

## ⚠️ Notes

* Backend must run before Flutter
* Update DB credentials before running
* this is a simple role based login page cybersecurity features are yet to be added 