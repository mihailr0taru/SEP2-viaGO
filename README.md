# viaGO

viaGO is a **vehicle reservation system for students at VIA University College**.  
It allows students to **reserve and return scooters, bikes, and e-bikes** in a shared student-only environment.

---

## Tech Stack

- Java
- JavaFX
- PostgreSQL
- Socket Networking
- MVC Architecture

---

## Features

- Reserve available vehicles
- Return rented vehicles
- Client-server communication
- User authentication
- Database storage for vehicles and reservations
- JavaFX graphical interface

---

## Architecture

```
JavaFX Client
     │
     │ Sockets
     ▼
Java Server
     │
     ▼
PostgreSQL Database
```

---

## Project Structure

```
src
 ├── client
 ├── server
 ├── model
 ├── networking
 ├── database
 └── utility
```

---

## Running the Project

1. Start the **server**
2. Launch the **JavaFX client**

Make sure the **PostgreSQL database is running and configured**.

---

## Purpose

This project was developed as part of a **Software Engineering course at VIA University College**.
