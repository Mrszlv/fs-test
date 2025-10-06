# Food Ordering Web App — MERN Stack

A full-stack **Food Ordering Web Application** built using the **MERN stack** (MongoDB, Express, React, Node.js).  
Includes customer and admin interfaces with authentication, Stripe payments, and order management.

---

## Problems (to fix)

### Authentication Fixes

- **Login:** Return `401 Unauthorized` if credentials are incorrect (currently returns `200 OK`).
- **Registration:** Return `401 Unauthorized` if the user already exists (currently returns `200 OK`).

### UI Enhancements

- Add a **zoom-in hover effect** for each menu image.

### Order UI Fix

- Ensure the **minus (–)** icon remains aligned when quantity changes.

---

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Backend Setup](#backend-setup)
- [Frontend Setup](#frontend-setup)
- [Admin Setup](#admin-setup)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [API Documentation](#api-documentation)

---

## Introduction

This project is a **food ordering system** with a customer-facing app for browsing and purchasing food,  
and an **admin dashboard** for managing orders and menu items.

---

## Features

- User authentication (JWT)
- Browse and filter menu items
- Add to cart, edit quantities, and place orders
- Stripe integration for secure payments
- Order tracking (user + admin)
- Admin panel for managing menu and orders

---

## Technologies Used

| Layer          | Stack                               |
| -------------- | ----------------------------------- |
| Frontend       | React.js, Context API, React Router |
| Backend        | Node.js, Express.js                 |
| Database       | MongoDB                             |
| Authentication | JWT                                 |
| Payments       | Stripe                              |
| Styling        | CSS / Custom UI                     |

---

## Installation

STRIPE_SECRET_KEY="your_stripe_secret_key_here"

### Prerequisites

- Node.js ≥ 18
- MongoDB running locally or cloud (e.g., MongoDB Atlas)

---

### Clone the Repository

```bash
git clone https://github.com/Mrszlv/fs-test.git
cd fs-test
```

## Demo

Loom: https://www.loom.com/share/75a005f710e44452878e2828a9b9864e
