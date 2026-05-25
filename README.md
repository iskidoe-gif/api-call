# Postman API-Testing/API-CALL

## Author & Course
Jonathan L. Ordonio
III - BSIT - B

---

## Project Title
Postman API-Testing

---

## Project Description
Postman API-Testing/API-CALL is a simple RESTful API built using Laravel.  
This project allows users to manage student records through CRUD operations (Create, Read, Update, Delete). It supports JSON responses and API testing using Postman.

### Features
- Fetch/Retrieve All Students Data
- Fetch/Retrieve Single Student Data
- Insert/Add Student Data
- Update/Modify Student Data
- Update/Modify Specific Student Data
- Delete All Student Data
- Delete Specific Student Data

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/iskidoe-gif/api-call
```

### 2. Go to Project Directory

```bash
cd api-call
```

### 3. Install Dependencies

```bash
composer install
```

### 4. Configure Environment

Copy `.env.example` file to `.env`

```bash
cp .env.example .env
```

### 5. Generate Application Key

```bash
php artisan key:generate
```

### 6. Run Database Migration

```bash
php artisan migrate:fresh
```

### 7. Start Laravel Server

```bash
php artisan serve
```

### 8. Test API in Postman

Base URL:

```txt
http://127.0.0.1:8000/api
```

### Example Endpoints

```http
GET /students
GET /students/{id}
POST /students
PUT /students/{id}
PATCH /students/{id}
DELETE /students/{id}
DELETE /students
```

---

## Note

This project is for educational purposes only.

## Screen Record Video
https://drive.google.com/drive/folders/1kQJI6fk2toql9g9qaV4DnDxsC_CCddEM