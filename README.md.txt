# Student Enrollment Form

This project is a simple web-based form to manage student enrollments using **JsonPowerDB**.

## 📋 Project Description

- Student Enrollment Form using HTML, JavaScript, JsonPowerDB.
- Form allows **Saving**, **Updating**, and **Resetting** records.
- Uses JsonPowerDB for backend database storage.
- Database and table are auto-created on first insert.

## 🛠 Technologies Used

- HTML
- JavaScript
- JsonPowerDB (backend)
- Talend API Tester (for testing APIs)

## 🏛 Database Information

- **Database Name**: `schoolDB`
- **Relation/Table Name**: `STUDENT-TABLE`
- **Primary Key**: `Roll-No`

## 📑 Form Fields

| Field Name         | Type    |
|---------------------|---------|
| Roll-No             | Integer |
| Full-Name           | String  |
| Class               | String  |
| Birth-Date          | Date    |
| Address             | String  |
| Enrollment-Date     | Date    |

## 📈 Features

- Add new student records.
- Update existing records.
- Reset form inputs.

## 🚀 How to Run Locally

1. Clone or Download this repository.
2. Open `index.html` in your browser.
3. Replace your `connToken` in `form.js` file with your JsonPowerDB token.
4. Start adding/updating student records.

## 🌐 API Endpoints Used

| API Purpose    | URL | Command |
|----------------|-----|---------|
| Insert (Save)  | `/api/iml` | PUT |
| Read (Find)    | `/api/irl` | GET_BY_KEY |
| Update         | `/api/iml` | UPDATE |

## 🔥 Benefits of JsonPowerDB

- Easy NoSQL database.
- CRUD operations using simple HTTP APIs.
- Fast and lightweight.
- Ideal for mini projects.

## 📝 Release History

- v1.0 - Initial Release (April 2025)

---

