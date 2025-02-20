
# 🎯 Task Management App - Backend

This is the **backend** of the Task Management App, built using the **Godspeed Framework** and **Prisma ORM**. It currently supports basic **CRUD operations** for managing tasks and serves as a foundation for adding more features in the future.

---

## 🚀 Features

- **CRUD Operations**:
  - Create tasks
  - Read tasks (view all or specific tasks)
  - Update tasks
  - Delete tasks

- **Database Management**: Integrated with **Prisma ORM** for efficient database operations.

---

## 🛠️ Tech Stack

- **Backend Framework**: Godspeed
- **Database ORM**: Prisma
- **Database**: mongoDB atlas (configurable)

---


---

## 📋 API Endpoints

### Tasks Endpoints
| Method | Endpoint       | Description             |
|--------|----------------|-------------------------|
| GET    | `/tasks`       | Get all tasks          |
| POST   | `/tasks`       | Create a new task      |
| GET    | `/tasks/:id`   | Get a specific task    |
| PUT    | `/tasks/:id`   | Update a specific task |
| DELETE | `/tasks/:id`   | Delete a specific task |

--

## Future Plans

Add user authentication with JWT
Implement task filters (by deadline, status, etc.)
Role-based access (Admin/User)
Email notifications for task deadlines


## Acknowledgments
Special thanks to Dharuv Marchanda and the Godspeed team for their incredible support and for introducing me to this fantastic framework.



