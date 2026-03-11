# Online Food Delivery Project

A full-stack web application that allows customers to browse food items, place orders, and track deliveries.  
The system also provides an admin panel for managing food items and menus.

---

## Overview

This project demonstrates a simple online food ordering workflow with separate components for customers, administrators, and backend services.

The application includes:

- Customer interface for browsing and ordering food
- Admin dashboard for managing menu items
- Backend API for handling requests and data processing

---

## Project Structure

```
online-food-delivery-project
│
├── adminpanel/        # Admin dashboard
├── foodies/           # Customer frontend
├── foodiesapi/        # Backend API
├── food_images/       # Image assets
│
├── Foodies API.postman_collection.json
└── Steps to run the project.txt
```

---

## Features

- Role-based authentication system
- Customer food browsing and ordering
- Cart and order management
- Admin CRUD operations for menu items
- API testing using Postman collection

---

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/himangshugayan77/online-food-delivery-project.git
cd online-food-delivery-project
```

### 2. Run Backend

```bash
cd foodiesapi
npm install
npm start
```

### 3. Run Frontend

Open the following folders in a browser or serve them with a local server:

```
foodies/
adminpanel/
```

---

## API Testing

The repository includes a Postman collection:

```
Foodies API.postman_collection.json
```

Import this file into Postman to test the backend API endpoints.

---

## Technologies Used

- HTML
- CSS
- JavaScript
- Node.js
- REST API

---
