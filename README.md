# 📒 Address Book - Contact Manager Web App

A simple yet powerful Address Book application built with the **MERN Stack (MongoDB, Express, Angular, Node.js)**. This project allows users to manage contacts efficiently with functionalities to add, edit, delete, search, and export contact data.

## 🌟 Features

- 🔐 Basic Authentication (Login/Signup)
- ➕ Add, ✏️ Edit, ❌ Delete contact information
- 🔍 Search and filter contacts by name or email
- 📤 Export contacts as a CSV file
- 💾 Secure contact storage using MongoDB
- 📱 Responsive and intuitive UI built with Angular

## 🛠️ Tech Stack

| Layer        | Technology            |
|--------------|------------------------|
| Frontend     | Angular                |
| Backend      | Node.js + Express.js   |
| Database     | MongoDB (Mongoose)     |
| Authentication | JWT / Basic Auth     |
| Deployment   | Vercel / Netlify       |

## 🔧 API Endpoints

| Method | Endpoint           | Description                    |
|--------|--------------------|--------------------------------|
| GET    | `/api/contacts`    | Get all contacts               |
| POST   | `/api/contacts`    | Add a new contact              |
| GET    | `/api/contacts/:id`| Get contact by ID              |
| PUT    | `/api/contacts/:id`| Update contact by ID           |
| DELETE | `/api/contacts/:id`| Delete contact by ID           |

## 📂 Folder Structure

```bash
address-book/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   └── assets/
├── .env
├── README.md
